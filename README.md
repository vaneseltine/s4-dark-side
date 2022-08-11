# s4-dark-side

Science of Science Summer School (S4) 2022 #project-dark-side

## Notebooks

### 1_fetch.ipynb

Scrape retracted and up to 200 journal-year-matched-unretracted json records from OpenAlex

### 2_collate.ipynb

Combine retracted and (as run, up to 20) unretracted (as run, n = 113,937) into single file

### 3_core_df.ipynb

Build core_df, the article-level dataframe with retracted and control measures

### 4_disruptiveness.ipynb

Scrape and calculate (simultaneously -- too large to cache) Funk & Owen-Smith-style disruptiveness measure

### reduce_shibayama_results.ipynb

Take in raw shibayama novelty results and output the bare minimum of work ID, abstract, title scores

### 5_analysis_df.ipynb

Merge together the core dataframe with outcomes (disruptiveness and novelty) to create analysis dataset

### 6_modeling.ipynb

Do some analysis

## Data

### ./data/shibayama

output from reduce_shibayama_results.ipynb

### ./data/core_df.feather

output from 3_core_df.ipynb

### ./data/analysis_df.feather

output from 5_analysis_df.ipynb
