# Entity Resolution with Blocking and Fuzzy Matching

This project solves the Entity Resolution challenge using:
- Preprocessing and fuzzy name/location/tag similarity
- Blocking strategy for performance
- Clustering based on similarity threshold

## Features
- Blocking to reduce comparisons
- RapidFuzz for fast string similarity
- Clean clustering

## How to Run
1. Upload the document you want to check in `data_set/`
2. Update the path
`df = pd.read_parquet("data_set/Your_File_Name", engine="pyarrow")`


## Output
- `result/resolved_entities.csv`: clusters of resolved entities