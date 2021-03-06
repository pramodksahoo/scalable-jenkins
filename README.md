# scalable-jenkins
Setup Scalable Jenkins on Top of a Kubernetes Cluster


``Jenkins Scalability``
Scalability is a measure that shows the ability of a system to expand its capabilities to handle an additional load. One of the strongest sides of Jenkins is that it has a scaling feature almost out-of-the-box. Jenkins scaling is based on the master/slaves model, where you have a number of agent instances (called slaves) and one main Jenkins instance (called master), which is responsible mainly for distributing jobs across slaves. Sounds simple right?

- The ability to run many more build plans in parallel
- Automatically replacing corrupted Jenkins instances
- Automatically spinning up and removing slaves based on need, which saves costs
- Distributing the load across different physical machines while keeping required resources available  for each specific build plan

``Kubernetes Sandbox Installation``

➜ ``curl -Lo minikube https://storage.googleapis.com/minikube/releases/latest/minikube-darwin-amd64 && chmod +x minikube && sudo mv minikube /usr/local/bin/``

To run the Minikube after its installation:
➜ minikube start

