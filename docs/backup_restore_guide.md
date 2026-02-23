# Kong Configuration Backup & Restore Guide

## Overview
This project automates Kong configuration backups using decK and AWX.

## Backup Types

### Full Backup
Exports entire Kong configuration.

### Specific Workspace Backup
Exports only selected workspace configuration.

## Required Survey Variables

- backup_type (full / specific)
- workspace_name (required if specific)
- github_token (for Git push)

## Restore Process

To restore:

