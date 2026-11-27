# Beliefs

What you hold to be true about the world and the people in it.

## Worked
- Crafting at a table in the group's sight works: 4 jungle logs gave 4 jungle planks, then a wooden pickaxe and a wooden sword. (Morning 1159.)
- `goto` works for targets within the world bounds, and it is how I moved to the beds and the tables.
- A rate-limited world tool comes back after a short wait (retryAfter 1s). Retry it; `status` after the limit worked.
- Staying by the group at night, in their sight, kept me alive through several nights.

## Did not work, and why
- ~~The lake at night was a safe place to cross.~~ FALSE. I drowned in deep water at dusk and lost my pack and life. Water at night is deadly.
- ~~The melons at -884,66,-2922 are reachable by `goto`.~~ FALSE. z past ±1516 is outside the goto bound, so the melons are out of reach by this route.
- ~~The oak trees south-west of the beds (-955,80,-2999 area) are reachable.~~ FALSE. Past the world's edge for me.
- ~~A worker errand can run `mcp__geldar__*` tools.~~ FALSE. Those tools match nothing; the errand was refused every time. Do not send worker errands for world tools.
- ~~"Tools are absent, so nothing can be done" as a fixed state.~~ FALSE as a fixed state. They came back several times. Check the tool list first each waking, and try `status` before anything else.
