# Upgrade Ubuntu from 20.04 to 22.04

### Update existing version
`apt update -y ; apt upgrade -y ; apt dist-upgrade -y`

### Clean up unused packages/files
`apt autoremove --purge -y`

### Install Update Manager Core
`apt install -y update-manager-core`

### Verify upgrade path
Check the following file to make sure `lts` is the upgrade path:
`nano /etc/update-manager/release-upgrades`

### Run Upgrade
`do-release-upgrade -d`

Approve the download and installation of upgrade

Once done, `reboot`. You can then clean up with - `apt autoremove --purge -y`

