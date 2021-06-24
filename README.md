# gcs-uploader

## Introduction

Customers require a user friendly tool that allows non-technical enterprise end-users to upload content to GCP. In media use cases, these uploads can be hundreds of gigabytes in size and are not suitable for upload via browser based interfaces.

The desktop uploader tool is designed for enterprises with non-technical end users who wish to upload large files from their desktops into the cloud on a regular basis. The desktop upload tool has the following features:
* Uploader desktop app
* Uses composable, parallel upload features of GCS
* Uses Google Auth in the cloud to prevent any propagation of sensitive credentials to the desktop app
* UI takes a list of files and folders in any combination and gives the user feedback on the progress of the various files

The system has been designed in a manner such that no sensitive information is shipped with the desktop app. All access to resources and credentials is provided through the Google authentication system. This allows the uploader to be a more secure desktop tool that can only be used by authorized users.

While the initial setup and configuration is a multi-step process for the system administrator, the actual operation of the uploader tool is, by design, exceedingly simple for the end user.

Please read the [User Manual](User-Manual.pdf) for detailed instructions on installing and operationalizing the gcs-uploader.


