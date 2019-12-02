<snippet>
  <content>

## Backup Netscaler

The scope of this project is to write a script that creates and downloads a full
<br> backup from a Citrix Netscaler (ADC).
<br>Using this backup archive a restore of the whole appliance can be done.
<br>The script also does some clean-up. It deletes the backup from the Netscaler
<br>and the undecodded file from local directory.
<br> The backup archive will be located in the folder (backup_location) you define in the script.
<br> For example :  backup_location: "/home/ansible/ns_sys_backup"

## Installation

It is written in Ansible (ansible 2.7.1) The python version used is 2.7.12.
<br> Also, you need the Nitro API python SDK.

## Usage

Like any ansible script you will run it like this:
<br>ansible-playbook -i inventory  backupNS.yml

## Credits

This was written by Mihai Cziraki
</content>
</snippet>
