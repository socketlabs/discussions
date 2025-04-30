# SocketLabs API

# [1.0.33925] 2025-04-30
## Added

### Complex Sender Features

- Reporting Connectors - Adding new connector type for Reporting Subaccounts

## [1.0.32950] 2025-03-26
## Added

### All Account Types
* Reports
  * All message detail reports are adding a new column named ProcessedTime. Shows the time the at which the message was either delivered or failed.

## [1.0.30056] 2024-10-23
## Added

### All Account Types

* User Notifications
  * Account Admin and Billing roles are enrolled to receive Critical Billing and Suspension notifications.
  * Account Point of Contacts are enrolled to receive Critical Billing and Suspension notifications.

### Self Serve Features

* Servers
  * Added Multi-SuperTag maintenance

### Complex Sender Features

* Connectors
  * Added Multi-SuperTag maintenance for a Reporting Subaccount
* Reporting Subaccounts
  * Added Multi-SuperTag maintenance
* Advanced Authentication
  * Added ability to assign a DKIM record as an Identity DKIM on an IP Pool

## Changed

### Self Serve Features

* Servers
  * Removing single SuperTag Key from Server Config

### Complex Sender Features

* Connectors
  * Removing single SuperTag Key from Connector Config


## [1.0.28248] 2024-08-22

## Added
### All Account Types
- Reports
    - Added Event Date based reporting to all reports. Feature not available for all plans.
    - Added SuperTag as an aggregate type in all aggregate reports
- User Management - Ability to modify two factor authentication on behalf of a user by an Account Admin or a User Admin

### Complex Sender Features
- Advanced Authentication - Adding assignment of DKIM and Bounce Domains to Subaccounts from the Account.
- Rule Engine - Adding new rule types, Metadata, Tags, SuperTag.
- Domain Management - Adding optional sending domain restrictions. Feature not available for all plans.

## Changed
### All Account Types
- Reports - Added Event Date based reporting to all reports. Feature not available for all plans.

## [1.0.27085] 2024-07-18

## Added
**All Account Types**
- Reports - Added Tag Filter - filter applies to all overview and aggregate reports.

## Changed
### Complex Sender Features
- Subaccount Management - Adding SuperTag Key Management - Adds a new aggregate type in all aggregate reports

### Simple Sender Features
- Server Management - Adding SuperTag Key Management - Adds a new aggregate type in all aggregate reports

## \[1.0.26034\] 2024-06-06

### Changed
**All Account Types**
- Reporting
    - added functionality to support usage reporting
    - Fixed Message Detail Report filter errors for SystemMessageID

## \[1.0.21140\] 2024-05-08

### Changed
**All Account Types**
- Event Webhooks - modified Test Post examples to include the response from the webhook Url

## \[1.0.25130\] 2024-05-03

### Changed
**All Account Types**
- Reporting - Added additional performance enhancements

### Added
**Complex Sender Features**
- Subaccount StreamMonitor - Added Report by Sending Domain and SuperTag

## \[1.0.21140\] 2024-01-10

### Changed
**All Account Types**
- Reports - added 500,000 limits to cvs downloads

### Added
**Complex Sender Features**
- Reporting Connectors - Adding connectors for Reporting Subaccounts

## \[1.0.19528\] 2023-11-06

### Added
**All Account Types**
- Inbound Webhooks - Adding endpoints to add inbound webhooks on Servers and Subaccounts

## \[1.0.19104\] 2022-11-06

### Changed
**All Account Types**
- Reports - Added additional Detail types to message detail reports

## \[1.0.18656\] 2022-10-25

### Changed

**All Account Types**
- Reports - Additional performance enhancements and bugfixes

### Added

**Complex Sender Features**
- IP Pool Queue - Count, Detail, Pause & Purge functions

## [1.0.14432] 2022-5-10

### Added
**Simple Sender Features**
* Reports - Adding Hourly Aggregate to all reports

**Complex Sender Features**
* Reports - Adding Hourly Aggregate to Sending Overview

### Changed
**All Account Types**
* User Management
  * Add, Edit, Delete User
  * Update User Preferences

## [1.0.14006] 2022-04-26
### Added
**Simple Sender Features**
* Server: Sending IP List

**Complex Sender Features**
* Subaccount: Sending IP List
* IP Pool
  * Sending IP List
  * Adding Count of Subaccounts processed to IP Pool Response
  *
## [1.0.13466] 2022-4-5

### Added
**Simple Sender Features:**
* Server - Get single Server, server name update
* Advanced Settings - non-delivery, overage settings, auto Bcc
* Queue - Count, Detail, Pause & Purge functions
* Reports - Marketing Mailings

### Changed
**Simple Sender Features:**
* Server - Adding Detail to get servers


## [1.0.12509] 2023-3-8
### Added
**Complex Sender Features:**
* Account Engagement Tracking Domains
* Account Bounce Domains
* Account DKIM Identity Domains
* StreamMonitor Top Insights Reports
  * List Hygiene
  * Recipient Frequency
  * Sign-up Policies

