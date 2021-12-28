# L2PTVPNScript

# Windows based L2PT VPN script

# About

I created a basic PowerShell based script that allows the IT Department to easily deploy an L2PT based VPN connection across all user accounts that allow staff to access our internal network for both store branches (Albany and Henderson) while working from home. This script also maps network drives onto the staff's computer.

# Reasoning for creating this script

We do not have an active directory setup at the time of making this script, so we cannot utilise GPO to deploy a script upon logon. Initially, we had to use CMD to deploy this script which can cause issues if we did not use the correct syntax. With this script, it allows us to dploy a secure VPN connection to access our Kitchen Cabinets and Stones internal network with just a single click of a button (not including entering radius credentials). This does not need administrator privilages.

# Improvements or further implementation

I would like to have this run as a logon script for every computer. Preferably, it would check if the vpn script has already been implemented, if so do not run. If not, run the script.

Feel free to use this script with some modifications to suit your environment!

https://user-images.githubusercontent.com/61443806/147519053-c14885a8-d5a6-4ffc-b580-7d9ab2ea75f1.mp4

