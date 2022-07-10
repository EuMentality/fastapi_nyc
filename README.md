Backend Heroku Organization 
===============
    ├── model
    │   ├── catboost.bin         <- Trained Catboost model.
    │   └── kmeans.pkl           <- Trained K-means model.
    │
    ├── src
    │   ├── __init__.py          <- Make src a Python module.
    │   ├── add_features.py      <- Add features for tuning or predicting.
    │   └── make_prediction.py   <- Predict trip duration: frontend request.
    │                     
    ├── README.md                <- Backend Description.
    │
    ├── app.py                   <- FastAPI backend app.
    │
    ├── Procfile                 <- Heroku Configuration
    │
    └── requirements.txt         <- Requirements for env.
