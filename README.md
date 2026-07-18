# Roblox Version

Monitoring and tracking Roblox client versions across different platforms and channels.

## Data Sources

This project fetches version information from the following Roblox API endpoints:

### Deploy History
- [Windows Deploy History](https://setup.rbxcdn.com/DeployHistory.txt)
- [Mac Deploy History](https://setup.rbxcdn.com/Mac/DeployHistory.txt)

### Client Versions - LIVE Channel
- [Windows Player (LIVE)](https://clientsettings.roblox.com/v2/client-version/WindowsPlayer/channel/LIVE)
- [Windows Studio 64 (LIVE)](https://clientsettings.roblox.com/v2/client-version/WindowsStudio64/channel/LIVE)
- [Mac Player (LIVE)](https://clientsettings.roblox.com/v2/client-version/MacPlayer/channel/LIVE)
- [Mac Studio (LIVE)](https://clientsettings.roblox.com/v2/client-version/MacStudio/channel/LIVE)

### Client Versions - ZBETA Channel
- [Windows Player (ZBETA)](https://clientsettings.roblox.com/v2/client-version/WindowsPlayer/channel/zbeta)
- [Windows Studio 64 (ZBETA)](https://clientsettings.roblox.com/v2/client-version/WindowsStudio64/channel/zbeta)
- [Mac Player (ZBETA)](https://clientsettings.roblox.com/v2/client-version/MacPlayer/channel/zbeta)
- [Mac Studio (ZBETA)](https://clientsettings.roblox.com/v2/client-version/MacStudio/channel/zbeta)

## Purpose

Track and monitor Roblox version releases and updates across multiple platforms (Windows, Mac) and channels:

- **LIVE Channel**: Current stable release versions for all users
- **ZBETA Channel**: Testing and future versions, used to track upcoming releases before they go to production

## About ZBETA

ZBETA is Roblox's beta/testing channel where new features and versions are tested before being released to the LIVE channel. Monitoring ZBETA helps track future version releases and upcoming changes.

## License

This project is for tracking and informational purposes.
