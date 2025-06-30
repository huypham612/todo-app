# Focus7 - Minimal TODO App

A minimal PWA with a 7-task limit and Pomodoro timer, seamlessly integrates with [Clarity7](https://claude.ai/public/artifacts/83db0d97-97df-4c9f-ac28-d627c6001898), an AI-powered priority finder, to transform decision paralysis into focused action using AI and cognitive science.

## Why 7 Tasks?

Research-backed limit based on Miller's Rule - people can effectively focus on 7±2 items. This forces prioritization and prevents overwhelm, leading to higher completion rates.

## Install

Visit the URL → "Add to Home Screen" or "Install App"
📱 https://huypham612.github.io/todo-app/ 

## Features

- **7-Task Limit**: Research-backed focus
- **Clarity7 Import**: Paste AI-prioritized tasks directly
- **Pomodoro Timer**: 25-minute focus sessions
- **PWA**: Install as native app
- **Offline**: Works without internet
- **Auto-cleanup**: Tasks expire after 1 day

## Clarity7 Integration

Focus7 works seamlessly with [Clarity7](https://claude.ai/public/artifacts/83db0d97-97df-4c9f-ac28-d627c6001898) - an AI-powered priority finder:

1. **Clarify**: Use Clarity7 to find your essential priorities from overwhelming task lists
2. **Export**: Copy the AI-generated task list from Clarity7
3. **Import**: Paste directly into Focus7's task input box
4. **Execute**: Focus on your 7 most important tasks

## Deployment
```bash
# Update version in sw.js to force update
sed -i '' "s/const VERSION = '[^']*'/const VERSION = '1.0.2'/" sw.js

# Push to main branch
git add . && git commit -m "update" && git push

# GitHub Pages auto-deploys
# PWAs auto-update on next visit
```
