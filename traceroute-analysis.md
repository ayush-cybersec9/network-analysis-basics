# Traceroute Analysis

## Command Used
tracert google.com

## Observations
- Data passed through multiple hops (routers)
- Each hop represents an intermediate network device
- Some hops returned * * * (no response)
  Means the router is secured , maybe it blocks icmp packets or
  firewall drops traceroute packets ..
  router is still forwarding data , just not responding to us.

## Explanation
- Routers may block ICMP responses for security reasons
- Even if no response is received, traffic is still forwarded

## Key Learning
Internet communication is not direct — it passes through multiple networks
