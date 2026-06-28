# Tier C Demo Sandbox

This folder is the safe target for the AIOS Cert C7 Tier C ScheduledRun demo.

## What lives here
- `heartbeat.txt` - one line per ScheduledRun fire (timestamp + a short marker). Empty on creation.

## Purpose
Used to demo:
1. A ScheduledRun (remote cron agent) exists.
2. Firing one run live appends a visible line to `heartbeat.txt`.
3. The kill-switch (delete the routine) removes it cleanly.

## Safety
Synthetic and disposable. No customer data, no production system. The whole folder can be deleted after the demo.
