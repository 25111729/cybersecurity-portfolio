# Host Discovery and Service Enumeration

## Objective

I used an isolated virtual lab to identify live hosts and inventory services running on the target VM. The exercise focused on authorized reconnaissance and service discovery.

## Environment and tools

- Virtualisation platform: UTM
- Attacker VM: Kali Linux
- Target VM: Metasploitable 2
- Network: host-only
- Tools: ping and Nmap

## Method

1. Confirmed that the VMs were connected through the host-only lab network.
2. Used ping to check connectivity to the target.
3. Used `nmap -sn` to identify live hosts in the lab.
4. Used `nmap -sV` to identify services and reported versions on the target.
5. Recorded the findings and considered defensive steps.

## Results

The lab identified two live hosts: Kali Linux and Metasploitable 2. The findings table recorded these examples:

| Port | Service | Reported version |
|---|---|---|
| 21/tcp | FTP | vsftpd 2.3.4 |
| 22/tcp | SSH | OpenSSH 4.7p1 |

## Risk notes

- **FTP:** Confirm whether FTP is required. If it is not, disable it; otherwise restrict access and use a secure alternative for transferring credentials or files.
- **SSH:** Verify that the server version is supported and updated. Restrict management access to authorized hosts and use secure authentication settings.

## Evidence

- Ping connectivity result
- Nmap host-discovery result
- Nmap service/version scan
- Findings table and risk notes

## What I would improve

I would make the findings table cover every service I chose to assess, with a supporting scan result and a mitigation note for each. I would also keep the scan scope limited to the isolated lab network.
