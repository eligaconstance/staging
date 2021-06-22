{:external: target="_blank" .external}
{:codeblock: .codeblock}

## Getting started with Operations Console

Operations Console is ideal for any customers who want to store their data, run their ledger transaction workloads on their own infrastructure. Clients can build, operate, and grow their operation networks with an offering that can be used from development through production.

Your entitlement includes the console for managing your operation network. Use the console or Operations Console APIs to build a consortium of organizations to easily transact on the same network, regardless of each client's cloud preference. 

Experienced Hyperledger Fabric customers who prefer to deploy and manage their containers can download and use the peer, CA, orderer, and smart contract container images without the management console.

The ** Operations Console** is an open source stand-alone entitlement. You are responsible for provisioning your own Kubernetes cluster for image deployment. Additionally, you will need to [open ports in your firewall](/docs/security) if you are using one.

### Operations Console images

- Your Operations Console images are based on the open source Hyperledger Fabric code base and contain a number of enhancements for stability and serviceability. The Operations Console images do not include the management console or operator. This offering is intended for experienced Fabric users with existing Fabric deployments. 

## Installation

### Step one: Install the Operations Console
{: #get-started-console-foc-step-two-deploy-console}

The Operations Console uses a [Kubernetes Operator](https://kubernetes.io/docs/concepts/extend-kubernetes/operator/){: external} to install the Operations Console console on your cluster and manage the deployment and your blockchain nodes. A cluster administrator can use your entitlement key to deploy the platform on any Kubernetes Cluster.

- If you are deploying the perations Console on open source Kubernetes, use the steps described in the [Deploying Operations Console on Kubernetes](/docs/console-deploy-k8).

- If you are an experienced Hyperledger Fabric customer and prefer to only use the Operations Console images, see [Using the Operations Console images](/docs/console-images). Consult the Fabric documentation for further deployment, configuration, and management instructions. The rest of the steps in this topic do not apply when using the images.

### Step two: Grant console access to other users

After the platform is deployed, the console administrator can log in to the console with the email address and password that was provided during console deployment. The password that was provided becomes the default password of the console, and is used by all new users to log in to the console for the first time. The administrator can then add new users to the console, allowing others to log in and start working with Operations Console nodes. 

### Step three: Connect networks across clouds

You can use your console to operate components that are running on other clusters. First, you need to export the component information to a JSON file from the console where the component was originally deployed. Then, you can import the node JSON file into the console that is deployed on your local cluster and manage the components across clouds. For more information, see [Importing nodes](/docs/console-import-nodes#ibp-console-import-nodes).
