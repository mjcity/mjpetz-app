# Changelog

What changed in each MjPetz release, in plain words. The newest release is at the top.

## 0.7.37 (13 November 2026)

- **Every page result tells the agent which browser it ran in,** so it never names the wrong one.

## 0.7.36 (13 November 2026)

- **Agents can read big pages, and a browser step never hangs a chat.** A deep page (Wikipedia's "Cat", say) now reads in seconds. Every browser step ends with a plain answer within about 90 seconds (time a card waits for you is not counted), so a message queued behind it goes.
- **Switching a running chat to Chief of Staff or Creator gives the agent its tools.** Claude Code gets them from your next message in the same chat. For agents that cannot change tools mid-chat, the preset menu says it starts a new chat, and your last chat is kept.
- **"Commands still running" stays readable in a narrow chat.** It becomes a terminal icon with a count instead of a cut-off word.

## 0.7.35 (13 November 2026)

- **New: Second Brain, one memory for every agent, if you want it.** It stays off until you say yes on a card. Then say "remember that …" or use Remember this on a message, and the Second Brain view lists your notes with search, pin, confirm and forget. Notes are plain files on your computer and never hold passwords or keys.
- **Second Brain keeps agents' orders back.** A note an agent saves that reads like an instruction waits for you before any agent sees it, a note can end on a date, and when an agent's note disagrees with yours, yours stands.
- **Approval cards say what the agent wants in plain words**, instead of raw code, and each button names exactly what it allows.
- **Confirmations look like MjPetz.** "Allow everything?", "Start a new key" and every "Delete …?" question are now MjPetz's own box. The safe button stays the default, and the other one only takes a fresh click.
- **A blocked request is no longer called "not signed in".** When a security check, proxy or rate limit stops a request, the chat says what happened in plain words.
- **Shorter freezes at start** and when opening the chat or Settings.
- **"Send to another screen" finishes the trip,** and lands the pet wholly on the new screen.
- **Busy agents glow in Teams.** An agent at work pulses in its own colour; one waiting for your OK shows a steady ringed dot.

## 0.7.34 (11 November 2026)

- **Paying and signing in always wait for you in the agents' browser.** Order buttons, pay forms, checkouts, donations, bids, account deletion and passkeys get your own card, which Full access never answers.
- **An agent is no longer told "the person did not allow" when nobody answered.** Only Deny is called a no.
- **Settings has search.** Press / or Ctrl+F to find any setting in any tab, and Settings now works fully from the keyboard.
- **The sidebar works from the keyboard and keeps full names visible.**
- **The Browser tab grew up.** Open its page in your own browser, copy its address, save a screenshot, open chat links in the side pane, and expand the pane over the chat and back. Loading, errors and the address bar are clearer.
- **Chat replies read more cleanly.** Plain sentences are no longer shown as code, tables scroll instead of breaking words, and code blocks have Wrap and Copy.
- **The chips over the message box fold neatly in a narrow chat** instead of piling up.

## 0.7.33 (11 November 2026)

- **A pet docked at the screen edge stays docked while it works,** leaning round the edge with its working animation, and is never cut off by its own window.
- **A queued message is no longer lost** when a Team or channel job takes the agent at the same moment.
- **Vanta's tablet glows again** while he works.

## 0.7.32 (11 November 2026)

- **New pet: Halo,** an operator in camouflage who rides off on a jet ski and rides back in on your other screen.
- **"Commands still running" only shows while something really runs.**
- **Settings fits a narrow pane.**
- **Run & Gun:** the first turret no longer hurts you from beside its crates, and your running shots hit it.
- **Vanta is sharper,** and his tablet now comes from behind his back.

## 0.7.31 (11 November 2026)

- **New pet: Vanta,** a tactical operator with night-vision goggles who leaves and arrives in a puff of smoke.
- **Run & Gun: Stage 2 opens.**
- **Offline only no longer stops every chat,** and its control is a small chip next to the shield.
- **The HUD bar no longer draws names over the message box.** It tidies itself in a fixed order when space runs short.

## 0.7.30 (10 November 2026)

- **New: Offline only.** One switch in Settings › Privacy & Data (and a chip in the chat) keeps cloud agents, connectors, shared channels, updates and web previews off the network, while MjPetz's own brain keeps working.
- **Safer Auto approvals.** Auto now lets a command through without a card only when it plainly just looks, and asks for anything that could reach a password file or leave the folder.
- **Shared channels sync long histories in any language,** emoji included.
- **The pet's bubble and notifications show clean status lines,** never raw code or streamed output, and keys are masked in them.
- **The pet repaints itself after sleep,** so it no longer goes invisible after many lid closes.
- **MjPetz's own brain asks every time before it opens or reads a file or page,** and only reads files you attach.

## 0.7.29 (10 November 2026)

- **Your settings survive a bad write.** A crash or full disk mid-save can no longer wipe your settings.
- **Desktop: MjPetz's own windows are off limits to agents,** so an agent can never press Allow for itself.
- **The pet's speech bubble stays on the screen,** even on a short laptop screen.
- **New colours: Honey, Amethyst and Amber** in Settings › Appearance.
- **Write in my voice.** Opt in to build a private style profile from your own sent Gmail messages, and attach it to an agent. It guides drafts and never sends anything.

For anything older, or anything that looks wrong here, email [support@mjpetz.xyz](mailto:support@mjpetz.xyz).
