# Premium Hospital CVD App

This is a Render-ready Flask + Docker project with a premium healthcare-style frontend.

## Deploy
1. Create a new GitHub repo
2. Upload all files from this folder
3. Commit and push
4. In Render, create a new Web Service from the repo
5. Use Docker environment
6. Deploy

Render will use the Dockerfile automatically.

## Real model
Place your saved model file here before pushing for real predictions:
model/cvd_logreg_pipeline.joblib

If the model file is missing, the app still runs using a safe fallback scoring system so the UI can be demonstrated immediately.
