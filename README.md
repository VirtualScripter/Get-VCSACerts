# Get-VCSACerts
Powershell script to retrieve vCenter and host certificates and details

Changelog:
5-4-2021
  Added a filter when retrieving hosts to exclude disconnected and powered off hosts.  
  Changed Try/Catch for the hosts to be inside the foreach statement
5-6-2022
  Automatically remove any duplicate certificates when using the -all flag
