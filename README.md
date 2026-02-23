# Kong Configuration Backup (decK + AWX)

This repository automates Kong configuration backups using:

- Kong decK
- AWX Automation
- GitHub for version control

## Folder Structure

- playbooks/ → AWX automation logic
- deck_backups/ → Stored backup YAML files
- docs/ → Documentation

## How It Works

1. AWX runs playbook
2. decK exports configuration
3. Backup stored in Git
4. Versioned for tracking

## Supported Backup Modes

- Full configuration
- Workspace-specific configuration

## Restore

Use:

