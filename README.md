Firewall Configuration

## Objective
Configured and tested basic firewall rules using UFW on Ubuntu.

## Steps Performed
1. Enabled UFW and listed existing rules.
2. Blocked inbound traffic on Port 23 (Telnet).
3. Allowed SSH on Port 22.
4. Verified the block using telnet.
5. Took relevant screenshots.
   
## Commands Used
```bash
sudo ufw enable
sudo ufw status numbered
sudo ufw deny 23
sudo ufw allow 22
# firewall-task
