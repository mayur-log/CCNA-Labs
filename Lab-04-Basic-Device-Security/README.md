# Day 04 - Basic Device Security

## Objective
Configure basic security settings on a Cisco router to prevent unauthorized access.

## Topics Covered
- Configure Enable Secret Password
- Configure Console Password
- Configure VTY Password
- Enable Password Encryption
- Configure MOTD Banner
- Save Configuration
- Verify Configuration

## CLI Commands Used
```bash
enable
configure terminal
hostname R1
enable secret class
line console 0
password cisco
login
exit
line vty 0 4
password cisco
login
exit
service password-encryption
banner motd # Unauthorized Access Prohibited #
end
copy running-config startup-config
show running-config
show startup-config
```

## Software Used
- Cisco Packet Tracer

## Skills Learned
- Basic router security
- Password protection
- Configuration verification
- Saving router configuration
