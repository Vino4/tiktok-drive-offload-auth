# SR4710 Drive Offload

A personal recording archive tool that uploads completed TikTok recordings
from the operator's server to the Google Drive account selected during
authorization.

The uploader verifies each archive using file size and a checksum. A background
service retries interrupted uploads. Optional local cleanup requires a verified
archive copy.

Google authorization uses the limited `drive.file` scope. The app accesses
archive files and folders it creates or that the user explicitly selects.

Read the [privacy policy](PRIVACY.md). Operator contact is matt@almenshad.com.
