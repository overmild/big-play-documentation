# Vision

## Problem statement

Fantasy football is something you do alone on your phone, even when you're sitting in a bar packed with people watching the exact same game. Every catch and touchdown might be quietly making or breaking someone's week, and nobody around them has any idea. Bars have the big screens and the crowd. What they don't have is anything tying what's happening on the field to what's happening in people's lineups. The most social night of the football week has no shared layer for the game most of those fans actually care about.

## Vision statement

Picture walking into a bar on Sunday, scanning in, and watching your fantasy team show up on the screen above the bar right along with the game. Every play that moves your score gets called out for the room to see instead of buried in a phone notification. The guy at the next table becomes your rival in that day's standings without either of you doing anything but showing up. Fantasy football stops being a private tab you check between plays. It becomes part of what everyone in the room is watching and yelling about.

## Goals

- [ ] Let a user sign in and pull in their existing fantasy team from the platforms people actually use, connected to a shared display
- [ ] Show fantasy points updating live, tied to real plays as they happen
- [ ] Support a physical check-in at a venue, so someone can scan or log in and join that bar's screen
- [ ] Build "Bar League," a leaderboard that automatically pits everyone checked in at a bar that day against each other
- [ ] Make joining fast enough that a stranger who's never heard of this can be on the screen in under a minute

## Non-goals

We're not building a fantasy platform ourselves. We plug into the ones that already exist. We don't compete with them, and we don't touch scoring rules or league management. No money changes hands here either. Bar League is bragging rights, not betting.

At MVP we're NFL only, on a handful of platforms, not every sport and every integration under the sun. We're also not trying to replace anything the bar already runs, like their TVs or ordering system. This is an extra screen, not a takeover of anything they already have going.

- Not building custom hardware from day one if a tablet and a QR code can prove the idea works
- Not supporting season-long leagues inside Bar League. It resets every day on purpose

## Target users / audience

| Who | Their need |
| --- | --- |
| Fantasy players at a bar | Want their live score visible without staring at a phone, and something to hold over whoever else is in the room |
| Bar owners | Want fantasy fans picking their bar over the one down the street, and staying longer once they're there |
| Casual fans who don't play fantasy | Want a reason to care when the room suddenly loses it over a third-string running back |
| League commissioners | Want an excuse to get the whole group together in person with something live to watch besides the game itself |

## Success looks like

Getting this running for real in one bar, with actual patrons signing in and seeing themselves on the screen, is the bar for MVP. From there:

- Someone walking in should be seeing their team on screen inside 60 seconds, not fumbling through a sign-in flow
- A full NFL Sunday should run end to end with Bar League live and the leaderboard actually correct
- Bar staff or owners should notice people sticking around longer or engaging differently because of the screen
- Scores on screen should match real plays as they happen, without lag or errors that make people distrust it

## Constraints

This is still ideation. There's no budget locked in and no committed team size, so scope has to stay something a small team, or one person, could actually build.

We're at the mercy of third-party fantasy platforms for roster and scoring data, and some of them don't offer a clean API or any API at all. Live NFL play-by-play data has the same problem. Getting it accurately in real time probably means paying for a data provider.

The hardware side adds real cost and real logistics: installing something, supporting it, making sure bar staff don't have to babysit it. For MVP this probably means faking the "device" with a QR code and a tablet rather than building anything custom. Bar wifi being unreliable is also just a fact of life we have to design around.

One more thing worth flagging early: using team logos, player likenesses, or broadcast footage on a public display isn't free of licensing questions. That needs a real look before this goes in front of actual customers.
