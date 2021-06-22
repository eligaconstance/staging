---

copyright:
  years: 2021
lastupdated: "2021-06-16"

keywords: Fabric Operations Console


---

{:DomainName: data-hd-keyref="APPDomain"}
{:DomainName: data-hd-keyref="DomainName"}
{:android: data-hd-operatingsystem="android"}
{:api: .ph data-hd-interface='api'}
{:apikey: data-credential-placeholder='apikey'}
{:app_key: data-hd-keyref="app_key"}
{:app_name: data-hd-keyref="app_name"}
{:app_secret: data-hd-keyref="app_secret"}
{:app_url: data-hd-keyref="app_url"}
{:authenticated-content: .authenticated-content}
{:beta: .beta}
{:c#: data-hd-programlang="c#"}
{:cli: .ph data-hd-interface='cli'}
{:codeblock: .codeblock}
{:curl: .ph data-hd-programlang='curl'}
{:deprecated: .deprecated}
{:dotnet-standard: .ph data-hd-programlang='dotnet-standard'}
{:download: .download}
{:external: target="_blank" .external}
{:faq: data-hd-content-type='faq'}
{:fuzzybunny: .ph data-hd-programlang='fuzzybunny'}
{:generic: data-hd-operatingsystem="generic"}
{:generic: data-hd-programlang="generic"}
{:gif: data-image-type='gif'}
{:go: .ph data-hd-programlang='go'}
{:help: data-hd-content-type='help'}
{:hide-dashboard: .hide-dashboard}
{:hide-in-docs: .hide-in-docs}
{:important: .important}
{:ios: data-hd-operatingsystem="ios"}
{:java: .ph data-hd-programlang='java'}
{:java: data-hd-programlang="java"}
{:javascript: .ph data-hd-programlang='javascript'}
{:javascript: data-hd-programlang="javascript"}
{:new_window: target="_blank"}
{:note .note}
{:note: .note}
{:objectc data-hd-programlang="objectc"}
{:org_name: data-hd-keyref="org_name"}
{:php: data-hd-programlang="php"}
{:pre: .pre}
{:preview: .preview}
{:python: .ph data-hd-programlang='python'}
{:python: data-hd-programlang="python"}
{:route: data-hd-keyref="route"}
{:row-headers: .row-headers}
{:ruby: .ph data-hd-programlang='ruby'}
{:ruby: data-hd-programlang="ruby"}
{:runtime: architecture="runtime"}
{:runtimeIcon: .runtimeIcon}
{:runtimeIconList: .runtimeIconList}
{:runtimeLink: .runtimeLink}
{:runtimeTitle: .runtimeTitle}
{:screen: .screen}
{:script: data-hd-video='script'}
{:service: architecture="service"}
{:service_instance_name: data-hd-keyref="service_instance_name"}
{:service_name: data-hd-keyref="service_name"}
{:shortdesc: .shortdesc}
{:space_name: data-hd-keyref="space_name"}
{:step: data-tutorial-type='step'}
{:subsection: outputclass="subsection"}
{:support: data-reuse='support'}
{:swift: .ph data-hd-programlang='swift'}
{:swift: data-hd-programlang="swift"}
{:table: .aria-labeledby="caption"}
{:term: .term}
{:tip: .tip}
{:tooling-url: data-tooling-url-placeholder='tooling-url'}
{:troubleshoot: data-hd-content-type='troubleshoot'}
{:tsCauses: .tsCauses}
{:tsResolve: .tsResolve}
{:tsSymptoms: .tsSymptoms}
{:tutorial: data-hd-content-type='tutorial'}
{:ui: .ph data-hd-interface='ui'}
{:unity: .ph data-hd-programlang='unity'}
{:url: data-credential-placeholder='url'}
{:user_ID: data-hd-keyref="user_ID"}
{:vbnet: .ph data-hd-programlang='vb.net'}
{:video: .video}



# Getting started with Fabric Operations Console
{: #get-started-console-foc}


Fabric Operations Console is ideal for the customers who want to store their data, or run their workloads on their own infrastructure or across public and private clouds for security, risk mitigation, preference, or compliance reasons. Clients can build, operate, and grow their operation networks with an offering that can be used from development through production.
{:shortdesc}

Your entitlement includes the flexible management console for managing your operation network. Use the console or Fabric Operations Console APIs to build a consortium of organizations to easily transact on the same network, regardless of each client's cloud preference. 

Experienced Hyperledger Fabric customers who prefer to deploy and manage their containers can download and use the peer, CA, orderer, and smart contract container images without the management console.

The **Fabric Operations Console** is an open source stand-alone entitlement. You are responsible for provisioning your own Kubernetes cluster for image deployment. Additionally, you will need to [open ports in your firewall](/docs/op-sw?topic=blockchain-sw-252-ibp-security#ibp-security-ibp-ports) if you are using one.
{: important}

## Is Fabric Operations Console suitable for you?
{: #get-started-console-foc-suitable}

| |Fabric Operations Console  |
|----|----|
| Where do you want to deploy the platform?|  Multiple Kubernetes distributions on a private, public or hybrid **multicloud** <br><br> See [Supported Platforms](/docs/op-sw?topic=blockchain-sw-252-console-foc-about#console-foc-about-prerequisites) | 
| What are my deployment options? | Only Fabric Operations Console images ** | 
| Can I connect with Peers in other clouds? |  Yes| 
| Can my data center be on-prem and behind a firewall? | Yes| 
| Are APIs available for node management? | Yes | 
| Does the product integrate with the Fabric Operations Console VSCode extension to develop and test my smart contracts?| Yes |
| I am an experienced Fabric customer. Are peer, CA, orderer, and smart contract images available and supported? | Yes |
| Where can I learn more? |See [About Fabric Operations Console](/docs/op-sw?topic=blockchain-sw-252-console-foc-about#console-foc-about-offers) | 
| Ready to get started? | See [Step one: Install the Fabric Operations Console](/docs/op-sw?topic=blockchain-sw-252-get-started-console-foc#get-started-console-foc-step-two-deploy-console) |

{: caption="Table 1. Which offering is right for your business?" caption-side="bottom"}
** Fabric Operations Console images - Your Fabric Operations Console includes an entitlement to images for peer, CA, ordering service, and smart contract containers. The images are based on the open source Hyperledger Fabric code base and contain a number of enhancements for stability and serviceability. The Fabric Operations Console images do not include the Fabric Operations Console management console or operator. This offering is intended for experienced Fabric users with existing Fabric deployments. For more information, see [Using the Fabric Operations Console images](/docs/op-sw?topic=blockchain-sw-252-blockchain-images).  


### Developer Tools
{: #get-started-console-foc-dev-tools}

Are you a developer? Check out to install locally the [**Fabric Operations Console Developer Tools**](/docs/op-sw?topic=blockchain-sw-252-develop-vscode#develop-vscode), a free IDE that provides an explorer and commands accessible from the command palette for developing smart contracts quickly.

### Fabric Operations Console images
{: #get-started-console-foc-images}

- Your Fabric Operations Console images are based on the open source Hyperledger Fabric code base and contain a number of enhancements for stability and serviceability. The Fabric Operations Console images do not include the management console or operator. This offering is intended for experienced Fabric users with existing Fabric deployments. 

## Before you begin
{: #get-started-console-foc-set-up-foc}

1. Review the [Supported Platforms](/docs/op-sw?topic=blockchain-sw-252-console-foc-about#console-foc-about-prerequisites).

2. Install a Kubernetes cluster and log in to your cluster. If you are using OpenShift, see the [OpenShift Container Platform CLI](https://docs.openshift.com/container-platform/4.3/cli_reference/openshift_cli/getting-started-cli.html){: external} to deploy the CLI. If you are using an OpenShift cluster that was deployed with the {{site.data.keyword.IBM_notm}} Kubernetes Service, use these instructions to [Install the OpenShift Origin CLI](/docs/openshift?topic=openshift-openshift-cli#cli_oc).

3. If you are _not_ running the platform on Red Hat OpenShift Container Platform or Red Hat Open Kubernetes Distribution, you need to set up the NGINX Ingress controller and it needs to be running in [SSL passthrough mode](https://kubernetes.github.io/ingress-nginx/user-guide/tls/#ssl-passthrough){: external}.

4. If you are not deploying from Red Hat Marketplace, get the entitlement key from your MyIBM account in order to install the platform. For more information, see [Get your entitlement key](/docs/op-sw?topic=blockchain-sw-252-deploy-foc#deploy-foc-entitlement-key).

5. Review the persistent storage considerations for [OpenShift](/docs/op-sw?topic=blockchain-sw-252-deploy-foc-getting-started#deploy-foc-storage) or [Kubernetes](/docs/op-sw?topic=blockchain-sw-252-deploy-k8#deploy-k8-storage) depending on your platform.

## Step one: Install the Fabric Operations Console
{: #get-started-console-foc-step-two-deploy-console}

The Fabric Operations Console uses a [Kubernetes Operator](https://kubernetes.io/docs/concepts/extend-kubernetes/operator/){: external} to install the Fabric Operations Console console on your cluster and manage the deployment and your blockchain nodes. A cluster administrator can use your entitlement key to deploy the platform on any Kubernetes Cluster

-  If you are deploying the Fabric Operations Console on the OpenShift Container Platform, you can deploy the platform by using the steps in [Deploy Fabric Operations Console on the OpenShift Container Platform](/docs/op-sw?topic=blockchain-sw-252-deploy-foc). Or, if you prefer to deploy from the Red Hat Marketplace see [Deploy Fabric Operations Console from Red Hat Marketplace](/docs/op-sw?topic=blockchain-sw-252-deploy-foc-rhm).

- If you are deploying the Fabric Operations Console on open source Kubernetes or a distribution such as Rancher, use the steps described in the [Deploying Fabric Operations Console on Kubernetes](/docs/op-sw?topic=blockchain-sw-252-deploy-k8).

- If you are an experienced Hyperledger Fabric customer and prefer to only use the Fabric Operations Console images, see [Using the Fabric Operations Console images](/docs/op-sw?topic=blockchain-sw-252-blockchain-images). Consult the Fabric documentation for further deployment, configuration, and management instructions. The rest of the steps in this topic do not apply when using the images.

## Step two: Grant console access to other users
{: #get-started-console-foc-step-four-add-console-admin}

After the platform is deployed, the console administrator can log in to the console with the email address and password that was provided during console deployment. The password that was provided becomes the default password of the console, and is used by all new users to log in to the console for the first time. The administrator can then add new users to the console, allowing others to log in and start working with Fabric Operations Console nodes. The administrator can also set a new default password. To learn more, see [Managing users from the console](/docs/op-sw?topic=blockchain-sw-252-console-icp-manage#console-icp-manage-users).

## Step three: Use the console to create your components
{: #get-started-console-foc-build-network}

After you deploy the console, you can use it to create, operate, and govern Fabric Operations Console components on your Kubernetes cluster. To get started with building a blockchain network by using the management console, go to the [Build a network tutorial](/docs/op-sw?topic=blockchain-sw-252-ibp-console-build-network#ibp-console-build-network).

## Step four: Connect networks across clouds
{: #get-started-console-foc-import-nodes}

You can use your console to operate components that are running on other clusters. First, you need to export the component information to a JSON file from the console where the component was originally deployed. Then, you can import the node JSON file into the console that is deployed on your local cluster and manage the components across clouds. For more information, see [Importing nodes](/docs/op-sw?topic=blockchain-sw-252-ibp-console-import-nodes#ibp-console-import-nodes).
