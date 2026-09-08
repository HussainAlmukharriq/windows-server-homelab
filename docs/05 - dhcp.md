# DHCP Configuration and Management

## Objective

Configure and manage DHCP on Windows Server 2022 to automatically provide network configuration to client devices and gain hands-on experience with DHCP scopes, leases, exclusions, and reservations.

## DHCP Server Configuration

I installed the DHCP Server role on DC01 and authorized the server within Active Directory.

I then created and configured a DHCP scope to provide network configuration to client devices.

The configuration included:

- DHCP scope creation
- IP address range configuration
- DHCP authorization
- Address leases
- Exclusion ranges
- DHCP reservations

## DHCP Leases

I used the DHCP management console to view active leases and identify devices that had received addresses from the DHCP server.

This provided practical experience in understanding how DHCP tracks address assignments and how leases are associated with client devices rather than individual domain users.

## Exclusion Ranges

I configured DHCP exclusions to prevent selected addresses within the scope from being dynamically assigned.

This demonstrated how portions of an address range can be reserved for devices that require manually managed or otherwise unavailable addresses.

## DHCP Reservations

I created DHCP reservations for selected client devices.

Reservations allow a device to continue using DHCP while consistently receiving the same IP address based on its network adapter's MAC address.

This provided experience working with:

- Client IP addresses
- MAC addresses
- DHCP leases
- Reservations
- Address management

## Client Testing

I tested DHCP configuration from client devices by renewing their network configuration and verifying the resulting address assignments.

I also monitored the DHCP management console to confirm that leases and reservations behaved as expected.

## What I Learned

This portion of the homelab provided hands-on experience with:

- Installing the Windows Server DHCP role
- Authorizing a DHCP server
- Creating and configuring DHCP scopes
- Managing DHCP leases
- Creating exclusion ranges
- Creating DHCP reservations
- Associating reservations with client MAC addresses
- Renewing client network configurations
- Verifying DHCP behavior from both the server and client side
