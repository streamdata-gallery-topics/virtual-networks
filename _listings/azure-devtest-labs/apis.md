---
name: Azure DevTest Labs
x-slug: azure-devtest-labs
description: Azure DevTest Labs makes it easy to quickly create environments to deploy
  and test applications. Use reusable templates and artifacts to build Windows and
  Linux environments while minimalizing waste and controlling costs.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Virtual Networks
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-networks/master/_listings/azure-devtest-labs/apis.md
specificationVersion: "0.14"
apis:
- name: DevTestLabsClient - Virtual Networks List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworks-get
  description: List virtual networks in a given lab.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-networks/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-networks/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworks-get-openapi.md
- name: DevTestLabsClient - Virtual Networks Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-get
  description: Get virtual network.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-networks/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-networks/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-get-openapi.md
- name: DevTestLabsClient - Virtual Networks Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-put
  description: Create or replace an existing virtual network. This operation can take
    a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-networks/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-put-openapi.md
- name: DevTestLabsClient - Virtual Networks Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-delete
  description: Delete virtual network. This operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-networks/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-networks/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-delete-openapi.md
- name: DevTestLabsClient - Virtual Networks Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-patch
  description: Modify properties of virtual networks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/virtual-networks/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-patch-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.data.lake.store.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.devtest.labs.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/devtest-lab/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/devtest-lab/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/devtest-lab/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/devtest-lab/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---