---
name: Google Compute Engine
x-slug: google-compute-engine
description: Google Compute Engine delivers virtual machines running in Googles innovative
  data centers and worldwide fiber network. Compute Engines tooling and workflow support
  enable scaling from single instances to global, load-balanced cloud computing.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Disk
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/disk/master/_listings/google-compute-engine/apis.md
specificationVersion: "0.14"
apis:
- name: Google Compute Engine API Get Disk Type
  x-api-slug: google-compute-engine-api
  description: Retrieves an aggregated list of disk types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/diskTypes
  tags: Disk,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disk/master/_listings/google-compute-engine/projectaggregateddisktypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disk/master/_listings/google-compute-engine/projectaggregateddisktypes-get-openapi.md
- name: Google Compute Engine API Get Disks
  x-api-slug: google-compute-engine-api
  description: Retrieves an aggregated list of persistent disks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/disks
  tags: Disk,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disk/master/_listings/google-compute-engine/projectaggregateddisks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disk/master/_listings/google-compute-engine/projectaggregateddisks-get-openapi.md
- name: Google Compute Engine API Move Disk
  x-api-slug: google-compute-engine-api
  description: Moves a persistent disk from one zone to another.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/moveDisk
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disk/master/_listings/google-compute-engine/projectmovedisk-post-openapi.md
- name: Google Compute Engine API Get Zone Disk Types
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of disk types available to the specified project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/diskTypes
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disk/master/_listings/google-compute-engine/projectzoneszonedisktypes-get-openapi.md
- name: Google Compute Engine API Get Zone Disk Type
  x-api-slug: google-compute-engine-api
  description: Returns the specified disk type. Get a list of available disk types
    by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/diskTypes/{diskType}
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disk/master/_listings/google-compute-engine/projectzoneszonedisktypesdisktype-get-openapi.md
- name: Google Compute Engine API Get Zone Disks
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of persistent disks contained within the specified
    zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/disks
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disk/master/_listings/google-compute-engine/projectzoneszonedisks-get-openapi.md
- name: Google Compute Engine API Create Zone Disk
  x-api-slug: google-compute-engine-api
  description: Creates a persistent disk in the specified project using the data in
    the request. You can create a disk with a sourceImage, a sourceSnapshot, or create
    an empty 500 GB data disk by omitting all properties. You can also create a disk
    that is larger than the default size by specifying the sizeGb property.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/disks
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disk/master/_listings/google-compute-engine/projectzoneszonedisks-post-openapi.md
- name: Google Compute Engine API Delete Zone Disk
  x-api-slug: google-compute-engine-api
  description: Deletes the specified persistent disk. Deleting a disk removes its
    data permanently and is irreversible. However, deleting a disk does not delete
    any snapshots previously made from the disk. You must separately delete snapshots.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/disks/{disk}
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disk/master/_listings/google-compute-engine/projectzoneszonedisksdisk-delete-openapi.md
- name: Google Compute Engine API Get Zone Disk
  x-api-slug: google-compute-engine-api
  description: Returns a specified persistent disk. Get a list of available persistent
    disks by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/disks/{disk}
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disk/master/_listings/google-compute-engine/projectzoneszonedisksdisk-get-openapi.md
- name: Google Compute Engine API Create Snapshot of Zone Disk
  x-api-slug: google-compute-engine-api
  description: Creates a snapshot of a specified persistent disk.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/disks/{disk}/createSnapshot
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disk/master/_listings/google-compute-engine/projectzoneszonedisksdiskcreatesnapshot-post-openapi.md
- name: Google Compute Engine API Resize Zone Disk
  x-api-slug: google-compute-engine-api
  description: Resizes the specified persistent disk.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/disks/{disk}/resize
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disk/master/_listings/google-compute-engine/projectzoneszonedisksdiskresize-post-openapi.md
- name: Google Compute Engine API Attach Disk to Zone Instance
  x-api-slug: google-compute-engine-api
  description: Attaches a Disk resource to an instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}/attachDisk
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disk/master/_listings/google-compute-engine/projectzoneszoneinstancesinstanceattachdisk-post-openapi.md
- name: Google Compute Engine API
  x-api-slug: google-compute-engine-api
  description: Google Compute Engine delivers virtual machines running in Googles
    innovative data centers and worldwide fiber network. Compute Engines tooling and
    workflow support enable scaling from single instances to global, load-balanced
    cloud computing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disk/master/_listings/google-compute-engine/openapi.md
x-common:
- type: x-code
  url: https://cloud.google.com/compute/docs/api/libraries
- type: x-documentation
  url: https://cloud.google.com/compute/docs/reference/latest/
- type: x-guides
  url: https://cloud.google.com/compute/docs/api/how-tos/how-tos
- type: x-rate-limits
  url: https://cloud.google.com/compute/docs/api-rate-limits
- type: x-sla
  url: https://cloud.google.com/compute/sla
- type: x-website
  url: https://cloud.google.com/compute/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---