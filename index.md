# Awesome Cloud Foundry [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of Cloud Foundry open-source tools, distributions, talks and tutorials(videos and blog post).

Cloud Foundry is an open source platform that allows application development teams to build, test, deploy, and scale applications. It also provides an underlying infrastructure including Kubernetes, developer frameworks, and application services.

- [The Official Cloud Foundry Website](https://cloudfoundry.org)
- [Join the Cloud Foundry Community](https://slack.cloudfoundry.org)

## Content

- [Projects](#Projects)
- [Distributions](#Distributions)
- Articles
  - Buildpacks
  - CF-for-k8s
  - CI/CD
  - Deployments
  - Installation
  - KubeCF
  - Logging
  - Monitoring
  - Network
  - Services
- Books
- Courses
- Videos
- Podcasts
- Slides Presentation
- Conferences
- Meetup Groups

# Projects

- [BOSH](https://bosh.io/docs/) - Bosh an open source tool for release engineering, deployment, lifecycle management, and monitoring of distributed systems.
- [Cloud Foundry CLI](https://github.com/cloudfoundry/cli) - The official command line client for Cloud Foundry
- [CF Dev](https://github.com/cloudfoundry-attic/cfdev) - CF Dev is a distribution of Cloud Foundry designed to run on a developer’s laptop or workstation using native hypervisors and a fully functional BOSH Director.
- [CF-for-K8s](https://cf-for-k8s.io) - Cloud Foundry For Kubernetes (cf-for-k8s) blends the popular CF developer API with Kubernetes, Istio, and other open source technologies.
- [Diego](https://github.com/cloudfoundry/diego-release) - Diego is the container runtime for the Application Runtime, making it possible to run applications with Buildpacks or Docker images
- [Erini](https://eirini.cf) - Eirini is a project that provides pluggable scheduling for the Cloud Foundry Application Runtime
- [KubeCF](https://github.com/cloudfoundry-incubator/kubecf) - KubeCF is a distribution of Cloud Foundry Application Runtime (CFAR) for Kubernetes
- [Loggregator](https://github.com/cloudfoundry/loggregator-release) - Loggregator provides a highly-available (HA) and secure stream of logs and metrics for all applications and components on Cloud Foundry.
- [paketo](https://paketo.io/) - Paketo are Modular Buildpacks written in Go that leverage and contribute to the Cloud Native Buildpacks framework
- [UAA](https://github.com/cloudfoundry/uaa) - The UAA is a multi tenant identity management service, used in Cloud Foundry, but also available as a stand alone OAuth2 server.
- [Stratos](https://github.com/cloudfoundry/stratos) - Stratos is an Open Source Web-based UI (Console) for managing Cloud Foundry Clusters.

# Distributions

- ## Certified Distributions

  Certified Provider distributions use the same core Cloud Foundry software and are portable across cloud application platforms in a multi-vendor, multi-cloud environment.

  - [Atos Cloud Foundry](https://atos.net/en/solutions/multi-cloud-application-platform) - Atos Cloud Foundry is a multi-cloud platform, fully managed by Atos, supporting our customers in their digital business strategy.

  - [Cloud.gov](https://cloud.gov/) - cloud.gov is based on Cloud Foundry, enabling instant provisioning of services and environments, easy deployment of applications, and rapid scaling to match demand.
  - [IBM Cloud Foundry](https://www.ibm.com/cloud/cloud-foundry) - The IBM Cloud Foundry platform is not just about creating new apps or migrating existing ones, on-prem or off-prem implementations, or offering IaaS and PaaS cloud services.
  - [SAP Cloud Platform](https://www.sap.com/products/cloud-platform.html) - SAP Cloud Platform is the enterprise platform-as-a-service with comprehensive application development services and capabilities.
  - [SUSE Cloud Application Platform](https://www.suse.com/products/cloud-application-platform/) - SUSE Cloud Application Platform is a modern application delivery platform used by software development and operations teams to streamline lifecycle management of traditional and new cloud native applications
  - [Swisscom Application Cloud](https://www.swisscom.ch/en/business/enterprise/offer/cloud-data-center/application-cloud.html) - Swisscom Cloud Foundry is provided from the most modern and secure data centres in Switzerland. Corporate customers particularly value our Virtual Private offering and managed enterprise-grade services.
  - [VMware Tanzu](https://tanzu.vmware.com/tanzu) - VMware Cloud Foundry® is the world’s most powerful cloud-native platform to build and run software.

- ## Other Distributions
  - [anynines Public Paas](https://paas.anynines.com/) - Anynines Public PaaS (a9s) is a platform as a service that is built on top of Cloud Foundry

# Articles

This is a list of Articles based on various Cloud Foundry concepts and topics that can be very useful.

## Cf-for-K8s

- [Deploy A Java Application To Kubernetes With Cloud Foundry](https://medium.com/cloud-foundry-foundation/deploy-a-java-application-to-kubernetes-with-cloud-foundry-c3be6c34e0cb)
- [Deploying Your First PHP Application to Kubernetes Using Cloud Foundry](https://medium.com/cloud-foundry-foundation/deploying-your-first-php-application-to-kubernetes-using-cloud-foundry-901c390165bc)
- [How to Deploy a Django App to Kubernetes With Cloud Foundry](https://medium.com/cloud-foundry-foundation/how-to-deploy-a-django-app-to-kubernetes-with-cloud-foundry-5ad332fbe197)
- [How to Install Application Monitoring Tools on cf-for-k8s](https://medium.com/cloud-foundry-foundation/how-to-install-application-monitoring-tools-on-cf-for-k8s-8aa462c47c1a)
- [Installing cf-for-k8s on a Kubernetes Cluster Running on DigitalOcean](https://medium.com/cloud-foundry-foundation/installing-cf-for-k8s-on-a-kubernetes-cluster-running-on-digitalocean-acffdc652dcf)
- [Installing cf-for-k8s on Google Cloud GKE](https://medium.com/cloud-foundry-foundation/installing-cf-for-k8s-on-google-cloud-gke-5d6902ee99fa)
- [Using Cloud Native Buildpacks And Deploying to Kubernetes With Cloud Foundry](https://medium.com/cloud-foundry-foundation/using-cloud-native-buildpacks-and-deploying-to-kubernetes-with-cloud-foundry-eca190195fd)

## Deployment

- [Cloud Foundry Essentials](https://medium.com/cloud-foundry-foundation/cloud-foundry-essentials-601e794f102d)
- [Deploying apps on IBM Cloud Foundry](https://cloud.ibm.com/docs/cloud-foundry-public?topic=cloud-foundry-public-deployingapps)
- [Deploy a Nodejs App to Cloud Foundry](https://medium.com/cloud-foundry-foundation/deploy-a-nodejs-app-to-cloud-foundry-via-pivotal-bf2662f59a6f)
- [Deploying a PHP application to Cloud Foundry (OpenCart)](https://medium.com/cloud-foundry-foundation/deploying-a-php-application-to-cloud-foundry-opencart-e160a87c2eb0)
- [Deploy a Sample Ruby on Rails Application](https://docs.cloudfoundry.org/buildpacks/ruby/sample-ror.html)
- [Deploying a Spring Boot Application to Cloud Foundry](https://www.baeldung.com/spring-boot-app-deploy-to-cloud-foundry)
- [Deploy Cloud Foudry To Google Kubernetes in 10 Minutes](https://www.starkandwayne.com/blog/deploy-cf-for-k8s-to-google-in-10-minutes/)
- [Getting Started with Cloud Foundry for Kubernetes](https://tanzu.vmware.com/developer/guides/kubernetes/cf4k8s-gs/)
- [How to Deploy a Django App Using Cloud Foundry](https://medium.com/cloud-foundry-foundation/deploy-a-django-app-using-cloud-foundry-8d74769c9a12)
- [Installing Drupal (PHP) As A First Time Cloud Foundry User](https://medium.com/cloud-foundry-foundation/installing-drupal-php-as-a-first-time-cloud-foundry-user-ef557c3646a6)
- [Running cf-for-k8s on minikube](https://www.starkandwayne.com/blog/running-cf-for-k8s-on-minikube/)

##
