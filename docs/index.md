---
keywords: Operations Console, install operations console, Hyperledger Fabric Docker, Fabric test, Fabric samples
---
# Getting started with Operations Console

Operations Console is ideal for any customers who want to store their data, run their ledger transaction workloads on their own infrastructure. Clients can build, operate, and grow their operation networks with an offering that can be used from development through production.

## Before you begin

Before installing the Operations Console, you need to download and install the Fabric samples for set up and run the Fabric test in your local environment. Make sure you have installed all of the <a href="https://hyperledger-fabric.readthedocs.io/en/latest/prereqs.html" target=_blank">Fabric prerequisites</a> before <a href="https://hyperledger-fabric.readthedocs.io/en/latest/install.html" target="_blank">installing the Fabric Samples, Binaries and Docker Images</a>.

Once you have completed downloading the samples and Hyperledger Fabric Docker images, use the scripts provided in the <a href="https://github.com/hyperledger/fabric-samples" target="_blank">`fabric-samples` repository</a> and  the `./network.sh` to deploy and set up a test network. The test network contains two peer organizations with one peer each and a single node raft ordering service. 


## Installation

### Step one: Install the Operations Console

### Step two: 

### Step three: Connect networks across clouds

You can use your console to operate components that are running on other clusters. First, you need to export the component information to a JSON file from the console where the component was originally deployed. Then, you can import the node JSON file into the console that is deployed on your local environment and manage the components. For more information, see [importing nodes](console-import-nodes).
Also, see [build console network](console-build-network) and [join console network](console-join-network)
