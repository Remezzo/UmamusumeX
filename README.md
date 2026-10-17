<div align="center">

<img src="icarus.png" alt="Icarus" width="120" />

# UmamusumeX

### The whole game, on your own machine. Every rule is yours to change.

**UmamusumeX is a complete private server for Umamusume: Pretty Derby on Steam (Global), with a control panel that lets you reshape almost anything the official game decides for you.** Careers in all four scenarios, a real race engine, gacha, Team Trials, Champions Meeting, Legend Races, clubs and friends. The real, unmodified game client plays against a server that lives on your PC, keeps your saves on your disk, and answers to you. One file to download, one button to play, one button to go back.

[![Download](https://img.shields.io/badge/Download-UmamusumeX.exe-D4A017?style=for-the-badge)](https://github.com/Remezzo/UmamusumeX/releases/latest)
&nbsp;
[![Discord](https://img.shields.io/badge/Discord-Join_the_Icarus_hub-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/wpbd3hTBDc)

![Platform](https://img.shields.io/badge/platform-Windows_%2B_Linux_(Proton)-0078D6)
![Version](https://img.shields.io/badge/release-1.0.0-D4A017)
![Engine](https://img.shields.io/badge/engine-native_Rust-1f7a4d)
![Updates](https://img.shields.io/badge/updates-checksum_verified-1f7a4d)
![License](https://img.shields.io/badge/license-Proprietary-c02626)

*by Remezzo and Maple* &nbsp;·&nbsp; part of Icarus

</div>

---

> **Download `UmamusumeX.exe` → double-click → press Play.** It finds your game, sets itself up, starts the server, launches Steam and opens its control panel. If anything goes wrong, one button puts the game back on the official servers. You can't get stranded.

**UmamusumeX is yours to control.** The official game decides what you pull, how a career rolls, when an event runs and what a race gives you. Here you decide. Everything the panel can change says what it does and when it takes effect, and anything that can break a save takes a backup first.

---

## Contents

[At a glance](#at-a-glance) · [Why a private server](#why-a-private-server) · [Getting started](#getting-started) · [Never stranded](#never-stranded-the-way-back-to-official) · [The game](#the-game) · [Careers](#careers) · [The control panel](#the-control-panel) · [Running careers](#running-careers-the-admin-page) · [Career tuning](#career-tuning-a-slider-for-the-rules-of-the-game) · [Gift Shop](#the-gift-shop) · [Accounts](#accounts) · [Banners and events](#banners-and-events) · [Sync](#sync-play-any-day-of-the-game) · [Mods](#mods) · [Settings](#settings) · [Logs](#logs-and-bug-reports) · [Saves](#your-saves) · [Playing with friends](#playing-with-friends) · [Security](#built-to-be-trusted) · [Updates and removal](#updates-and-removal) · [Linux](#linux) · [Troubleshooting](#troubleshooting) · [FAQ](#faq)

---

## At a glance

| You want to… | UmamusumeX… |
|---|---|
| **Start playing in minutes** | Finds the game on its own, builds a certificate on your PC, points the game at itself and launches Steam. One checklist, one administrator prompt, one Play button. |
| **Play every scenario** | URA Finale, Unity Cup, Trackblazer and Grand Live, start to finish, with the game's own training formula, events, goals, skills, inheritance and finish screen. |
| **Change the rules** | Thirteen career sliders centred on "Normal": stat gains, failure rate, friendship speed, hint chance, energy use, spark strength, luck, rival strength and more. Pin exact numbers when you need them. |
| **Fix or edit anything** | Edit stats, aptitudes, skills, conditions, mood, energy, fans, turn, veterans and cards on any account, while the game is running. Every edit takes a backup first. |
| **Spoil yourself** | A Gift Shop for carats, monies, characters, support cards, tickets and refills, plus a downgrade tool for taking cards back down. |
| **Play any day of the game** | Sync replays any past date: its events, its Scout banners, its home theme. Compare official with your server side by side. |
| **Run events your way** | Start, end, reschedule, extend or restore any event, run your own banners and Legend Races, and give event points and Prize Coins. |
| **Try wild game modes** | Optional mods: an Archipelago multiworld, a permadeath casino run, a Twitch chat that joins your races, a randomizer, Dream's Luck and bigger race fields. |
| **Play with friends** | LAN mode lets everyone on your network join, each with their own account, clubs and follows. |
| **Never lose your way back** | A desktop shortcut, a logon prompt and a close-the-window safety net all return the game to the official servers. |
| **Stay safe** | Local-only by default, per-account keys, hashed passwords, a certificate valid for the game's two servers only, and backups of everything you can edit. |

---

## Why a private server

Umamusume is a game about long-term planning, and the official client gives you very little room to explore it. Banners rotate, events expire, a career takes an hour of tapping, and a bad roll costs you a day.

UmamusumeX moves the server onto your own machine and hands you the controls:

- **Practice without pressure.** Test a build against a stat curve, retry a bad event, or set the failure rate to Never and see how far a strategy goes.
- **Never miss anything.** Every banner and event the game's data contains can be run again, today, in any order.
- **Share a world.** Friends join the same server, race each other's trainees and fill the same club chat.
- **Keep it.** Your accounts, careers and rosters live in a local database. Back it up, move it, restore it.
- **Make your own game.** Add your own Scout banners and Legend Races, randomise every career, or let a Twitch audience throw traps at you.

The game client stays the real one. It isn't patched, repacked or injected. The only thing that changes is where it connects.

---

## Getting started

> **Windows 10 or 11, and the Steam version of Umamusume: Pretty Derby, launched at least once.** That's the whole requirements list.

1. **Download `UmamusumeX.exe`** and put it in a folder of its own.
2. **Double-click it.** A small window opens (keep it open while you play) and the control panel opens in your browser.
3. **Press "Get started" on the Home page.** UmamusumeX finds your game, then builds a certificate on your PC. Windows asks you to confirm it: answer **Yes**. Tick the box if you'd like a *Back to official servers* shortcut on your desktop.
4. **Press Play.** Windows asks once for administrator permission. The server starts, Steam launches the game, and an already-open game is restarted for you.
5. **Create an account when the game asks.** It's created on your server, and nowhere else.

That's it. On later days, double-click and press Play.

**The checklist** on Home shows everything UmamusumeX needs: the game data found, the certificate trusted, the redirect on, the game's port free, the race engine ready and the data folder writable. Every red line says what's wrong in plain words and has a **Fix** button. If something else is using the port, the panel names the program.

**The Start, Play, Restart and Stop buttons act on the game itself**, not only on the server: Play launches it (restarting it when it's already running), Restart relaunches it, Stop closes it.

---

## Never stranded: the way back to official

A private server is only comfortable if the exit is easy. UmamusumeX has five of them, and any one is enough.

- **Return to official servers** in the panel. Stops the server, turns the redirect off and, if you like, closes the game.
- **The desktop shortcut.** *UmamusumeX - Back to official servers* works even when UmamusumeX isn't running, with one administrator prompt.
- **Closing UmamusumeX.** Quit asks whether to return to official servers, and Yes is the default. Closing the console window does it too, and the server can't outlive the program that started it.
- **The logon prompt.** If your PC restarts while the redirect is on, Windows asks at sign-in whether to put the game back on the official servers. One click.
- **Uninstall.** The About page removes the redirect, the certificate, the shortcut, the startup entry and the program itself. You choose whether your saves go too.

The redirect is a single marked block in the Windows hosts file. UmamusumeX backs the file up, writes it, reads it back to confirm, and only ever removes its own lines.

---

## The game

UmamusumeX re-creates the game's server endpoint by endpoint: **more than 350 of them**, each built against what the real client does.

| | |
|---|---|
| **Careers** | All four scenarios (URA Finale, Unity Cup, Trackblazer, Grand Live) with the game's own training formula, support-card bonding, events, goals, inheritance, skills and the finish screen. |
| **Races** | A compiled race engine simulates every race: positions, pace, stamina, skills and overtakes. The client replays it as it would a real race, and the same seed gives the same race. |
| **Gacha** | Banners, rates, guarantees, tickets, sparks and duplicates from the game's own data, plus banners you add or hide. |
| **Team Trials** | Opponents drawn from a pool of characters (never the same character twice on one team), classes, promotions and rewards, with a setting for how often a win drops a gift box. |
| **Champions Meeting** | Rooms, leagues, rounds and results, with one-click jumps between phases for any account. |
| **Legend Races and daily races** | Legend Races by name, a rival ladder, daily races and practice lobbies, with the race field sized to the course. |
| **Accounts and social** | Sign-up, Data Link, profiles, honours, friends, follows and full clubs: chat, item requests, donations and rankings. |
| **Progress** | Missions, the main story, character and event stories, login bonuses, the present box and the shop. |
| **Media** | The jukebox, live theatre, concerts, galleries and the note archive. |
| **Every race unlocked** | Every race's trophy is reported from the start, so no race is locked to "view only" and View Results is open from day one. |

Existing saves always load. Every account is stored in a local database with automatic backups.

---

## Careers

Every scenario plays the way the game plays it: its own goals, its own training screen, its own events, with the real numbers behind them.

- **Training** is computed with the game's formula: facility level, support-card bonds, friendship and rainbow training, mood, energy, failure rate and the way each scenario shifts it.
- **Events** come from the game's full event database, with the real choices and their real outcomes.
- **Goals and races** are enforced the way the game enforces them, including goal races, class progression and the final.
- **Skills** use the game's own hint system, costs and discounts, and Fast Learner really does make them cheaper.
- **Inheritance** works end to end: parents, factors, sparks, compatibility, and the veteran you get at the finish.
- **Independent (idle) training** runs for as long as you set it. Choose between a realistic AI that plays a normal career turn by turn and lands where a casual player would, an instant maxed run for testing, or off.
- **Pal outings, Unity Cup teams, Grand Live songs and Trackblazer's shop** all play out through their own scenario logic.

---

## The control panel

Double-click UmamusumeX and the whole thing opens in your browser. No command line, ever. It has seven pages, a status rail and a quick-search box.

| Page | What it's for |
|---|---|
| **Home** | The first-run checklist, Play, game and server status, live activity, and every account on the server. |
| **Admin** | Running careers (stats, aptitudes, skills, conditions, turn, rules and cheats) and the Gift Shop. |
| **Mods** | Optional game modes, each with its own page. |
| **Banners and events** | What Scout shows, when events run, and your own banners and Legend Races. |
| **Sync** | Play any past day, compare official with your server, see what's coming. |
| **Settings** | Accounts and security, the launcher, backups, diagnostics and every server setting. |
| **Logs** | A live, redacted record of what the game asked for and how the server answered. |

**The status rail** on the right shows the server's state, the players connected, a plain-language line about what's going on right now ("Haru Urara is on turn 22", not an endpoint name), and a **Needs attention** list. When a change needs the game to go back to its title screen or restart, Needs attention says so and clears itself once it has happened.

**The account chip** in the top bar shows who's playing, with their carats. Click it for monies, TP, RP, cards and the present box. Gift Shop always acts on this account.

**Export log** sits in the top bar, so a bug report is one click.

**Ctrl+K** opens a search over every page, setting and account.

**Help** is built in, page by page, with a Problems section for when something goes wrong.

Everything is built to read well at any width, and nothing in the panel displays your Windows user name or the path to your files.

---

## Running careers: the Admin page

Admin edits careers while the game is running. Every edit takes a backup first, and each one tells you when it shows in the game.

**The trainee**

- **Tiles** for energy, mood, skill points, fans and class. Click one and change it.
- **Stats** shows each stat against its cap. Set a stat, or its cap.
- **Aptitudes** set the track (turf, dirt), distance (sprint, mile, medium, long) and running style (front, pace, late, end) grades, G through S.
- **Skills** adds, levels and removes skills. Search by name.
- **Conditions** gives or clears Fast Learner, Charming, Hot Topic, Practice Perfect, Shining Brightly and the bad ones too. Hover a name for what it does; Practice Perfect and Practice Poor change the failure rate.
- **Turn** moves the career forward or back, with options for the races and events in between.

**Maintenance**

| Tile | What it does |
|---|---|
| **Fix the career screen** | Rebuilds this turn's goals, races and training buttons if they look wrong. Stats and progress stay. |
| **Unlock this turn's buttons** | Turns on every greyed-out button on the training screen until the next turn. |
| **Clear stuck events** | If the game freezes or loads forever on an event, throws away waiting events and half-finished races. Shows how many are stuck right now. |
| **Replay story events** | Marks events from a turn onwards as unseen so they play again. |
| **Max out this career** | Maxes stats and skill points and teaches every skill. Finish the career in the game to keep the trainee. |
| **Put the career aside** | Saves the running career under a name and clears it, so you can start another. Resume it later. |
| **Parked careers and raw edits** | Your parked careers, and an advanced editor for any value in the career's data. |

**How changes apply** lists, at a glance, which edits show from the next turn and which need the title screen.

**Rules and cheats** open the settings that govern careers: tuning, stamina, idle training and the roster. A **TESTING ON** badge shows whenever a cheat is active.

---

## Career tuning: a slider for the rules of the game

Career tuning changes how the game plays without changing what's in it. Each slider is centred on **Normal**, the official game's behaviour. Move left for less, right for more, and press **Back to Normal** to undo.

| Slider | Moves |
|---|---|
| **Training gain** | Stat gains from training. |
| **Failure rate** | From **Never** through Normal to **Always**. It works even when the official chance would be zero. |
| **Friendship gain** | How fast support-card bonds fill. |
| **Hint chance** | How often a training turn hands out skill hints. |
| **Skill points** | Skill points earned. |
| **Fan gain** | Fans earned. |
| **Energy use** | How much energy training costs. |
| **Spark strength** | The strength of inheritance sparks. |
| **Luck** | How the game's random rolls fall. |
| **Rival strength** | How tough race opponents are. |
| **Event rate** | How often events trigger. |
| **Condition procs** | How often conditions appear. |
| **Race fatigue** | How much a race drains you. |

The training screen shows the changed numbers, so what you see is what you get.

**Exact pins** are for tests. Pin a stat gain or a failure rate to a fixed number, and choose which stats the pin applies to; the others keep the real formula. Leave every stat unticked and the pin applies to all of them.

Every setting in the panel states when it takes effect: right away, next turn, next career, after a return to the title screen, or after a game restart. The panel won't tell you to restart the game for something that doesn't need it.

---

## The Gift Shop

Gifts always go to the account in the game right now.

- **Quick gifts.** Carats, monies, a TP and RP refill, or every character and card at once.
- **Cards and roster.** Max your support cards, trainee cards and veterans, reset today's dailies, or add a friend to lend.
- **The basket.** Pick characters, cards and items, then send them all together.
- **Downgrade.** Take trainee cards back down in stars and talent, or support cards in limit break and level. Cards never go below their starting stars. A backup is taken first.

Gifts arrive in the game's present box. Open it and tap **Collect All**. Whole-collection gifts skip the box; go back to the title screen to see them.

---

## Accounts

Every account on your server shows up on Home with its own page. The panel can:

- Show and change currencies, items, cards and the present box.
- Give items and carats, and send mail.
- Edit **veterans** one at a time: stats, aptitudes, fans, max one out, and export or import a veteran as a file you can hand to a friend.
- Edit a **veteran roster** of up to hundreds of trainees, with a size limit you set.
- Reset an account's Data Link password.
- Delete an account, behind a typed confirmation.

To make another account, start the game with the redirect on and follow its sign-up. To switch accounts, use the game's own Data Link with the other account's trainer ID and password.

Edits made in the panel take the same per-account lock the game uses, so they never clash with someone playing.

---

## Banners and events

**Scout.** Choose which banners the game shows: the current ones plus any you add, or every banner except the ones you hide. Switch single banners on or off, move their dates, or let an old banner run again.

**Race events and game events.** Every event in the game's data can be controlled:

- **Start now** and **End now** run or end an event immediately. Past events can run again.
- **One at a time.** Starting a Champions Meeting, a Legend Race or a story event puts the others of that kind back on their own dates, so exactly one is live.
- **Jump a round** in a Champions Meeting with one click.
- **Event points and Prize Coins.** Starting a story event can also give an account its points and roulette spins.
- **The ⋯ menu** reschedules a whole event, extends only its end, or restores its original dates.
- **With the game open**, a change waits and applies the moment the game releases its data, and the dialog can restart the game for you. The newest change wins.

**Custom.** Build your own Scout banners and Legend Races on top of the existing ones. Legend Races are shown by their names everywhere in the panel.

Restart the game to see a date change.

---

## Sync: play any day of the game

- **Game date.** Pick any past day and the game follows it: events, Scout banners and the home theme. Your progress stays. *Play this day* changes the date; *Play this day and restart* also relaunches the game so you see it straight away.
- **Official versus your server.** Shows what's running on the official game right now beside what's running here, with a marker on every difference.
- **Match official.** Undoes every date change and banner switch you've made.
- **Coming to Global.** Upcoming events and banners, with the ones already in your game files ready to start now.

New events arrive with official game updates: the server tells the game when newer data exists, and the game downloads it by itself. If an event still isn't there, play once on the official servers so the game updates its files.

---

## Mods

Mods are optional, off until you switch them on, and each one says when it takes effect. They're all built into the server; the game client stays untouched except where noted.

| Mod | What it does |
|---|---|
| **Dream's Luck** | Support cards appear in their own training instead of a random one, so friendship training lines up. You choose how often. |
| **Archipelago** | Plays an Archipelago multiworld seed on a separate save. Scenarios, trainees, cards and buffs arrive as items; G1 wins, scenario finals, rank tiers and Legend Race rivals are the checks. Your normal save is never touched. |
| **Derby Casino** | A permadeath run: a trainee whose career ends early is gone for good. Careers pay Monies, a debt grows until it falls due, and new trainees only come out of a slot machine. Every price and rate is a setting. |
| **Randomizer** | Every new career rerolls the trainee's aptitudes, starting stats and skill hints, and the deck if you like. A seed replays the same roll. |
| **Twitch Derby** | Your stream's chat joins your races: `!join` names your rivals, channel points send traps and boons to your next career, and predictions open on your big races. If Twitch is down, the game plays on. |
| **Big fields** *(experimental)* | A client-side plugin for race fields of more than 18 runners. It's the one mod that touches the game client, it needs a plugin loader, and modifying the client is against the official game's terms. Use it on the private server only. |

Archipelago and Derby Casino can't run together. Turning on Archipelago sets Derby Casino and Dream's Luck aside, and turning it off brings them back.

---

## Settings

The Settings page holds everything that isn't a game rule:

- **Accounts and security.** Account protection, sign-in checks, and whether accounts from the official game are accepted.
- **Launcher.** LAN mode, whether the panel opens when the game connects, notifications, and whether other programs' traffic is passed to the official servers.
- **Backups.** Export every save as one file, import it back with validation, and restore any automatic backup.
- **Diagnostics.** Log level, session recording for bug reports, and the checks.
- **Server settings.** Careers (scenarios offered, TP cost, recovery and refills), Racing (Team Trials RP and gifts), Testing (forced SSR rate, a held-open Legend Race, field size, the server's clock) and one section per mod. Every setting has a plain description and a **Reset to defaults** button.

Settings save as you press Save, and a badge tells you when any testing setting is on.

---

## Logs and bug reports

The Logs page is a live record of what the game asked for and how the server answered, with level filters and friendly wording. Personal details are redacted. Press **Export log** in the top bar and you get a single file ready to send with a bug report.

---

## Your saves

Your accounts, careers, rosters, settings and logs live in a single data folder under your user profile, so replacing the exe with a newer one keeps everything.

- **Automatic backups** before every admin edit.
- **Export and import** of everything as one file.
- **Restore** from any backup in Settings.
- **Separate saves** for Archipelago seeds and Derby Casino runs, so the normal save is never touched.
- **Veteran export and import** as small files you can share.

---

## Playing with friends

Turn on **LAN mode** in Settings › Launcher and devices on your network reach the game server, each with their own account. Friends can join clubs, follow each other and race each other's trainees. The control panel itself is reachable from your PC only, always. Use LAN mode on a network you trust.

---

## Built to be trusted

- **Native-compiled.** The program and its race engine are one Rust binary. The server's data queries and request names are not stored as readable text inside it.
- **Local by default.** The game server answers only your PC unless you switch on LAN mode. The panel answers only your PC, needs a per-session token, and refuses other websites and other hosts.
- **Accounts that can't be taken over.** Every request must carry its account's own key, or come from the device the account belongs to. A trainer ID alone gets nobody in, and Data Link passwords can't be brute-forced.
- **No exploits.** The server is authoritative: prices, counts, ownership, race entries, skill purchases and rewards are checked on every request, and a request resent after a lost response is answered once, never applied twice.
- **Your data stays yours.** Nothing is sent anywhere. Passwords are stored hashed and never logged.
- **A careful certificate.** It's generated on your PC, valid for the game's two servers only, and its signing key is never stored.
- **Careful with your system.** The hosts file is backed up and verified; only UmamusumeX's own processes are ever stopped.
- **Tested end to end.** Thousands of real game requests are replayed against every build and must match byte for byte, alongside attack tests for every exploit that has ever been fixed.

---

## Updates and removal

**Updating.** The panel tells you when a new version is out. Press **Update now** and UmamusumeX downloads it, verifies its checksum, stops the server, swaps itself in and restarts, without turning the redirect off. Nothing installs until you press the button.

**Removing.** The About page has an Uninstall button. It returns the game to the official servers, removes the certificate, the desktop shortcut and the startup entry, and deletes the program. You choose whether to keep your saves.

---

## Linux

The game runs on Linux through Steam's Proton, and so does UmamusumeX. Setup scripts handle the certificate and the redirect for you. Run the setup once, start the server, and launch the game from Steam as usual.

---

## Troubleshooting

| Symptom | What to do |
|---|---|
| **The game can't connect** | Open the panel's checklist. A red line says what's wrong and its Fix button repairs it. The usual causes are an untrusted certificate (answer Yes in Windows' dialog) and the redirect being off. |
| **"Refusing unknown viewer" in the log** | The game still holds an account from the official servers. Log out in the game or clear its data so it makes a new account here, or allow such accounts in Settings. |
| **A career screen looks wrong** | Admin › Maintenance › **Fix the career screen**, then go back to the title screen and press Continue. |
| **The game freezes on an event or "Now Loading"** | Maintenance › **Clear stuck events**, then restart the game. |
| **An event or banner isn't showing** | Restart the game. If it still isn't there, play once on the official servers so the game updates its files. |
| **A setting doesn't seem to apply** | Each setting says when it takes effect. Most career settings apply from the next turn. |
| **Windows warns about an unknown publisher** | Normal for a new program without a paid signature. Choose **More info → Run anyway**. |

---

## FAQ

**Does this touch my real account?**
No. While the redirect is on, the game talks only to your PC, and the accounts you play on it exist only on your server. For extra safety, use a Steam account with no Data Link to your real game data.

**Do I need to patch or mod the game?**
No. The client is the real one, untouched. Only the optional Big fields mod touches it.

**Where are my saves, and how do I back them up?**
In UmamusumeX's data folder under your user profile. The Settings page exports everything as one file and restores any automatic backup.

**Can I use it offline?**
Yes. Once the game is installed, nothing needs the internet, apart from the update check and the optional Twitch mod.

**What if the game updates?**
The server tells the game when newer data exists, and the game fetches it. New events show up once you restart.

**What if I forget to go back to official?**
Closing UmamusumeX does it for you, the desktop shortcut does it, and a prompt at Windows sign-in offers it. You'd have to try quite hard to stay stranded.

**How do I remove it completely?**
About › Uninstall. It also removes the certificate, which is the one thing you'd otherwise have to find in `certmgr.msc`.

---

## Disclaimer and licence

UmamusumeX is an independent, unofficial project. It is **not affiliated with, endorsed by or sponsored by Cygames, Inc.** "Umamusume: Pretty Derby" and all related names and marks belong to their owners. No game assets are distributed: the server reads the game's data from your own installed copy.

UmamusumeX is **proprietary software**; see [LICENSE](LICENSE). You may download and run the official build for personal use. You may not copy, modify, redistribute or reuse it or its code. All rights reserved © 2026 Remezzo / Icarus.

Bundled third-party libraries keep their own licences; see [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

---

## Part of the Icarus suite

UmamusumeX is one tool in a family of Umamusume utilities by **Icarus**. Join the hub for releases, help and the wider toolset:

<div align="center">

### [→ discord.gg/wpbd3hTBDc](https://discord.gg/wpbd3hTBDc)

</div>

---

## Credits

**Remezzo** · **Maple** · **Icarus**
