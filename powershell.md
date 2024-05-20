# Hyper-V management

Get list of network adaptes
`Get-NetAdapter`

Create `external` virtual switch
`New-VMSwitch -Name <switch-name>  -NetAdapterName <netadapter-name>`

Create a VM
`new-vm -Name "WSTEST" -MemoryStartupBytes 2GB -Generation 2 -NewVHDPath "D:\hyper-v\virtualhard disks\WSTEST.vhdx" -NewVHDSizeBytes 60000000000 -Switchname "External"`
