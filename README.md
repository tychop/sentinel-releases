# Sentinel Releases

Public releases for [Sentinel](https://github.com/tychop/Sentinel) - a macOS app for monitoring GitHub repositories, workflow runs, and pull requests.

## Installation

### Via Homebrew

```bash
brew tap tychop/sentinel
brew install sentinel-app
```

### Manual Download

1. Go to [Releases](https://github.com/tychop/sentinel-releases/releases)
2. Download the latest `Sentinel-XX.dmg`
3. Open the DMG and drag `Sentinel.app` to `/Applications/`

## Requirements

- macOS 15.0+ (Sequoia/Tahoe)
- GitHub CLI (`gh`) installed and authenticated

## First Launch

Since the app uses ad-hoc signing, macOS will show a security warning on first launch:

1. **Option A**: Right-click the app and select "Open"
2. **Option B**: Go to System Settings > Privacy & Security > Security and click "Open Anyway"

This only needs to be done once.

## About Sentinel

Sentinel helps you:
- Monitor local GitHub repositories
- Track GitHub Actions workflow runs
- View pull requests requiring your attention
- Open repositories in Terminal, Finder, or Fork
- Access GitHub Actions and CI/CD status quickly
- View Home screen widgets

## License

MIT
