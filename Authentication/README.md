# Legal Disclaimer
This script is an example script and is not supported under any Zerto support program or service. The author and Zerto further disclaim all implied warranties including, without limitation, any implied warranties of merchantability or of fitness for a particular purpose.

In no event shall Zerto, its authors or anyone else involved in the creation, production or delivery of the scripts be liable for any damages whatsoever (including, without limitation, damages for loss of business profits, business interruption, loss of business information, or other pecuniary loss) arising out of the use of or the inability to use the sample scripts or documentation, even if the author or Zerto has been advised of the possibility of such damages.  The entire risk arising out of the use or performance of the sample scripts and documentation remains with you.

# Authentication
The YAML file and python code provided in this folder will allow a user to leverage Ansible to authenticate with a Zerto Virtual Manager (ZVM) and receive an API session key for futher use
with Zerto ZVMs API

# Getting Started

# Prerequisites
Environment Requirements:
- Ansible
- Python 3.7
- ZVR 5.0 +

YAML Requirements:
- Zerto User Name, Password, IP

# Running Ansible Module
Once the necessary requirements have been completed select an appropriate host to run the script from. To run the script type the following:
ansible-playbook Authentication.yml
