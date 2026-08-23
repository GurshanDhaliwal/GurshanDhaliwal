# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [Unreleased]
### Fixed
- Replaced broken/deprecated badge sources in the GitHub Stats section:
  - `github-readme-stats.vercel.app` → `github-stats-extended.vercel.app` (maintained fork; original project deprecated and returning 503 `DEPLOYMENT_PAUSED`).
  - `github-profile-trophy.vercel.app` → community load-balancing mirror (`trophygithubreadmelang.cybee.dpdns.org`) after the official instance started returning 402 "deployment paused" errors.

### Removed
- GitHub Trophies section (disabled, then removed entirely).
- GitHub Stats and Top Languages badges, keeping only the GitHub Streak badge.
- "📈 Contribution Graph" section.
- Closing "Thanks for stopping by!" footer note.
- "✏️ Update the descriptions above..." reminder note under Featured Projects.

## [1.0.0] - 2026-08-23
### Added
- Initial GitHub profile README (`github-profile.md`) with intro, skills, GitHub stats, streak, and trophy sections.
- Repository initialized and pushed to GitHub.
