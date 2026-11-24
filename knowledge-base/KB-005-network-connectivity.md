# KB-005 — Network Connectivity Issues

## Category

Network and Infrastructure

## Affected Service

Corporate Network and Internet Connectivity

## Symptoms

- No internet connection.
- Corporate resources are inaccessible.
- Slow or intermittent connectivity.
- Wi-Fi connection failures.
- DNS resolution errors.
- Invalid or missing IP address.

## Initial Troubleshooting

1. Identify the affected device and operating system.
2. Determine whether the connection uses Wi-Fi or Ethernet.
3. Verify physical connections and network adapter status.
4. Determine whether other users are affected.
5. Check IP configuration using `ipconfig /all` on Windows.
6. Test default gateway connectivity using `ping`.
7. Check DNS resolution using `nslookup`.
8. Review available network service status information.
9. Recommend approved troubleshooting procedures.

## Escalation Criteria

- Multiple users or departments are affected.
- Corporate network infrastructure is unavailable.
- Persistent DNS or DHCP failures are detected.
- Network equipment failure is suspected.
- Initial troubleshooting is unsuccessful.

## Recommended Support Team

Network and Infrastructure Support — Level 2.

## Service Restoration Validation

- Confirm successful network connectivity.
- Verify access to authorized corporate resources.
- Confirm DNS resolution and connection stability.
- Request confirmation from affected users.
- Document troubleshooting results.

## Safety and Restrictions

- Never disable firewalls or security controls.
- Never modify network infrastructure without authorization.
- Never assign unauthorized static IP addresses.
- Never restart corporate network equipment without approval.
- Never assume that a failed ping confirms a network outage.

## Article Status

Educational lab — simulated knowledge base article. Pending technical validation.
