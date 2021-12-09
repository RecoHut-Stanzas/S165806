# Group Playlist Recommender

In many social situations, like parties and road trips, groups of people with different music tastes will listen to music together. It's hard to please everyone, and it's even harder if you don't know what each person likes. There are multiple ways to synthesize the preferences of a group. Should you average their preferences? Should you try to make sure that no one hates the choices at the cost of excluding someone's favorites? This tutorial explores these questions by first generating a music profile for each person, and then applying different strategies to combine their preferences into a single playlist.

## Project structure
```
.
├── [ 59M]  artifacts
│   ├── [ 10M]  le_item.pkl
│   ├── [ 49M]  le_user.pkl
│   └── [4.0K]  models
├── [ 44M]  data
│   ├── [4.0K]  bronze
│   └── [ 44M]  silver
│       ├── [5.8M]  test.parquet.gz
│       └── [ 38M]  train.parquet.gz
├── [ 23K]  images
│   └── [ 19K]  process_flow.svg
├── [ 66K]  nbs
│   └── [ 62K]  P969119_Group_Playlist_Recommendations_on_Million_Songs_Dataset_using_Surprise_SVD_and_NMF_Model.ipynb
├── [ 38M]  outputs
│   ├── [  50]  eval_results.csv
│   ├── [ 38M]  model_result_ensemble.csv
│   ├── [ 510]  rankings_avg.csv
│   └── [  53]  results.csv
└── [2.0K]  README.md

 141M used in 8 directories, 11 files
```