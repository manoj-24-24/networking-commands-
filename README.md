# Networking Commands.

## Network Information

| Command | Purpose | Example |
|---|---|---|
| `ip addr` | Show IP addresses and interfaces | `ip addr` |
| `ip route` | Show routing table | `ip route` |
| `hostname` | Show system hostname | `hostname` |
| `ss` | Show network connections | `ss -tuln` |

## Connectivity

| Command | Purpose | Example |
|---|---|---|
| `ping` | Test connectivity | `ping 8.8.8.8` |
| `traceroute` | Trace network path | `traceroute example.com` |
| `curl` | Make HTTP requests | `curl https://example.com` |

## DNS

| Command | Purpose | Example |
|---|---|---|
| `nslookup` | Query DNS | `nslookup example.com` |
| `dig` | Perform detailed DNS queries | `dig example.com` |
| `host` | Perform DNS lookup | `host example.com` |

## Security Analysis

### View listening ports

```bash
ss -lntup
