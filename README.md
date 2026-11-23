# Dennis Decoene

Builder. Tinkerer. Pragmatist.

West-Flanders based. I work at the intersection of systems thinking and making things
that actually run.

## The quest

In 1984, the PC office ran on three programs: WordStar, dBASE III, and Lotus 1-2-3.
I'm rebuilding all three for the browser. Not emulation: clean-room reimplementation.
The interface stays sacred, down to the quirks. What gets added is the one thing 1984
couldn't do: multiple people in the same file at the same time.

- **[WebWordStar](https://github.com/DDecoene/WebWordStar)**: The 1978 word processor
  George R. R. Martin never gave up. The full diamond, `^K` blocks, dot commands, and
  a terminal aesthetic over WebSockets and SQLite, now with real-time multiplayer
  editing. v1.0 shipped.

- **[WebBaseIII](https://github.com/DDecoene/WebBaseIII)**: dBASE III, dot prompt and
  all. TypeScript interpreter, WebSocket/Node backend, WAL-mode SQLite, per-session
  isolated executors. Unlimited work areas, because we're no longer rationing DOS file
  handles. Shipped. Because some ideas deserve a proper second life.

- **[Web123](https://github.com/DDecoene/Web123)**: Lotus 1-2-3. The slash menu, @functions, keyboard-only cell navigation,
  and live collaboration on the same worksheet. Rust compiled to WebAssembly, local-first:
  the formula engine, a keyboard-driven grid (READY, EDIT, POINT) and CRDT-backed
  persistence already run. Peer-to-peer collaboration is next. This is the missing
  third of the trinity.

Then the endgame: all three on one shared virtual disk, integrated the way 1984 did
it: interchange files, not APIs. dBASE writes a `.wks`, Lotus reads it, WordStar
mail-merges the records. One Docker Compose file, one URL, the whole office. And once
there are files worth managing, **WebCommander**: two blue panels, F5 to copy. You
know the one.

### Want in?

Everything is open source and written to be read. If you ever ran an office on these
programs, or wish you'd been there, there's work that fits in an evening: @functions
for Web123, missing dot commands, or muscle-memory bug reports from people whose
fingers still know `^KB`. Open an issue on any repo, send a PR, or just come argue
about period authenticity.

## The other quest: a Commodore 64 game, and the tools to make it

- **[raster-rumble](https://github.com/DDecoene/raster-rumble)**: a C64 dodge game in
  6502 assembly. Raster bars, a story about a ship inside a C64 at night, and a dark
  industrial techno loop. **[Play it in your browser](https://ddecoene.github.io/raster-rumble/play/)**
  ([about the game](https://ddecoene.github.io/raster-rumble/)). Alpha.

- **[WebSidTracker](https://github.com/DDecoene/WebSidTracker)**: born because the
  game's sound was dragging it down. A SID music tracker in the browser
  ([open it](https://ddecoene.github.io/WebSidTracker/)) with a 2 KB player written from
  scratch in 6502 assembly, which runs in an emulator in the page and drives reSIDfp.
  Music and sound effects, exported as assembler source, `.prg` or `.sid`, and dropped
  into your own game. raster-rumble's tune is a tracker project you can open and change.
  Clean-room, alpha, v0.2.0.

## Also building

- **[rgwnd](https://rgwnd.app)**: Wind-optimized cycling route planning for the Belgian
  knooppuntennetwerk. Built for the rider who treats headwind as a variable, not a surprise.

## How I work

Self-hosted on Hetzner. Docker Compose, Caddy, Tailscale. I assemble existing tools
over building new ones when that's the honest answer. I have a bias toward shipping
things that work over announcing things that might.

18 years of Microsoft Dynamics NAV/Business Central in a past life. Still useful.
Not the whole story.

## Outside the terminal

Daily 30km on a non-electric bike. Working toward building custom steel bicycle frames:
fillet brazing, laser-cut dropouts, the whole thing. Somewhere between hobby and
slow-burn second career.

Also: Latin (Familia Romana), algorithmic music (Strudel/TidalCycles, dark warehouse
techno), and a philosophy paper that keeps getting longer.

## Contact

[@DDecoene](https://twitter.com/DDecoene) on X/Twitter
