# Isolated Virtual Lab Setup

## Objective

I built a controlled virtual environment for cybersecurity practice using a separate attacker machine and target machine. Keeping them separate makes it possible to practise safely without testing against unrelated systems.

## Environment and tools

- Virtualisation platform: UTM
- Attacker VM: Kali Linux
- Target VM: Metasploitable 2
- Recovery points: fresh-install snapshots for both VMs

## Method

1. Set up the Kali Linux and Metasploitable 2 virtual machines separately.
2. Started each VM and confirmed that it reached its desktop or login screen.
3. Created a fresh-install snapshot for each VM.
4. Kept the snapshots as restore points for later lab exercises.

## Results

Both virtual machines started, and each had a fresh-install snapshot available. This provided a recoverable environment for the network discovery and scanning exercise in Lab 2.

## Evidence

- Kali Linux VM running
- Metasploitable 2 VM running
- Fresh-install snapshots for both VMs

## What I would improve

Before each exercise, I would record the VM settings and verify the network isolation. I would also keep a short checklist for restoring each VM to its clean snapshot.
