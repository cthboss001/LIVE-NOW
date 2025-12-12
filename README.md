# Live Task Dashboard

A focused task management system designed for people drowning in endless to-do lists. When you have 100+ tasks screaming for attention, this dashboard forces you to breathe and focus on one thing at a time.

## Philosophy

**One task. Maximum attention. No distractions.**

Stop context-switching between 50 open tabs and scattered sticky notes. This dashboard takes your entire workload and puts exactly ONE task in your face at a time. Complete it. Move on. Repeat.

## Features

- **75% screen dedicated to current task** - Impossible to ignore, impossible to forget
- **Breathing visual effects** - Pulsing red accents remind you this task is LIVE
- **Handles 1000+ tasks** - Throw everything at it, but you'll only see one at a time
- **Persistent local storage** - Your tasks survive browser restarts
- **Zero backend complexity** - Pure client-side, no servers, no databases
- **Instant task completion** - One click moves task to completed sidebar
- **Queue management** - Click any pending task to make it current

## Why This Exists

If you're like most people, you have:
- 47 browser tabs open
- 3 different to-do apps
- Sticky notes everywhere
- A notebook with crossed-out tasks
- Constant anxiety about what you're forgetting

This dashboard says: **Stop. Focus on THIS. Right now. Nothing else matters.**

## Demo

🔗 **[Live Demo](https://yourusername.github.io/task-dashboard)**

## Installation

### Option 1: Use GitHub Pages (Recommended)
1. Fork this repository
2. Go to Settings → Pages
3. Enable Pages from `main` branch
4. Access at `https://yourusername.github.io/task-dashboard`

### Option 2: Run Locally
1. Download `index.html`
2. Open in any modern browser
3. That's it. No build process, no dependencies.

## Usage

1. **Add all your tasks** - Dump everything that's stressing you out
2. **First task auto-selected** - It's now LIVE and demanding your attention
3. **Work until done** - Focus on this one thing
4. **Click "COMPLETE TASK"** - Task goes green in sidebar
5. **Next task auto-loads** - Keep the momentum
6. **Repeat** - Watch your completed list grow

**Keyboard Shortcuts:**
- `Ctrl + Enter` while typing - Add new task

## Data Storage

All tasks are stored in your browser's `localStorage`. This means:
- ✅ Data persists across sessions
- ✅ Works completely offline
- ✅ No account required
- ✅ Private by default
- ⚠️ Data tied to browser/device
- ⚠️ Clearing browser data = losing tasks

## Technical Stack

- Pure HTML/CSS/JavaScript
- React 18 (via CDN)
- Tailwind CSS (via CDN)
- localStorage API
- Zero build process
- Zero dependencies to manage

## Browser Support

Works in any modern browser:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

## Contributing

This is intentionally simple. If you want to add features, remember the core principle: **one task at a time, maximum focus**.

Pull requests welcome for:
- Performance improvements
- Bug fixes
- Visual polish
- Accessibility enhancements

Please don't PR:
- Backend integration (defeats the purpose)
- Complicated project management features (wrong tool)
- Anything that breaks the single-task focus

## License

MIT - Do whatever you want with it

## Philosophy Deep Dive

**Why one task at a time?**

Research shows human brains are terrible at multitasking. Every context switch costs you 15-20 minutes of productivity. When you have 100 tasks visible, your brain tries to process all 100 simultaneously. Result? Paralysis.

This dashboard removes the decision fatigue. You don't choose what to work on. The dashboard chooses for you. Your job is simple: complete the task in front of you.

**Why the aggressive visual design?**

The breathing effects, pulsing red accents, and massive text aren't just aesthetics. They're psychological triggers. Your brain can't ignore something that's pulsing and glowing. It demands attention at a primal level.

**Why localStorage instead of a database?**

Because adding a backend means:
- Sign-up friction
- Privacy concerns  
- Server maintenance
- Sync conflicts
- Complexity

This tool should work instantly, forever, with zero maintenance. localStorage achieves that.

---

**Made for people who have too much to do and not enough time to do it.**

Stop managing tasks. Start completing them.
