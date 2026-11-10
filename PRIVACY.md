# Privacy policy

SR4710 Drive Offload. Effective November 10, 2026.

## Purpose and Google data access

This personal-use application archives completed recordings to the Google Drive
account selected during authorization. It uses the `drive.file` scope to create
archive folders, upload recordings, and read archive file identifiers, names,
sizes, and checksums for verification. User-selected files or folders may also
be accessed when explicitly authorized.

## Storage and use

Recordings are sent from the operator's server to the selected Google Drive
destination. OAuth credentials are stored in a private configuration file on the
operator's server. Local verification receipts contain file identifiers, paths,
sizes, checksums, and timestamps. This information supports uploads, retries, and
optional verified local cleanup.

## Sharing and retention

The operator controls the server, Google account, archive folder, and Drive
sharing settings. The application uses Google APIs to provide the archive
service. Google user data is not sold, used for advertising, or used to train
AI models. Archive retention is controlled by the operator. Optional server-side
deletion occurs only after verification and the configured retention checks.

## Control

The operator can stop the upload service, revoke the application's access in
Google Account permissions, delete the server-side credentials and receipts,
and delete archive files through Google Drive. Revocation prevents further API
access but does not itself delete existing archive files.

The application's use and transfer of information received from Google APIs
adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including its Limited Use requirements.

Questions or deletion requests can be sent to matt@almenshad.com.
