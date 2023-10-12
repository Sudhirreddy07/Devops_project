# **Devops_project**

## This project Interact with following Tools
```
     1. Jenkins
     2. Docker
     3. kubernetes(EKS)
     4. MongoDB
     5. ReactJS
     6. Flask
```
> 1. **Jenkins:** Jenkins is an open source automation server. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration, and continuous delivery.

> 2. Docker: The docker is used to build, test and deploy the application quickly. In docker, we can quickly deplioy and scale application into any environment.

> 3. Kubernetes(EKS): EKS is a cloud based container mangement service that is natively used for deploy application. EKS service automatically manage and scaleble clustur of cloud services.

> 4. MangoDB: MongoDB is a non-relational document database that provides support for JSON-like storage. The MongoDB database has a flexible data model that enables you to store unstructured data, and it provides full indexing support, and replication with rich and intuitive APIs.

> 5. The React. js framework is an open-source JavaScript framework and library developed by Facebook. It's used for building interactive user interfaces and web applications quickly and efficiently with significantly less code than you would with vanilla JavaScript.

> 6. Flask is used for developing web applications using python, implemented on Werkzeug and Jinja2. Advantages of using Flask framework are: There is a built-in development server and a fast debugger provided. Lightweight.

# Let's get into project
## First Stage Creation of EKS Cluster

### THE pre-requirements for creation of cluster
```
1. AWS Account
2. Install AWS CLI
3. Install kubectl
4.install eksctl
```

### Installing of eksctl
> 1. Go to aws documentaion or [click here](https://eksctl.io/installation/)
> 2. After downloading the file, extract the file and copy the path of file
> 3. open system envirement variable, paste the path in local variable path and save it
> 4. open a command promt and pass the command $ **eksctl version**
> 5. create a file [cluster.yaml](https://github.com/Sudhirreddy07/Devops_project/blob/main/kubernetes/cluster.yaml)
> 6. Run the command to create a cluster in aws eks $ eksctl create cluster -f cluster.yaml
> 7. deletion of cluster $ eksctl delete cluster --name=<name> [--region=<region>]

##Installion of Minikube localy
>   1. Download the minikube exc file [Download Here](https://storage.googleapis.com/minikube/releases/latest/minikube-installer.exe)
>   2. Run the exc file, After installation start docker
>   3. Start your cluster
>      ```
>      minikube start
>      ```
>  4. Interact with your cluster
>     You can also make your life easier by adding the following to your shell config:
>      ```
>      doskey kubectl=minikube kubectl --
>      ```
>      If you already have kubectl installed, you can now use it to access your shiny new cluster:
>     ```
>     kubectl get po -A
>     ```

## Deployment of Mangodb in Kubernetes
> 1.
> 2.  Creation of Mangobd in kubernetes cluster, follow the steps
> 3. 