### Changed
**Simple Sender Features:**
* Server - Engagement Tracking Default Settings Updates
* Server Reports - Added Mailing Names from Marketing Mailings to reports
  * Delivered Messages Reports (Overview, Aggregates, & Detail)
  * Engagement Tracking Reports (Overview, Aggregates, & Detail)
  * Complaints Reports (Overview, Aggregates, & Detail)
  * Failed Messages Reports (Overview, Aggregates, & Detail)
  * Inbound Parse Reports (Overview & Detail)


## [1.0.12004] 2023-2-15
### Added
**Complex Sender Features:**
* StreamMonitor - IpPool Reports

### Changed
**Simple Sender Features:**
* Server - Engagement Tracking Default Settings Updates

**Complex Sender Features:**
* Subaccount - Engagement Tracking Default Settings Updates


## [1.0.11605] 2023-2-1
### Changed
**Simple Sender Features:**
* Server Reports - General Maintenance
  * Delivered Messages Reports (Overview, Aggregates, & Detail)
  * Engagement Tracking Reports (Overview, Aggregates, & Detail)
  * Complaints Reports (Overview, Aggregates, & Detail)
  * Failed Messages Reports (Overview, Aggregates, & Detail)
  * Inbound Parse Reports (Overview & Detail)

**Complex Sender Features:**
* Subaccount Reports - General Maintenance
  * Delivered Messages Reports (Overview, Aggregates, & Detail)
  * Engagement Tracking Reports (Overview, Aggregates, & Detail)
  * Complaints Reports (Overview, Aggregates, & Detail)
  * Failed Messages Reports (Overview, Aggregates, & Detail)
  * Inbound Parse Reports (Overview & Detail)


## [1.0.10864] 2022-12-22
### Added
**Simple Sender Features:**
* Server Reports
  * Delivered Messages Reports (Overview, Aggregates, & Detail)
  * Inbound Parse Reports (Overview & Detail)
* Marketing Api Credentials

**Complex Sender Features:**
* Subaccount Reports
  * Delivered Messages Reports (Overview, Aggregates, & Detail)
* Rule Engine

### Changed
**Simple Sender Features:**
* Server Credentials
* Subaccount Credentials



## [1.0.10113] 2022-11-15
### Added
**Simple Sender Features:**
* User Management
* Server Reports
  * Recipient Search
  * Engagement Tracking Reports (Overview, Aggregates, & Detail)
  * Complaints Reports (Overview, Aggregates, & Detail)
  * Failed Messages Reports (Overview, Aggregates, & Detail)

### Changed
**Complex Sender Features:**
* StreamMonitor (Performance Enhancements and data additions)
* Subaccount Reports
  * Recipient Search
  * Engagement Tracking Reports (Overview, Aggregates, & Detail)
  * Complaints Reports (Overview, Aggregates, & Detail)
  * Failed Messages Reports (Overview, Aggregates, & Detail)



## [1.0.9394] 2022-10-13
### Added
**Simple Sender Features:**
* Server Credentials

**Complex Sender Features:**
* Subaccount Credentials
* Message Reports (Overview, Aggregates, & Detail)
* Account Api Credentials

### Changed
**Simple Sender Features:**
* StreamMonitor (Performance Enhancements and data additions)



## [1.0.8847] 2022-09-22
### Added
**Complex Sender Features:**
* Message Overview Reports
* Account Level Suppressions
* Account Level Webhooks


## [1.0.8204] 2022-09-01
# Added
**Complex Sender Features:**
* IP Pool
* Subaccount
* IP Allocation
* Suppression List (formerly Suppression API)
* Event Webhook (formerly Notification API)
* Existing Management API endpoints upgraded as v2 with response types upgraded to v2 response types.
* Bounce Domain
* DKIM
* CName DKIM
* Tracking Domain
* Encrypted Tracking Domain
* Sending Domain
* Event Search
*
### Changed
**Simple Sender Features:**
* Existing Management API endpoints upgraded as v1.
* Bounce Domain
* DKIM
* CName DKIM
* Tracking Domain
* Encrypted Tracking Domain
* Sending Domain
* Event Search

# Management API
As of 2022-09-01 the Management is being deprecated. All existing functions still exist under v1 of the SocketLabs API.

## [1.0.484] 2022-05-17
### Added
* CName DKIM

## [1.0.459] 2022-04-12
### Added
* Sandbox Restrictions

## [1.0.438] 2022-03-08
### Added
* Sending Domain
* Domain Verification

## [1.0.431] 2021-09-16
### Added
* Event Search

## [1.0.424] 2021-08-25
### Added
* CRM Integration

## [1.0.413] 2021-05-15
Initial Release

### Added
* Bounce Domain
* DKIM
* Tracking Domain
* Encrypted Tracking Domain
