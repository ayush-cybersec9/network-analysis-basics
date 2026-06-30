# Netstat Analysis

## Command Used
netstat -an

## Observations
- Multiple active connections were visible
- Local ports were random (ephemeral ports)
- Foreign addresses included port 443 (HTTPS)

## Explanation
- Each connection uses a unique local port
- Browsers open multiple connections for performance

## Key Learning
Systems handle multiple simultaneous connections using dynamic ports
