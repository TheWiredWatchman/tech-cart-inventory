# Tech Cart Inventory 🔧

**Stop hunting. Start finding.**

---

## The Problem

You're on a call. Machine's down. Production's breathing down your neck.

You need that one RS232 cable — the Omron CQM1 interface — and you *know* it's on one of the carts. But which one? First shift's cart? Second? Is it even plugged into the right laptop?

So you walk. You dig. You check three carts, four toolboxes, and ask two guys who aren't sure either.

**15 minutes gone.** On a cable hunt.

Now multiply that by every call, every shift, every technician on the floor.

---

## The Solution

One HTML file. No install. No server. No IT ticket.

Double-click and you've got:

- ✅ **Every cable** on every cart, with slot positions
- ✅ **Laptop specs** — RAM, storage, OS, network config
- ✅ **Software versions** — which machine has GX Works3? KV Studio 12? Sysmac?
- ✅ **Instant search** — type "RS232" and see every match across all carts
- ✅ **Works offline** — no network required

**Built by a maintenance technician. For maintenance technicians.**

---

## Quick Start

1. Download `index.html`
2. Double-click to open
3. That's it. You're done.

Want it on every cart? Copy the file to each laptop's desktop. Create a shortcut. Boom — every tech has instant access.

---

## What's Inside

| Feature | Description |
|---------|-------------|
| **Multi-Cart Tracking** | Switch between shifts/stations with one click |
| **Cable Inventory** | Full list with descriptions and slot positions |
| **Laptop Specs** | Hardware, storage, network — all the details |
| **Software Versions** | Know exactly what's installed where |
| **Live Search** | Find anything across all categories instantly |
| **Stats Dashboard** | Cable count, software packages, storage % at a glance |

---

## Customizing For Your Shop

Everything lives in one JavaScript object called `shiftData`. Open the HTML file in any text editor and scroll to the data section.

```javascript
const shiftData = {
    '1st': {
        name: 'Your Cart Name',
        laptop: 'Laptop ID',
        cables: [
            'Your Cable 1',
            'Your Cable 2',
            // Add more...
        ],
        specs: {
            manufacturer: 'LENOVO',
            model: 'Your Model',
            processor: 'Your CPU',
            ram: '16 GB',
            // etc...
        },
        software: {
            'Category Name': [
                'Software 1 (v1.0)',
                'Software 2 (v2.0)',
            ],
            // Add more categories...
        }
    },
    // Add more carts/shifts...
};
```

No programming experience needed. Just edit the text between the quotes.

---

## Why I Built This

I got tired of the cable hunt.

I got tired of asking "which laptop has the KEYENCE software?" and getting three different answers.

I got tired of watching minutes turn into hours across a year of inefficiency.

So I built a tool. With AI assistance. In a single afternoon.

**That's the point of The Wired Watchman** — we don't have to wait for someone else to solve our problems. We have the tools now. We just have to use them.

---

## The Hidden Stuff 🎮

Yeah, there are Easter eggs. Because why not?

I'm not telling you what they are. But if you're old enough to remember the Konami Code... you might find something.

---

## Tech Stack

- **HTML/CSS/JavaScript** — Single file, no dependencies
- **No frameworks** — Just vanilla code that works
- **No backend** — Runs entirely in your browser
- **No install** — Download and go

---

## ROI

Let's do the math:

| Before | After |
|--------|-------|
| 5-10 min searching per call | 30 seconds |
| "I think it's on Cart B?" | Exact location, instant |
| "Does anyone have GX Works3?" | Search → answer |

**Conservative estimate:** 20 minutes saved per day across shifts = **120+ hours per year**

Cost of this tool: **$0**

---

## License

MIT — Do whatever you want with it. Fork it. Modify it. Make it yours.

If you build something cool, I'd love to see it.

---

## Connect

**The Wired Watchman**

I'm a maintenance technician with 28 years in industrial automation. I build tools that solve real problems on the production floor.

- 🔗 [GitHub](https://github.com/TheWiredWatchman)
- 🎥 [YouTube](https://youtube.com/@TheWiredWatchman)
- 💼 [LinkedIn](https://linkedin.com/in/TheWiredWatchman)

---

*The future isn't coming — it's already here. We just have to build it ourselves.*
