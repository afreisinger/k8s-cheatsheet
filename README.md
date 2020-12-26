

Kubernetes


[Jenkins](https://www.jenkins.io)


-


[What is CDF?](https://cd.foundation/)
[Jenkins X](https://jenkins-x.io/)
[Tekton](https://cloud.google.com/tekton/)
[Spinnaker](https://www.spinnaker.io/)


-
[Blog](https://www.jenkins.io/node)


-


Documentation


[**
User Guide
**](https://www.jenkins.io/doc/book)
[ - Installing Jenkins](https://www.jenkins.io/doc/book/installing/)
[ - Jenkins Pipeline](https://www.jenkins.io/doc/book/pipeline)
[ - Managing Jenkins](https://www.jenkins.io/doc/book/managing/)
[ - System Administration](https://www.jenkins.io/doc/book/system-administration)
[ - Terms and Definitions](https://www.jenkins.io/doc/book/glossary/)
[**
Solution Pages
**](https://www.jenkins.io/solutions)
[**
Tutorials
**](https://www.jenkins.io/doc/tutorials/)
[ - Guided Tour](https://www.jenkins.io/doc/pipeline/tour/getting-started/)
[ - More Tutorials](https://www.jenkins.io/doc/tutorials/)
[**
Developer Guide
**](https://www.jenkins.io/doc/developer)
[**
Contributor Guide
**](https://www.jenkins.io/participate)


-
[Plugins](https://plugins.jenkins.io/)


-


Community


[Overview](https://www.jenkins.io/participate)
[Chat](https://www.jenkins.io/chat)
[Meet](https://www.jenkins.io/projects/jam)
[Events](https://www.jenkins.io/events)
[Issue Tracker](https://issues.jenkins.io/)
[Mailing Lists](https://www.jenkins.io/mailing-lists)
[Wiki](https://wiki.jenkins.io/)
[Account Management](https://accounts.jenkins.io/)
[**
Special Interest Groups
**](https://www.jenkins.io/sigs/)
[ - Advocacy and Outreach](https://www.jenkins.io/sigs/advocacy-and-outreach/)
[ - Chinese Localization](https://www.jenkins.io/sigs/chinese-localization/)
[ - Cloud Native](https://www.jenkins.io/sigs/cloud-native/)
[ - Documentation](https://www.jenkins.io/sigs/docs/)
[ - Google Summer of Code](https://www.jenkins.io/sigs/gsoc/)
[ - Hardware and EDA](https://www.jenkins.io/sigs/hw-and-eda/)
[ - Pipeline Authoring](https://www.jenkins.io/sigs/pipeline-authoring/)
[ - Platform](https://www.jenkins.io/sigs/platform/)
[ - User Experience](https://www.jenkins.io/sigs/ux/)


-


Subprojects


[Overview](https://www.jenkins.io/projects/)
[Evergreen](https://www.jenkins.io/projects/evergreen/)
[Google Summer of Code in Jenkins](https://www.jenkins.io/projects/gsoc/)
[Infrastructure](https://www.jenkins.io/projects/infrastructure/)
[CI/CD and Jenkins Area Meetups](https://www.jenkins.io/projects/jam/)
[Jenkins Configuration as Code](https://www.jenkins.io/projects/jcasc/)
[Jenkins Remoting](https://www.jenkins.io/projects/remoting/)
[Document Jenkins on Kubernetes](https://www.jenkins.io/sigs/docs/gsod/2020/projects/document-jenkins-on-kubernetes/)


-


About


[Security](https://www.jenkins.io/security)
[Press](https://www.jenkins.io/press)
[Awards](https://www.jenkins.io/awards)
[Conduct](https://www.jenkins.io/project/conduct)
[Artwork](https://www.jenkins.io/artwork)


-


English


[中文 Chinese](https://www.jenkins.io/zh)


-
[Download](https://www.jenkins.io/download)


[User Documentation Home](https://www.jenkins.io/doc)


#####
User Handbook


-
[User Handbook overview](https://www.jenkins.io/doc/book/getting-started)


-
[Installing Jenkins](https://www.jenkins.io/doc/book/installing)


-
[Docker](https://www.jenkins.io/doc/book/installing/docker)


-
[Kubernetes](https://www.jenkins.io/doc/book/installing/kubernetes)


-
[Linux](https://www.jenkins.io/doc/book/installing/linux)


-
[macOS](https://www.jenkins.io/doc/book/installing/macos)


-
[WAR files](https://www.jenkins.io/doc/book/installing/war-file)


-
[Windows](https://www.jenkins.io/doc/book/installing/windows)


-
[Other Systems](https://www.jenkins.io/doc/book/installing/other)


-
[Offline Installations](https://www.jenkins.io/doc/book/installing/offline)


-
[Initial Settings](https://www.jenkins.io/doc/book/installing/initial-settings)


-
[Using Jenkins](https://www.jenkins.io/doc/book/using)


-
[Pipeline](https://www.jenkins.io/doc/book/pipeline)


-
[Blue Ocean](https://www.jenkins.io/doc/book/blueocean)


-
[Managing Jenkins](https://www.jenkins.io/doc/book/managing)


-
[System Administration](https://www.jenkins.io/doc/book/system-administration)


-
[Scaling Jenkins](https://www.jenkins.io/doc/book/scaling)


-
[Appendix](https://www.jenkins.io/doc/book/appendix)


-
[Glossary](https://www.jenkins.io/doc/book/glossary)


#####
Tutorials


-
[Guided Tour](https://www.jenkins.io/doc/pipeline/tour/getting-started)


-
[Jenkins Pipeline](https://www.jenkins.io/doc/tutorials#pipeline)


-
[Using Build Tools](https://www.jenkins.io/doc/tutorials#tools)


#####
Resources


-
[Pipeline Syntax reference](https://www.jenkins.io/doc/book/pipeline/syntax)


-
[Pipeline Steps reference](https://www.jenkins.io/doc/pipeline/steps)


-
[LTS Upgrade guides](https://www.jenkins.io/doc/upgrade-guide)


[⇐ Docker](https://www.jenkins.io/doc/book/installing/docker)


[⇑ Installing Jenkins](https://www.jenkins.io/doc/book/installing/)


[Index](https://www.jenkins.io/doc/book/)


[Linux ⇒](https://www.jenkins.io/doc/book/installing/linux)


#
Kubernetes


Table of Contents

-  [Prerequisites](https://www.jenkins.io/doc/book/installing/kubernetes/#prerequisites)

-  [Create a minikube cluster](https://www.jenkins.io/doc/book/installing/kubernetes/#create-a-minikube-cluster)

-  [Create a namespace](https://www.jenkins.io/doc/book/installing/kubernetes/#create-a-namespace)


-  [Install Jenkins with Helm v3](https://www.jenkins.io/doc/book/installing/kubernetes/#install-jenkins-with-helm-v3)

-  [Prerequisites](https://www.jenkins.io/doc/book/installing/kubernetes/#prerequisites-2)

-  [Install Helm](https://www.jenkins.io/doc/book/installing/kubernetes/#install-helm)

-  [Configure Helm](https://www.jenkins.io/doc/book/installing/kubernetes/#configure-helm)

-  [Create a persistent volume](https://www.jenkins.io/doc/book/installing/kubernetes/#create-a-persistent-volume)

-  [Create a service account](https://www.jenkins.io/doc/book/installing/kubernetes/#create-a-service-account)

-  [Install Jenkins](https://www.jenkins.io/doc/book/installing/kubernetes/#install-jenkins)


-  [Install Jenkins with YAML files](https://www.jenkins.io/doc/book/installing/kubernetes/#install-jenkins-with-yaml-files)

-  [Create Jenkins deployment file](https://www.jenkins.io/doc/book/installing/kubernetes/#create-jenkins-deployment-file)

-  [Deploy Jenkins](https://www.jenkins.io/doc/book/installing/kubernetes/#deploy-jenkins)

-  [Grant access to Jenkins service](https://www.jenkins.io/doc/book/installing/kubernetes/#grant-access-to-jenkins-service)

-  [Access Jenkins dashboard](https://www.jenkins.io/doc/book/installing/kubernetes/#access-jenkins-dashboard)


-  [Install Jenkins with Jenkins Operator](https://www.jenkins.io/doc/book/installing/kubernetes/#install-jenkins-with-jenkins-operator)

-  [Prerequisites](https://www.jenkins.io/doc/book/installing/kubernetes/#prerequisites-3)

-  [Install Jenkins Operator](https://www.jenkins.io/doc/book/installing/kubernetes/#install-jenkins-operator)

-  [Configure Custom Resource Definition](https://www.jenkins.io/doc/book/installing/kubernetes/#configure-custom-resource-definition)

-  [Deploy Jenkins Operator](https://www.jenkins.io/doc/book/installing/kubernetes/#deploy-jenkins-operator)

-  [Deploy Jenkins](https://www.jenkins.io/doc/book/installing/kubernetes/#deploy-jenkins-2)

-  [Deploy Jenkins to Kubernetes:](https://www.jenkins.io/doc/book/installing/kubernetes/#deploy-jenkins-to-kubernetes)


-  [Post-installation setup wizard](https://www.jenkins.io/doc/book/installing/kubernetes/#setup-wizard)

-  [Unlocking Jenkins](https://www.jenkins.io/doc/book/installing/kubernetes/#unlocking-jenkins)

-  [Customizing Jenkins with plugins](https://www.jenkins.io/doc/book/installing/kubernetes/#customizing-jenkins-with-plugins)

-  [Creating the first administrator user](https://www.jenkins.io/doc/book/installing/kubernetes/#creating-the-first-administrator-user)


Kubernetes (K8s) is an open-source system for automating deployment, scaling,
and management of containerized applications.


A Kubernetes cluster adds a new automation layer to Jenkins.
Kubernetes makes sure that resources are used effectively and that your servers
and underlying infrastructure are not overloaded.
Kubernetes' ability to orchestrate container deployment ensures that Jenkins always
has the right amount of resources available.
This section will describe different options to install/run Jenkins on Kubernetes.


Note: the documented approach with Minikube is a Quickstart guide only suited for development and testing purposes.
It should not be used for production instances.
Configure production instances based on the  [Kubernetes guidelines](https://kubernetes.io/docs/setup/production-environment/)  .


##  [](https://www.jenkins.io/doc/book/installing/kubernetes/#prerequisites)  Prerequisites


Docker


Refer to the  [Docker Engine installation instructions](https://docs.docker.com/engine/install/)   for your platform.

Kubernetes


If you don’t have a running Kubernetes cluster, see the  [Create a minikube cluster](https://www.jenkins.io/doc/book/installing/kubernetes/#create-a-minikube-cluster)   section.


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#create-a-minikube-cluster)  Create a minikube cluster


Minikube is a tool that creates a single-node Kubernetes cluster on your computer.
Follow these steps if you don’t have a running Kubernetes cluster:


1.


Install minikube by following the steps from the  [Install minikube](https://kubernetes.io/docs/tasks/tools/install-minikube/)   site.


2.


Install kubectl. See the instructions from the  [Install and Set Up kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)   page.


3.


You can now create a minikube cluster by entering the following command:


$ minikube start


4.


Once the cluster has been created, you can verify its status by entering:


$ minikube status


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#create-a-namespace)  Create a namespace


A distinct namespace provides an additional layer of isolation and more control
over the continuous integration environment. Create a namespace for the Jenkins
deployment by typing the following command on your terminal:


$ kubectl create namespace jenkins


Use the following command to list existing namespaces:


$ kubectl get namespaces


The output confirms that the jenkins namespace was created successfully.


$ kubectl get namespaces
NAME              STATUS   AGE
default           Active   50m
jenkins           Active   30s
kube-node-lease   Active   50m
kube-public       Active   50m
kube-system       Active   50m


##  [](https://www.jenkins.io/doc/book/installing/kubernetes/#install-jenkins-with-helm-v3)  Install Jenkins with Helm v3


A typical Jenkins deployment consists of a controller node and, optionally, one or more agents. To simplify the deployment of Jenkins, we’ll use  [Helm](https://helm.sh/)   to deploy Jenkins.
Helm is a package manager for Kubernetes and its package format is called a chart.
Many community-developed charts are available on  [GitHub](https://github.com/helm/charts)  .


Helm Charts provide “push button” deployment and deletion of apps, making adoption and development of Kubernetes apps easier for those with little container or microservices experience.


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#prerequisites-2)  Prerequisites


Helm command line interface


If you don’t have Helm command line interface installed and configured locally, see the sections below to  [Install Helm](https://www.jenkins.io/doc/book/installing/kubernetes/#install-helm)   and  [Configure Helm](https://www.jenkins.io/doc/book/installing/kubernetes/#configure-helm)  .


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#install-helm)  Install Helm


To install Helm CLI, follow the instructions from the  [Installing Helm](https://helm.sh/docs/intro/install/)   page.


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#configure-helm)  Configure Helm


Once Helm is installed and set up properly, add the Jenkins repo as follows:


$ helm repo add jenkinsci https://charts.jenkins.io
$ helm repo update


The helm charts in the Jenkins repo can be listed with the command:


$ helm search repo jenkinsci


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#create-a-persistent-volume)  Create a persistent volume


We want to create a  [persistent volume](https://kubernetes.io/docs/concepts/storage/persistent-volumes/)   for our Jenkins controller pod.
This will prevent us from losing our whole configuration of the Jenkins controller and our jobs when we reboot our minikube.
This  [official minikube doc](https://github.com/kubernetes/minikube/blob/master/docs/persistent_volumes.md)   explains which directories we can use to mount or data.
In a multi-node Kubernetes cluster, you’ll need some solution like NFS to make the mount directory available in the whole cluster.
But because we use minikube which is a one-node cluster we don’t have to bother about it.


We choose to use the  /data  directory. This directory will contain our Jenkins controller configuration.


** We will create a volume which is called jenkins-pv: **


1.


Paste the content from  [https://raw.githubusercontent.com/installing-jenkins-on-kubernetes/jenkins-volume.yaml](https://raw.githubusercontent.com/jenkins-infra/jenkins.io/master/content/doc/tutorials/kubernetes/installing-jenkins-on-kubernetes/jenkins-volume.yaml)   into a YAML formatted file called  jenkins-volume.yaml .


2.


Run the following command to apply the spec:


$ kubectl apply -f jenkins-volume.yaml


It’s worth noting that, in the above spec, hostPath uses the /data/jenkins-volume/ of your node to emulate network-attached storage.
This approach is only suited for development and testing purposes.
For production, you should provide a network resource like a Google Compute Engine persistent disk, or an Amazon Elastic Block Store volume.


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#create-a-service-account)  Create a service account


In Kubernetes, service accounts are used to provide an identity for pods.
Pods that want to interact with the API server will authenticate with a
particular service account.
By default, applications will authenticate as the  default  service account in
the namespace they are running in.
This means, for example, that an application running in the  test  namespace
will use the default service account of the  test  namespace.


** We will create a service account called jenkins: **


A ClusterRole is a set of permissions that can be assigned to resources within a given cluster.
Kubernetes APIs are categorized into API groups, based on the API objects that they relate to.
While creating a ClusterRole, you can specify the operations that can be performed by the ClusterRole on one or more API objects in one or more API groups, just as we have done above.
ClusterRoles have several uses. You can use a ClusterRole to:


-


define permissions on namespaced resources and be granted within individual namespace(s)


-


define permissions on namespaced resources and be granted across all namespaces


-


define permissions on cluster-scoped resources


If you want to define a role cluster-wide, use a ClusterRole;
if you want to define a role within a namespace, use a Role.


A role binding grants the permissions defined in a role to a user or set of users.
It holds a list of subjects (users, groups, or service accounts), and a reference to the role being granted.


A RoleBinding may reference any Role in the same namespace.
Alternatively, a RoleBinding can reference a ClusterRole and bind that ClusterRole to the namespace of the RoleBinding.
To bind a ClusterRole to all the namespaces in our cluster, we use a ClusterRoleBinding.


1.


Paste the content from  [https://raw.githubusercontent.com/installing-jenkins-on-kubernetes/jenkins-sa.yaml](https://raw.githubusercontent.com/jenkins-infra/jenkins.io/master/content/doc/tutorials/kubernetes/installing-jenkins-on-kubernetes/jenkins-sa.yaml)   into a YAML formatted file called
jenkins-sa.yaml .


2.


Run the following command to apply the spec:


$ kubectl apply -f jenkins-sa.yaml


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#install-jenkins)  Install Jenkins


We will deploy Jenkins including the Jenkins Kubernetes plugin.
Here you can find the official chart.


1.


To enable persistence, we will create an override file and pass it as an argument to the
Helm CLI.
Paste the content from  [raw.githubusercontent.com/jenkinsci/helm-charts/main/charts/jenkins/values.yaml](https://raw.githubusercontent.com/jenkinsci/helm-charts/main/charts/jenkins/values.yaml)   into a YAML formatted file called  jenkins-values.yaml .


The  jenkins-values.yaml  is used as a template to provide values that are necessary for setup.


2.


Open the  jenkins-values.yaml  file in your favorite text editor and modify the following:


-


nodePort: Because we are using minikube we need to use NodePort as service type. Only cloud providers offer load balancers. We define port 32000 as port.


-


storageClass:


storageClass :   jenkins-pv


-


serviceAccount: the serviceAccount section of the jenkins-values.yaml file should look like this:


serviceAccount :
create :   false
# Service account name is autogenerated by default
name :   jenkins
annotations :   {}


Where `name: jenkins` refers to the serviceAccount created for jenkins.


-


We can also define which plugins we want to install on our Jenkins.
We use some default plugins like git and the pipeline plugin.


-


Now you can install Jenkins by running the  helm install  command and passing it the
following arguments:


-


The name of the release  jenkins


-


The -f flag with the YAML file with overrides  jenkins-values.yaml


-


The name of the chart  jenkinsci/jenkins


-


The  -n  flag with the name of your namespace  jenkins


$ chart=jenkinsci/jenkins
$ helm install jenkins -n jenkins -f jenkins-values.yaml $chart


This outputs something similar to the following:


NAME: jenkins
LAST DEPLOYED: Wed Sep 16 11:13:10 2020
NAMESPACE: jenkins
STATUS: deployed
REVISION: 1


1.


Get your 'admin' user password by running:


$ jsonpath="{.data.jenkins-admin-password}"
$ secret=$(kubectl get secret -n jenkins jenkins -o jsonpath=$jsonpath)
$ echo $(echo $secret | base64 --decode)


2.


Get the Jenkins URL to visit by running these commands in the same shell:


$ jsonpath="{.spec.ports[0].nodePort}"
$ NODE_PORT=$(kubectl get -n jenkins -o jsonpath=$jsonpath services jenkins)
$ jsonpath="{.items[0].status.addresses[0].address}"
$ NODE_IP=$(kubectl get nodes -n jenkins -o jsonpath=$jsonpath)
$ echo http://$NODE_IP:$NODE_PORT/login


3.


Login with the password from step 1 and the username: admin


4.


Use Jenkins Configuration as Code by specifying configScripts in your values.yaml file.
See the configuration as code  [documentation](http:///configuration-as-code)   and   [examples](https://github.com/jenkinsci/configuration-as-code-plugin/tree/master/demos)  .


Visit the  [Jenkins on Kubernetes solutions page](https://cloud.google.com/solutions/jenkins-on-container-engine)   for more information on running Jenkins on Kubernetes.
Visit the  [Jenkins Configuration as Code project](https://jenkins.io/projects/jcasc/)   for more information on configuration as code.
. Depending on your environment, it can take a bit of time for Jenkins to start up. Enter the
following command to inspect the status of your Pod:


$ kubectl get pods -n jenkins


Once Jenkins is installed, the status should be  set to Running as in the following output:


$ kubectl get pods -n jenkins
NAME                       READY   STATUS    RESTARTS   AGE
jenkins-645fbf58d6-6xfvj   1/1     Running   0          2m


1.


To access your Jenkins server, you must retrieve the password. You can retrieve your password
using either of the two options below.


** Option 1 **


Run the following command:


$ jsonpath="{.data.jenkins-admin-password}"
$ secret=$(kubectl get secret -n jenkins jenkins -o jsonpath=$jsonpath)
$ echo $(echo $secret | base64 --decode)


The output should look like this:


Um1kJLOWQY


👆🏻Note that your password will be different.


** Option 2 **


Run the following command:


$ jsonpath="{.data.jenkins-admin-password}"
$ kubectl get secret -n jenkins jenkins -o jsonpath=$jsonpath


The output should be a ** base64 encoded string ** like this:


WkIwRkdnbDZYZg==


Decode the base64 string and you have your password. You can use  [this website](https://www.base64decode.org/)   to decode your output.


2.


Get the name of the Pod running that is running Jenkins using the following command:


$ kubectl get pods -n jenkins


3.


Use the kubectl command to set up port forwarding:


$ kubectl -n jenkins port-forward <pod_name> 8080:8080
Forwarding from 127.0.0.1:8080 -> 8080
Forwarding from [::1]:8080 -> 8080


Visit  [127.0.0.1:8080/](http://127.0.0.1:8080/)   and log in using  admin  as the username and the password you retrieved earlier.


##  [](https://www.jenkins.io/doc/book/installing/kubernetes/#install-jenkins-with-yaml-files)  Install Jenkins with YAML files


This section describes how to use a set of YAML (Yet Another Markup Language) files to install Jenkins on a Kubernetes cluster.
The YAML files are easily tracked, edited, and can be reused indefinitely.


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#create-jenkins-deployment-file)  Create Jenkins deployment file


Copy the contents  [here](https://raw.githubusercontent.com/jenkins-infra/jenkins.io/master/content/doc/tutorials/kubernetes/installing-jenkins-on-kubernetes/jenkins-deployment.yaml)   into your preferred text editor and create a jenkins-deployment.yaml file in the “jenkins” namespace we created in this  [section](https://www.jenkins.io/doc/book/installing/kubernetes/#create-a-namespace)   above.


-


This  [deployment file](https://raw.githubusercontent.com/jenkins-infra/jenkins.io/master/content/doc/tutorials/kubernetes/installing-jenkins-on-kubernetes/jenkins-deployment.yaml)   is defining a Deployment as indicated by the  kind  field.


-


The Deployment specifies a single replica. This ensures one and only one instance
will be maintained by the Replication Controller in the event of failure.


-


The container image name is jenkins and version is 2.32.2


-


The list of ports specified within the spec are a list of ports to expose from
the container on the Pods IP address.


-


Jenkins running on (http) port 8080.


-


The Pod exposes the port 8080 of the jenkins container.


-


The volumeMounts section of the file creates a Persistent Volume.
This volume is mounted within the container at the path /var/jenkins_home and so
modifications to data within /var/jenkins_home are written to the volume.
This volume is mounted within the container at the path /var/jenkins_home and
so modifications to data within /var/jenkins_home are written to the volume.
The role of a persistent volume is to store basic Jenkins data and preserve it
beyond the lifetime of a pod.


Exit and save the changes once you add the content to the Jenkins deployment file.


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#deploy-jenkins)  Deploy Jenkins


To create the deployment execute:


$ kubectl create -f jenkins-deployment.yaml -n jenkins


The command also instructs the system to install Jenkins within the jenkins namespace.


To validate that creating the deployment was successful you can invoke:


$ kubectl get deployments -n jenkins


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#grant-access-to-jenkins-service)  Grant access to Jenkins service


We have a Jenkins instance deployed but it is still not accessible.
The Jenkins Pod has been assigned an IP address that is internal to the Kubernetes cluster.
It’s possible to log into the Kubernetes Node and access Jenkins from there but that’s not a very useful way to access the service.


To make Jenkins accessible outside the Kubernetes cluster the Pod needs to be exposed as a Service.
A Service is an abstraction that exposes Jenkins to the wider network.
It allows us to maintain a persistent connection to the pod regardless of the changes in the cluster.
With a local deployment, this means creating a NodePort service type.
A NodePort service type exposes a service on a port on each node in the cluster.
The service is accessed through the Node IP address and the service nodePort.
A simple service is defined  [here](https://raw.githubusercontent.com/jenkins-infra/jenkins.io/master/content/doc/tutorials/kubernetes/installing-jenkins-on-kubernetes/jenkins-service.yaml)  :


-


This  [service file](https://raw.githubusercontent.com/jenkins-infra/jenkins.io/master/content/doc/tutorials/kubernetes/installing-jenkins-on-kubernetes/jenkins-service.yaml)   is defining a Service as
indicated by the  kind  field.


-


The Service is of type NodePort. Other options are ClusterIP (only accessible within the cluster) and LoadBalancer (IP address assigned by a cloud provider e.g. AWS Elastic IP).


-


The list of ports specified within the spec is a list of ports exposed by this service.


-


The port is the port that will be exposed by the service.


-


The target port is the port to access the Pods targeted by this service. A port name may also be specified.


-


The selector specifies the selection criteria for the Pods targeted by this service.


To create the service execute:


$ kubectl create -f jenkins-service.yaml -n jenkins


To validate that creating the service was successful you can run:


$ kubectl get services -n jenkins
NAME       TYPE        CLUSTER-IP       EXTERNAL-IP    PORT(S)           AGE
jenkins    NodePort    10.103.31.217    <none>         8080:32664/TCP    59s


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#access-jenkins-dashboard)  Access Jenkins dashboard


So now we have created a deployment and service, how do we access Jenkins?


From the output above we can see that the service has been exposed on port 322664.
We also know that because the service is of type NodeType the service will route
requests made to any node on this port to the Jenkins pod.
All that’s left for us is to determine the IP address of the minikube VM.
Minikube have made this really simple by including a specific command that outputs
the IP address of the running cluster:


$ minikube ip
192.168.99.100


Now we can access the Jenkins instance at  [192.168.99.100:30104/](http://192.168.99.100:30104/)


To access Jenkins, you initially need to enter your credentials.
The default username for new installations is admin.
The password can be obtained in several ways.
This example uses the Jenkins deployment pod name.


To find the name of the pod, enter the following command:


$ kubectl get pods -n jenkins


Once you locate the name of the pod, use it to access the pod’s logs.


$ kubectl logs <pod_name> -n jenkins


The password is at the end of the log formatted as a long alphanumeric string:


*************************************************************
*************************************************************
*************************************************************

Jenkins initial setup is required.
An admin user has been created and a password generated.
Please use the following password to proceed to installation:

94b73ef6578c4b4692a157f768b2cfef

This may also be found at:
/var/jenkins_home/secrets/initialAdminPassword

*************************************************************
*************************************************************
*************************************************************


You have successfully installed Jenkins on your Kubernetes cluster and can use it to create new and efficient development pipelines.


##  [](https://www.jenkins.io/doc/book/installing/kubernetes/#install-jenkins-with-jenkins-operator)  Install Jenkins with Jenkins Operator


The  [Jenkins Operator](https://jenkinsci.github.io/kubernetes-operator/docs/)   is a Kubernetes native Operator which manages operations
for Jenkins on Kubernetes.
It was built with immutability and declarative configuration as code in mind.
The Jenkins Operator is easy to install with just a few manifest and allows
users to configure and manage Jenkins on Kubernetes.


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#prerequisites-3)  Prerequisites


Jenkins Operator


If you don’t have Jenkins Operator installed and configured locally,
see the sections below to  [Install Jenkins Operator](https://www.jenkins.io/doc/book/installing/kubernetes/#install-jenkins-operator)  .


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#install-jenkins-operator)  Install Jenkins Operator


Requirements


To run Jenkins Operator, you will need:


1.


Access to a Kubernetes cluster. If you don’t have a running Kubernetes cluster,
see the  [Create a Kubernetes cluster with minikube](https://www.jenkins.io/doc/book/installing/kubernetes/#create-a-kubernetes-cluster-with-minikube)   section above.


2.


kubectl version 1.11+


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#configure-custom-resource-definition)  Configure Custom Resource Definition


The Custom Resource Definition (CRD) API has been introduced to Kubernetes in v1.7
and it enables users to add custom APIs to their Kubernetes cluster which can be
used like any other native Kubernetes objects.
Defining a CRD object creates a new custom resource with a name and schema that you specify. The Kubernetes API serves and handles the storage of your custom resource.


Install Jenkins Custom Resource Definition


Kindly note that links to sample yaml files such as the one below are subject to change based on maintenance and will be best to verify from the official documentation  [here](https://jenkinsci.github.io/kubernetes-operator/docs/installation/)   before use.


$ CRD_FILE=kubernetes-operator/master/deploy/crds/jenkins_v1alpha2_jenkins_crd.yaml
$ kubectl apply -f https://raw.githubusercontent.com/jenkinsci/$CRD_FILE


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#deploy-jenkins-operator)  Deploy Jenkins Operator


There are two ways to deploy the Jenkins Operator.


Using YAML’s


Apply Service Account and RBAC roles:


$ DEPLOY_FILE=kubernetes-operator/master/deploy/all-in-one-v1alpha2.yaml
$ kubectl apply -f https://raw.githubusercontent.com/jenkinsci/$DEPLOY_FILE


Watch Jenkins Operator instance being created:


$ kubectl get pods


Now Jenkins Operator should be up and running in the default namespace.


Using Helm Chart


There is an option to use Helm to install the operator.
It requires the Helm 3+ for deployment.
If you don’t have Helm command line interface installed and configured locally,
see the sections above to  [Install Helm](https://www.jenkins.io/doc/book/installing/kubernetes/#install-helm)

Create a namespace for the operator


See the  [Create a namespace](https://www.jenkins.io/doc/book/installing/kubernetes/#create-a-namespace)   section above.

Configure Helm


Once Helm is installed and set up properly, add the Jenkins-Operator repo as follows:


$ CHART_FILE=kubernetes-operator/master/chart
$ helm repo add jenkins https://raw.githubusercontent.com/jenkinsci/$CHART_FILE


Install Jenkins Operator


$ helm install <name> jenkins/jenkins-operator -n jenkins


To add custom labels and annotations, you can use  values.yaml  file as explained in the  [Install Jenkins](https://www.jenkins.io/doc/book/installing/kubernetes/#install-jenkins)   section above or pass them into helm install command, e.g.:


$ LABEL="jenkins.labels.LabelKey=LabelValue"
$ ANNOTATION="jenkins.annotations.AnnotationKey=AnnotationValue"
$ NAME=my-jenkins-operator-install
$ helm install $NAME jenkins/jenkins-operator -n jenkins --set $LABEL,$ANNOTATION


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#deploy-jenkins-2)  Deploy Jenkins


Once Jenkins Operator is up and running let’s deploy the actual Jenkins instance.
Create a manifest e.g. jenkins_instance.yaml with the following data and save it locally.


apiVersion :   jenkins.io/v1alpha2
kind :   Jenkins
metadata :
name :   example
spec :
master :
containers :
-   name: jenkins-master
image :   jenkins/jenkins:lts
imagePullPolicy :   Always
livenessProbe :
failureThreshold :   12
httpGet :
path :   /login
port :   http
scheme :   HTTP
initialDelaySeconds :   80
periodSeconds :   10
successThreshold :   1
timeoutSeconds :   5
readinessProbe :
failureThreshold :   3
httpGet :
path :   /login
port :   http
scheme :   HTTP
initialDelaySeconds :   30
periodSeconds :   10
successThreshold :   1
timeoutSeconds :   1
resources :
limits :
cpu :   1500m
memory :   3Gi
requests :
cpu :   "  1  "
memory :   500Mi
seedJobs :
-   id: jenkins-operator
targets :   "  cicd/jobs/*.jenkins  "
description :   "  Jenkins Operator repository  "
repositoryBranch :   master
repositoryUrl :   https://github.com/jenkinsci/kubernetes-operator.git


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#deploy-jenkins-to-kubernetes)  Deploy Jenkins to Kubernetes:


$ kubectl create -f jenkins_instance.yaml -n jenkins


Watch the Jenkins instance being created:


$ kubectl get pods -n jenkins


Get Jenkins credentials


$ SECRET_NAME=jenkins-operator-credentials-<cr_name>
$ kubectl -n jenkins get secret $SECRET_NAME -o 'jsonpath={.data.user}' | base64 -d
$ kubectl -n jenkins get secret $SECRET_NAME -o 'jsonpath={.data.password}' | base64 -d


Connect to Jenkins (minikube)


$ minikube service jenkins-operator-http-<cr_name> --url -n jenkins


Connect to Jenkins (actual Kubernetes cluster)


$ kubectl port-forward jenkins-<cr_name> 8080:8080


Then open a browser with the address  [localhost:8080](http://localhost:8080)   to view your Jenkins Dashboard.


##  [](https://www.jenkins.io/doc/book/installing/kubernetes/#setup-wizard)  Post-installation setup wizard


After downloading, installing and running Jenkins using one of the procedures
above, the post-installation setup wizard begins.


This setup wizard takes you through a few quick "one-off" steps to unlock
Jenkins, customize it with plugins and create the first administrator user
through which you can continue accessing Jenkins.


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#unlocking-jenkins)  Unlocking Jenkins


When you first access a new Jenkins instance, you are asked to unlock it using
an automatically-generated password.


1.


Browse to  http://localhost:8080  (or whichever port you configured for
Jenkins when installing it) and wait until the ** Unlock Jenkins ** page appears.


![Unlock Jenkins page](https://www.jenkins.io/doc/book/resources/tutorials/setup-jenkins-01-unlock-jenkins-page.jpg)


2.


From the Jenkins console log output, copy the automatically-generated
alphanumeric password (between the 2 sets of asterisks).


![Copying initial admin password](https://www.jenkins.io/doc/book/resources/tutorials/setup-jenkins-02-copying-initial-admin-password.png)

** Note: **


-


The command:  sudo cat /var/lib/jenkins/secrets/initialAdminPassword  will print the password at console.


-


If you are running Jenkins in Docker using the official  jenkins/jenkins  image you can use  sudo docker exec ${CONTAINER_ID or CONTAINER_NAME} cat /var/jenkins_home/secrets/initialAdminPassword  to print the password in the console without having to exec into the container.


-


On the ** Unlock Jenkins ** page, paste this password into the ** Administrator
password ** field and click ** Continue **.

** Notes: **


-


You can always access the Jenkins console log from the Docker logs
( [above](https://www.jenkins.io/doc/book/installing/kubernetes/#accessing-the-jenkins-console-log-through-docker-logs)  ).


-


The Jenkins console log indicates the location (in the Jenkins home directory)
where this password can also be obtained. This password must be entered in the
setup wizard on new Jenkins installations before you can access Jenkins’s main
UI. This password also serves as the default admininstrator account’s password
(with username "admin") if you happen to skip the subsequent user-creation
step in the setup wizard.


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#customizing-jenkins-with-plugins)  Customizing Jenkins with plugins


After  [unlocking Jenkins](https://www.jenkins.io/doc/book/installing/kubernetes/#unlocking-jenkins)  , the ** Customize Jenkins ** page
appears. Here you can install any number of useful plugins as part of your
initial setup.


Click one of the two options shown:


-


** Install suggested plugins ** - to install the recommended set of plugins, which
are based on most common use cases.


-


** Select plugins to install ** - to choose which set of plugins to initially
install. When you first access the plugin selection page, the suggested
plugins are selected by default.


If you are not sure what plugins you need, choose ** Install suggested
plugins **.
You can install (or remove) additional Jenkins plugins at a later point in time
via the
[**Manage Jenkins**](https://www.jenkins.io/doc/book/managing)     >
[**Manage Plugins**](https://www.jenkins.io/doc/book/managing/plugins/)     page in Jenkins.


The setup wizard shows the progression of Jenkins being configured and your
chosen set of Jenkins plugins being installed. This process may take a few
minutes.


###  [](https://www.jenkins.io/doc/book/installing/kubernetes/#creating-the-first-administrator-user)  Creating the first administrator user


Finally, after  [customizing Jenkins with
plugins](https://www.jenkins.io/doc/book/installing/kubernetes/#customizing-jenkins-with-plugins)  , Jenkins asks you to create your first administrator user.


1.


When the ** Create First Admin User ** page appears, specify the details for your
administrator user in the respective fields and click ** Save and Finish **.


2.


When the ** Jenkins is ready ** page appears, click ** Start using Jenkins **.

** Notes: **


-


This page may indicate ** Jenkins is almost ready! ** instead and if so, click
** Restart **.


-


If the page does not automatically refresh after a minute, use your web
browser to refresh the page manually.


-


If required, log in to Jenkins with the credentials of the user you just
created and you are ready to start using Jenkins!


------------------------------


[⇐ Docker](https://www.jenkins.io/doc/book/installing/docker)


[⇑ Installing Jenkins](https://www.jenkins.io/doc/book/installing/)


[Index](https://www.jenkins.io/doc/book/)


[Linux ⇒](https://www.jenkins.io/doc/book/installing/linux)


------------------------------


[Was this page helpful?](https://www.jenkins.io/doc/book/installing/kubernetes/#feedback)


Please submit your feedback about this page through this
[quick form](https://www.jenkins.io/doc/feedback-form/)  .


Alternatively, if you don't wish to complete the quick form, you can simply
indicate if you found this page helpful?


Yes

No


See existing feedback  [here](https://docs.google.com/spreadsheets/d/1IIdpVs39JDYKg0sLQIv-MNO928qcGApAIfdW5ohfD78)  .


[Improve this page](https://github.com/jenkins-infra/jenkins.io/edit/master/content//doc/book/installing/kubernetes.adoc)
|
[Report a problem](https://github.com/jenkins-infra/jenkins.io/issues/new?labels=bug&template=4-bug.md&title=Kubernetes%20page%20-%20TODO:%20Put%20a%20summary%20here&body=Problem%20with%20the%20%5BKubernetes%5D(https://www.jenkins.io/doc/book/installing/kubernetes/)%20page,%20%5Bsource%20file%5D(https://github.com/jenkins-infra/jenkins.io/blob/master/content/doc/book/installing/kubernetes.adoc)%250A%250ATODO:%20Describe%20the%20expected%20and%20actual%20behavior%20here%20%250A%250A%2523%2523%20Screenshots%20%250A%250A%20TODO:%20Add%20screenshots%20if%20possible%20%250A%250A%2523%2523%20Possible%20Solution%20%250A%250A%253C!--%20If%20you%20have%20suggestions%20on%20a%20fix%20for%20the%20bug,%20please%20describe%20it%20here.%20--%253E%20%250A%250AN/A)


[Creative Commons Attribution-ShareAlike license](https://creativecommons.org/licenses/by-sa/4.0/)  [](https://licensebuttons.net/l/by-sa/4.0/88x31.png)


The content driving this site is licensed under the Creative
Commons Attribution-ShareAlike 4.0 license.


##### Resources


-
[Downloads](https://www.jenkins.io/download)


-
[Blog](https://www.jenkins.io/node)


-
[Documentation](https://www.jenkins.io/doc)


-
[Plugins](https://plugins.jenkins.io/)


-
[Security](https://www.jenkins.io/security)


-
[Contributing](https://www.jenkins.io/participate)


##### Project


-
[Structure and governance](https://www.jenkins.io/project)


-
[Issue tracker](https://issues.jenkins.io)


-
[Wiki](https://wiki.jenkins.io)


-
[GitHub](https://github.com/jenkinsci)


-
[Jenkins on Jenkins](https://ci.jenkins.io)


##### Community


-
[Events](https://www.jenkins.io/events)


-
[Mailing lists](https://www.jenkins.io/mailing-lists)


-
[Chats](https://www.jenkins.io/chat)


-
[Special Interest Groups](https://www.jenkins.io/sigs)


-
[Twitter](https://twitter.com/jenkinsci)


-
[Reddit](https://reddit.com/r/jenkinsci)


##### Other


-
[Code of Conduct](https://www.jenkins.io/conduct)


-
[Press information](https://www.jenkins.io/press)


-
[Merchandise](https://www.jenkins.io/merchandise)


-
[Artwork](https://www.jenkins.io/artwork)


-
[Awards](https://www.jenkins.io/awards)
