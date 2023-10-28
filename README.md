# node-microservice-boilerplate
### Services
1. User Service
2. Order Service
3. Inventory Service
4. API Gateway
### Commands
- To recreate changed services and run on docker
    ```bash
    npm run docker-up
    ```
- To spin services on kubernetes cluster
    ```bash
    npm run k8s-up
    ```
- To tunnel services on kubernetes cluster
   ```bash
   minikube service <service-name>
   ```
   Eg:
   ```bash
   minikube service api-gateway
   ```
- To run tests on a service
  ```bash 
  cd ./path/to/service
  npm jest
  ```
