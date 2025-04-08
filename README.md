<div align="center">

# [DART Threat Intelligence Database](https://thedartproject.github.io/)

![DART Project Logo](https://github.com/TheDARTProject/.github/blob/main/SCREENSHOTS/The-DART-Project.png)

Primary repository for storing and managing threat intelligence data.

</div>

## Data Structure
- `Main-Database/`: Current production dataset
  - `Compromised-Discord-Accounts.json`
  - `Active-Discord-Servers.json`
- `Backup-Database/`: Historical backups
- `Edit-Database/`: Staging area for changes
- `Excel-Import-Export/`: Templates for data transfer

## Schema Documentation
All JSON files follow standardized schemas documented in our [Data Dictionary](https://thedartproject.github.io/info).

## Data Management
1. Make changes in `Edit-Database/`
2. Validate with Database Tools
3. Submit pull request for review
4. Approved changes are merged to `Main-Database/`

⚠️ **Warning**: Never edit `Main-Database/` directly.

<div align="center">

## [Support my work on Ko-Fi](https://ko-fi.com/thatsinewave)

## [Join my Discord server](https://discord.gg/2nHHHBWNDw)

</div>
