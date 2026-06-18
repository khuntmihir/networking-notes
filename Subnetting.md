# Subnetting

Subnetting is the process of dividing a network into smaller networks called subnets.

## Why Subnetting is Used

- Improves network performance
- Reduces broadcast traffic
- Enhances security
- Makes network management easier

## IPv4 Address Structure

Example:

192.168.1.10

IPv4 addresses contain 32 bits.

They consist of:

- Network Portion
- Host Portion

## Common Private IP Ranges

### Class A

10.0.0.0 – 10.255.255.255

### Class B

172.16.0.0 – 172.31.255.255

### Class C

192.168.0.0 – 192.168.255.255

## Common Subnet Masks

| Subnet Mask | CIDR |
|-------------|-------|
| 255.0.0.0 | /8 |
| 255.255.0.0 | /16 |
| 255.255.255.0 | /24 |

## Example

IP Address:

192.168.1.100

Subnet Mask:

255.255.255.0

Network Address:

192.168.1.0

Broadcast Address:

192.168.1.255

## Why Subnetting Matters

Cybersecurity analysts use subnetting to:

- Understand network layouts
- Identify devices
- Investigate incidents
- Perform network segmentation
