# Movement

#### Commands

- using `/move <x> <y>` moves `<x>` steps to the right and `<y>` steps down.
- With the buttons below `/map`

#### Insights

- Moving at most 6 steps at a time takes always 2 seconds.
- Moving `x` steps (`x > 6`) takes `2 + 2 * (6 - x)` seconds (so 2 more seconds for each step after the 6th).
- To maximize speed, always take 6 steps.
- (to be verified) The automated path finding is not optimal and sometimes fails to find a path even tough it exists.
- (to be inestigated) Ladders take more time / the linear time part starts with few steps already

