# Cloud Run Button

Your own fancy button that uses Cloud Shell to deploy a git repo to Cloud Run in two clicks.

Like this:  

[![Run on Google Cloud](https://storage.googleapis.com/cloudrun/button.png)](https://console.cloud.google.com/cloudshell/editor?shellonly=true&cloudshell_image=gcr.io/cloudrun/button&cloudshell_git_repo=https://github.com/jamesward/cloud-run-button.git)

To add a Cloud Run deploy button to your project's readme:

1. Copy & paste this markdown:

    ```
    [![Run on Google Cloud](https://storage.googleapis.com/cloudrun/button.png)](https://console.cloud.google.com/cloudshell/editor?shellonly=true&cloudshell_image=gcr.io/cloudrun/button&cloudshell_git_repo=YOUR_HTTP_GIT_URL)
    ```

1. Replace `YOUR_HTTP_GIT_URL` with your HTTP git URL, like: `https://github.com/jamesward/hello-kotlin-ktor.git`

1. Make sure the repo is buildable on Google Cloud Build and its build config publishes a container to the Google Container Repository.  If you use a `cloudbuild.yaml` file, the publishing config must use `PROJECT_ID` and `REPO_NAME` parameters.

# Note To Shelf

Run this before any job application and close down the cloud resources after 4 weeks.

### Current Deployment

`hello-kotlin-ktor`

06-05-2019 | [My Repository on GCP](gcr.io/metal-smithy-160112/hello-kotlin-ktor) | [Live Deployment](https://hello-kotlin-ktor-ddyywwp6la-uc.a.run.app/)

