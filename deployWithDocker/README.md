# Deploy a model server


1. Build the `model_server` docker image: `docker build`.
2. Push the `model_server` docker image to your public dockerhub account: `docker push`.
3. Initiate terraform: `terraform init`.
4. Check the terraform plan: `terraform plan`.
5. Execute the plan, supplying the dockerhub URI when prompted: `terraform make`.
6. Ping the server at the returned IP address.