# Azure Storage Services

## Storage Types

- Azure Blob Storage

  - Unstructured blobs
  - stored in containers
  - Types
    - block blobs
    - append blobs: appending to an existing blob
    - page blobs

- Azure Disks

  - stores disks used in Azure VMs
  - HDD or SSD
  - persists storage for VM

- Azure Files
  - SMB based file storage
  - provides disk space in the cloud
  - sync locally with Azure File Sync

## Storage Tiers

- Hot
  - Often-used data
- Cool
  - data stored for longer periods
- Archive
  - Long-term storage

## Redundancy options

- Locally-redundant storage (LRS)
  - three copies of your data are created
  - least durable
- Zone-redundant storage (ZRS)
  - three copies, accross the zone
- Geo-redundant storage (GRS)
  - three LRS copies, three LRS copies in another region
- Geo-zone-redundant
  - three ZRS copies, three ZRS copies in another region

## Storage Account Options

- Standard
  - general-purpose v2
- Premium
  - block blobs
  - LRS and ZRS options
  - File shares
  - page blobs - supports LRS redundancy

## Options for Moving Files

- AzCopy
  - Command line tool to copy blobs and files to and from Azure storage
  - can copy entire directories
  - can be scripted
- Azure Storage Explorer
  - GUI for interacting with Azure files
  - Generate SAS tokens
  - change storage tiers
  - Create and manage storage containers
- Azure File Sync
  - Sync Azure files to on-prem
  - Speeds up interacting with files

## Migration options

- Azure Migrate
  - Migrates servers, databases, web apps, etc.
  - Discover -> Assess -> Migrate
- Azure Data Box
  - Migrate massive data
  - Three offerings:
    - Data Box Disk (single disk, only 1 storage account)
    - Data Box (up to 80TB)
    - Data Box Heavy (up to 1PB)
