# D2TrialsFirewall
If you know you know
**Clone repo or run this command:**

`wget -q https://raw.githubusercontent.com/Steinyamite/d2FirewallStock/main/d2firewallOG.sh -O ./d2firewallOG.sh`

**Usage**

**Setup: initial setup** `sudo bash d2firewallOG.sh -a setup`

**Add: add a sniffed id to your firewall** `sudo bash d2firewallOG.sh -a add`

**Remove: remove ids from the end of the list** `sudo bash d2firewallOG.sh -a remove`

**Sniff: Auto sniffer. (You must add your 2 host consoles prior to running this)** `sudo bash d2firewallOG.sh -a sniff`

**Start: Disables public matchmaking** `sudo bash d2firewallOG.sh -a start`

**Stop: Enables public matchmaking** `sudo bash d2firewallOG.sh -a stop`

**List: List the current accounts** `sudo bash d2firewallOG.sh -a list`

**Update: Update the script to the newest version.** `sudo bash d2firewallOG.sh -a update`

**Load: Load the saved rules after a reboot** `sudo bash d2firewallOG.sh -a load`

**Reset: Reset iptables to default** `sudo bash d2firewallOG.sh -a reset`
