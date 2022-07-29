  
# Seamless Platform Technical Documentation
Author | Reviewer | Published | Version | Changes
--|--|--|--|--
Susanta Das|Saradwata Sen|29-7-2022|0.1|Initial version

## Architecture
## System Diagram

## Platform
### Overview
### Directure Structure
### UI Components
### Generator
### Workflow
#### Business Rule
### Test
#### Test Plan
#### Automated Tests
##### Sanity Tests
##### Regression Tests
#### Manual Tests
##### Sanity Tests
##### Regression Tests

## Application
### Overview
### Create Application
#### Configuration
#### Steps
##### Routes
##### Views
###### Configuration
##### Static Resources
### Directory Structure
### Deployment
### Test
#### Test Plan
#### Automated Tests
##### Sanity Tests
##### Regression Tests
#### Manual Tests
##### Sanity Tests
##### Regression Tests



Notes:
- deployment script
- 

Here's a directory structure for a Seamless Platform:

```
|- app                      # Directory for application related files.
  |- apis                   # Directory for public api related files.
  |- routes                 # Directory for route related files.
  |- services               # Directory for service related files of application.
  |- templates              # Directory for template files of application.
  |- views                  # Directory for view related files.
    |- partials             # Directory for partials of view related files.
|- core                     # Directory for core files of platform.
  |- handlers               # Directory for core middleware files of platform.
  |- libs                   # Directory for core library files of platform.
  |- services               # Directory for core service related files of platform.
|- public                   # Directory for public facing files of platform.
```

- app
  - apis
  - routes


Here's a folder structure for a Seamless Application:

```
|- app                      # Directory for application related files.
  |- apis                   # Directory for public api related files of application.
  |- flows                  # Directory for workflow related files of application.
  |- forms                  # Directory for form related files of application.
  |- licenses               # Directory for license related files.
  |- privileges             # Directory for privilege related files of application.
  |- reports                # Directory for report related files of application.
  |- routes                 # Directory for route related files of application.
  |- services               # Directory for service related files of application.
  |- templates              # Directory for template files of application.
  |- views                  # Directory for view related files of application.
|- cache                    # Directory for cache files of application.
|- config                   # Directory for configuration related files of application.
|- libs                     # Directory for library files of application.
|- locales                  # Directory for locale files of application.
|- public                   # Directory for public facing files of application.
|- session                  # Directory for session related files for application.
|- upload                   # Directory for temporary uploaded files for application.
```
