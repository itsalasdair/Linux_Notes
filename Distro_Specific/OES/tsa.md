# TSA Commands

Find node which resource is running on

Check if eDir is running:\
`ndsrepair -T`

Check is Storage Management Serivces is running (this governs the TSA's):\
`rcnovell-smdrd status`

Check TSA's are loaded:\
`smsconfig -t`

To unload:\
`smsconfig -u $tsaname`

To load:\
`smsconfig -l $tsaname`

