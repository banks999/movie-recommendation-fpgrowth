# Movie Recommendation System using FP-Growth  

This project implements a movie recommendation engine on the **MovieLens dataset** using the **FP-Growth algorithm** for frequent itemset mining.  

## Features
- Association rule mining on user ratings (>= 4 stars).  
- Frequent itemset discovery with `mlxtend`.  
- Movie recommendations: "Users who liked X also liked Y".  
- Clean, tabulated outputs using `tabulate`.  

## Tech Stack
- Python, Pandas, mlxtend, Tabulate

## Dataset Link
- https://grouplens.org/datasets/movielens/32m/

## How to Run
```bash
pip install -r requirements.txt
python fpgrowth_recommender.py
