# proxmox_iptables_recent_params_fix
Quick fix instructions on how to change read-only parameters of the recent module in a proxmox installation.

1. Create or edit your `/etc/modprobe.d/xt_recent.conf`
2. Add the options you want to change for example `options xt_recent ip_list_tot=XXX ip_pkt_list_tot=YYY`
3. Hard reset your server
