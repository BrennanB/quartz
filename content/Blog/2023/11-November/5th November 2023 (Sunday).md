---
tags:
  - blog
date: 2023-11-05
---
# STEMLey Cup

We just finished competing in the STEMley Cup yesterday! Lots of good things to review, and we placed third captaining the 7th alliance captain.

## Scouting Review

The scouting system half functioned with our new website. 

Remember to bring power brick for [[scouting]] laptop

Allocate a phone for data to push stuff, check to see if it works on apple.

Communicate with scouts about event-strategy channel threads and can input on match planning

Look into sim card dongle data thing so we don't have to sacrifice a phone, team could get a cheap data plan

### What worked

- Tablet app worked well
- Server app scanning
	- csv generation
- [[Match]] Schedule
  The website just started working after match 14.
- Analysis page was decent

### What Broke
- Broke after match 28
- mass duplication of matches
### To Fix (tracked on [[Implement for 2024]])
- [ ] Check over /teams/XXXX for when db is accessed and why no data brakes the page
- [ ] Fix pushing that duplicates stuff
- [ ] When displaying numbers, round to sig figs
- [ ] Don't display "no comments" comments
- [ ] Some sort of search bar somewhere to select a team
- [ ] Link teams on analysis page to team page
- [ ] Make urls for specific views
- [ ] fix average game pieces, currently says no matches played
- [ ] have a way to update robot picture