# Upgrading openSUSE 15.2 to 15.3

### Refresh repositories and upgrade
`zypper ref`\
`zypper up`

### Check upgrade repo and verify
`zypper lr -u`

Verify we can get the 15.3 repo
`zypper --releasever=15.3 lr -u`

### Refresh repositories with 15.3 URI's
`zypper --releasever=15.3`

### Perform Distribution Upgrade
`zypper --releasever=15.3 dup`

and `reboot` once done
