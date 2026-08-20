# MK-CORP Support Lab

Hands-on enterprise IT support and application support lab designed to simulate a small company infrastructure.

The project focuses on practical administration, troubleshooting, SQL, Active Directory, networking, PowerShell and Microsoft enterprise technologies.

## Project Goals

- Build and administer a Windows domain environment
- Practice Active Directory, DNS and Group Policy
- Troubleshoot realistic IT support incidents
- Build and query a PostgreSQL database
- Practice SQL in application-support scenarios
- Automate administrative tasks with PowerShell
- Document incidents and technical solutions
- Develop practical skills for Junior IT / Application Support roles

## Planned Infrastructure

| System | Role | Operating System |
|---|---|---|
| DC01 | Domain Controller / DNS | Windows Server 2025 |
| CLIENT01 | Employee workstation | Windows 11 Enterprise |
| DB01 | PostgreSQL database server | Linux |

Planned Active Directory domain:

`mkcorp.test`

## Technologies

- KVM / QEMU
- libvirt
- Windows Server 2025
- Windows 11
- Active Directory Domain Services
- DNS
- Group Policy
- PowerShell
- Linux
- PostgreSQL
- SQL
- Git / GitHub
````markdown
````text
## Repository Structure

```text
docs/          Infrastructure documentation
powershell/    PowerShell scripts
screenshots/   Lab screenshots
sql/           SQL exercises and troubleshooting
tickets/       Simulated IT support incidents
