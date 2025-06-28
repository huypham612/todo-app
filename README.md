# Focus7 - Minimal TODO App

Minimal PWA with 7-task limit + Pomodoro timer for maximum focus.

## Install

Visit the URL → "Add to Home Screen" or "Install App"
📱 https://huypham612.github.io/todo-app/ 

## Features

- **7-Task Limit**: Research-backed focus
- **Pomodoro Timer**: 25-minute focus sessions
- **PWA**: Install as native app
- **Offline**: Works without internet
- **Auto-cleanup**: Tasks expire after 3 days

## Why 7 Tasks?

Research-backed limit based on Miller's Rule - people can effectively focus on 7±2 items. This forces prioritization and prevents overwhelm, leading to higher completion rates.

## Deployment
```bash
# Update version in sw.js
sed -i '' 's/focus7-v[0-9]*/focus7-v3/' sw.js

# Push to main branch
git add . && git commit -m "update" && git push

# GitHub Pages auto-deploys
# PWAs auto-update on next visit
```