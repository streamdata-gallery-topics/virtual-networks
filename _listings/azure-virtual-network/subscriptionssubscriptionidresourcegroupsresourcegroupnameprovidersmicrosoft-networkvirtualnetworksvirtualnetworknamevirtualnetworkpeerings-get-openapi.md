---
swagger: "2.0"
x-collection-name: Azure Virtual Network
x-complete: 0
info:
  title: Azure Virtual Network API Virtual Network Peerings List
  description: Gets all virtual network peerings in a virtual network.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}
  : delete:
      summary: Virtual Networks Delete
      description: Deletes the specified virtual network.
      operationId: VirtualNetworks_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkvirtualnetworksvirtualnetworkname-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      responses:
        200:
          description: OK
      tags:
      - Virtual Networks
    get:
      summary: Virtual Networks Get
      description: Gets the specified virtual network by resource group.
      operationId: VirtualNetworks_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkvirtualnetworksvirtualnetworkname-get
      parameters:
      - in: query
        name: $expand
        description: Expands referenced resources
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      responses:
        200:
          description: OK
      tags:
      - Virtual Networks
    put:
      summary: Virtual Networks Create Or Update
      description: Creates or updates a virtual network in the specified resource
        group.
      operationId: VirtualNetworks_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkvirtualnetworksvirtualnetworkname-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the create or update virtual network operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      responses:
        200:
          description: OK
      tags:
      - Virtual Networks
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/virtualNetworks:
    get:
      summary: Virtual Networks List All
      description: Gets all virtual networks in a subscription.
      operationId: VirtualNetworks_ListAll
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-networkvirtualnetworks-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Networks
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks:
    get:
      summary: Virtual Networks List
      description: Gets all virtual networks in a resource group.
      operationId: VirtualNetworks_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkvirtualnetworks-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Virtual Networks
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}/CheckIPAddressAvailability
  : get:
      summary: Virtual Networks Check IPAddress Availability
      description: Checks whether a private IP address is available for use.
      operationId: VirtualNetworks_CheckIPAddressAvailability
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkvirtualnetworksvirtualnetworknamecheckipaddressavailability-get
      parameters:
      - in: query
        name: ipAddress
        description: The private IP address to be verified
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      responses:
        200:
          description: OK
      tags:
      - Virtual Networks
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}/virtualNetworkPeerings/{virtualNetworkPeeringName}
  : delete:
      summary: Virtual Network Peerings Delete
      description: Deletes the specified virtual network peering.
      operationId: VirtualNetworkPeerings_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkvirtualnetworksvirtualnetworknamevirtualnetworkpeeringsvirtualnetworkpeeringname-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      - in: path
        name: virtualNetworkPeeringName
        description: The name of the virtual network peering
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Peerings
    get:
      summary: Virtual Network Peerings Get
      description: Gets the specified virtual network peering.
      operationId: VirtualNetworkPeerings_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkvirtualnetworksvirtualnetworknamevirtualnetworkpeeringsvirtualnetworkpeeringname-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      - in: path
        name: virtualNetworkPeeringName
        description: The name of the virtual network peering
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Peerings
    put:
      summary: Virtual Network Peerings Create Or Update
      description: Creates or updates a peering in the specified virtual network.
      operationId: VirtualNetworkPeerings_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkvirtualnetworksvirtualnetworknamevirtualnetworkpeeringsvirtualnetworkpeeringname-put
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      - in: path
        name: virtualNetworkPeeringName
        description: The name of the peering
      - in: body
        name: VirtualNetworkPeeringParameters
        description: Parameters supplied to the create or update virtual network peering
          operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Peerings
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}/virtualNetworkPeerings
  : get:
      summary: Virtual Network Peerings List
      description: Gets all virtual network peerings in a virtual network.
      operationId: VirtualNetworkPeerings_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkvirtualnetworksvirtualnetworknamevirtualnetworkpeerings-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Peerings
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---