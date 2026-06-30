# ARP Analysis

## Command Used
arp -a

## Observations
- ARP table contains IP to MAC mappings of devices in the local network
- Entries are created only after communication occurs
- Some entries may appear as incomplete if no response is received

## Experiment
- Pinged a device not in ARP table
- Observed ARP request broadcast
- Entry was added after receiving response

## Key Learning
ARP is a trust-based protocol and can be exploited (ARP spoofing)
