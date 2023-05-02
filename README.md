

##Python:  

python -m venv: Creates a virtual environment for a Python project  
python -m pip install: Installs a Python package using pip
python -c: Runs a command in the Python interpreter  
python -m http.server: Starts a simple HTTP server to serve files in the current directory
python -m json.tool: Formats JSON data for readability  
python -m json.tool: Formats JSON data for readability
python -m http.server: Starts a simple HTTP server to serve files in the current directory    
python -m timeit: Measures the execution time of a Python statement or expression  
python -m unittest discover: Discovers and runs unit tests in a project  
python -m pip freeze: Lists all installed packages and their versions

##GitHub:  

git clone: Downloads a copy of a repository from GitHub  
git add: Adds changes to a local repository  
git commit: Commits changes to a local repository 
git push: Pushes changes to a remote repository on GitHub  
git pull: Pulls changes from a remote repository on GitHub  
git branch: Lists all branches in a repository 
git checkout: Switches to a different branch in a repository
git merge: Merges changes from one branch into another
git log: Displays the commit history for a repository  
git log --graph: Displays the commit history graph for a repository
git reset: Undoes changes to a repository
git cherry-pick: Applies a commit from one branch to another
git rebase: Reapplies commits from one branch onto another
git submodule: Manages Git submodules, which are repositories within a repository
git bisect: Helps find the commit that introduced a bug in a repository

##Google Cloud Platform (GCP):  

gcloud init: Initializes the gcloud command-line tool 
gcloud auth login: Logs in to your GCP account
gcloud compute instances create: Creates a new virtual machine instance on GCP 
gcloud compute ssh: Connects to a virtual machine instance on GCP via SSH
gcloud app deploy: Deploys an application to Google App Engine
gcloud app deploy cron.yaml: Deploys a cron job to Google App Engine  
gcloud compute ssh-keys import: Imports SSH keys for connecting to virtual machine instances on GCP
gcloud compute images list: Lists available images for virtual machine instances
gcloud compute disks create: Creates a new disk for a virtual machine instance
gcloud compute firewall-rules create: Creates a new firewall rule for a virtual machine instance  
gcloud container clusters create: Creates a new Kubernetes cluster 
gcloud sql instances create: Creates a new Cloud SQL instance
gcloud compute instances delete: Deletes a virtual machine instance on GCP
gcloud container clusters delete: Deletes a Kubernetes cluster on GCP
gcloud sql instances delete: Deletes a Cloud SQL instance

##Terraform:

terraform init: Initializes a new Terraform working directory
terraform plan: Generates an execution plan for Terraform
terraform apply: Applies the changes to infrastructure described in the Terraform configuration  
terraform destroy: Destroys the infrastructure created by Terraform
terraform validate: Validates the syntax and semantics of a Terraform configuration 
terraform refresh: Updates the state file to match the real-world resources
terraform state list: Lists the resources that Terraform is managing
terraform output: Displays the values of output variables defined in a Terraform configuration
terraform fmt: Formats a Terraform configuration for readability
terraform taint: Marks a resource instance as tainted, forcing it to be destroyed and recreated on the next Terraform apply
terraform plan -out: Generates an execution plan for Terraform and saves it to a file
terraform state replace-provider: Replaces a provider in a Terraform state file
terraform workspace: Manages multiple workspaces for a Terraform configuration
terraform import: Imports an existing resource into a Terraform state file

##Kubernetes:  

kubectl get: Lists resources in a Kubernetes cluster  
kubectl create: Creates a resource in a Kubernetes cluster   
kubectl apply: Applies changes to a resource in a Kubernetes cluster  
kubectl delete: Deletes a resource in a Kubernetes cluster
kubectl logs: Displays logs for a pod in a Kubernetes cluster
kubectl describe: Displays detailed information about a resource in a Kubernetes cluster
kubectl exec: Runs a command in a container in a pod in a Kubernetes cluster
kubectl port-forward: Forwards a port from a local machine to a pod in a Kubernetes cluster
kubectl scale: Increases or decreases the number of replicas for a resource in a Kubernetes cluster
kubectl apply --dry-run: Checks if a resource can be created or updated in a Kubernetes cluster without actually making changes
kubectl rollout history: Displays the revision history for a deployment in a Kubernetes cluster 
kubectl rollout undo: Reverts a deployment in a Kubernetes cluster to a previous revision
kubectl exec -it: Runs a command in a container in a pod in a Kubernetes cluster and opens an interactive terminal session
kubectl apply --prune: Deletes resources that are not defined in a Kubernetes configuration
kubectl logs --previous: Displays logs for the previous container instance of a pod in a Kubernetes cluster

##Linux:  

ls: Lists files and directories in the current directory
cd: Changes the current directory 
pwd: Prints the current working directory
mkdir: Creates a new directory  
rm: Removes a file or directory  
cp: Copies a file or directory  
mv: Moves or renames a file or directory  
chmod: Changes the permissions of a file or directory  
grep: Searches for a pattern in a file or directory 
ps: Lists running processes on a Linux system
curl: Sends an HTTP request and displays the response
wget: Downloads a file from the internet
sed: Searches for and replaces text in a file 
awk: Searches for and processes text in a file
tail: Displays the last few lines of a file

##Node.js:  

npm init: Initializes a new Node.js project  
npm install: Installs dependencies for a Node.js project  
npm start: Starts a Node.js project  
npm test: Runs tests for a Node.js project
npm run build: Builds a production-ready version of a Node.js project  
npm outdated: Lists outdated dependencies for a Node.js project  
npm update: Updates dependencies for a Node.js project  
npm run: Runs a script defined in the package.json file for a Node.js project
npm install --save-dev: Installs a development dependency for a Node.js project  
npm publish: Publishes a Node.js package to the npm registry  
npm dedupe: Removes redundant dependencies for a Node.js project 
npm outdated --depth=0: Lists outdated dependencies for a Node.js project without listing outdated dependencies of dependencies
npm rebuild: Rebuilds native modules for a Node.js project
npm search: Searches the npm registry for packages
npm link --global: Creates a symbolic link between a Node.js project and a global package
