# cloud-functions-demo
GCP Cloud Function demo app

1. Open your cloud shell 
2.  mkdir ~/helloworld
    cd ~/helloworld
3. git clone this repo
4. mvn clean install
5. mvn function:run to test it locally
6. curl localhost:8080 from another cloud shell to check
7. gcloud functions deploy my-first-function --entry-point functions.HelloWorld --runtime java11 --trigger-http --memory 512MB --allow-unauthenticated
   to create function
8. gcloud functions describe my-first-function 
   to check URL of function 
