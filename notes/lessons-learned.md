# Lessons Learned

## Ubuntu Networking
Initially experienced DHCP autoconfiguration failure due to incorrect VMware bridged adapter selection.

Resolved by:
- Configuring VMnet0 manually
- Bridging directly to the physical Realtek network adapter

## Wazuh Installation
The all-in-one Wazuh dashboard installation failed on Ubuntu 24.04. Pivoted to installing only the Wazuh manager component to reduce resource usage and simplify the initial SOC lab deployment.