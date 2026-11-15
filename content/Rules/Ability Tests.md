---
share: true
color: var(--mk-color-green)
---
## Test Target Number
| Target Number | Test Difficulty | 50% Change | 90% Chance |
| :-----------: | --------------- | :--------: | :--------: |
|       7       | Routine         |     -3     |     +1     |
|       9       | Easy            |     -1     |     +3     |
|      11       | Average         |     +1     |     +5     |
|      13       | Challenging     |     +3     |     +7     |
|      15       | Hard            |     +5     |     +9     |
|      17       | Formidable      |     +7     |    +11     |
|      19       | Imposing        |     +9     |    +13     |
|      21       | Nigh Impossible |    +11     |    +15     |
## Basic Tests
1. Determine appropriate [[./Abilities and Focuses|Abilities and Focuses]]
2. Assign a target number
3. Roll & apply fortune
4. Test results successful >= target number

## Opposed Tests
1. Determine appropriate [[./Abilities and Focuses|Abilities and Focuses]] for both characters
2. Assign a target number for both characters
3. Both characters roll & apply fortune
4. Character 
	- win when >= TN and > opponent
	- Tie -> Drama dice
		- Tie -> highest ability score (including focus)
	- Both fail TN -> tie

## Advanced Test
1. Determine appropriate [[./Abilities and Focuses|Abilities and Focuses]] for both characters
2. Determine the TN or opposed roll
3. Each success on a test adds its Drama Die total to the success threshold until you either succeed or run out of time.
4. Each roll requires a time increment.
	- figure out the typical amount of time the task should take and divide it by half of the success threshold.
5. You make an ability test against the target number or opposed roll for each time increment:
	- Failure -> don’t make any headway, and the time passes. 
	- Success -> Add the Drama Die result to total
6. When the total meets or exceeds the success threshold, you complete the task.

| Task Difficulty | Success Threshold |
| --------------- | :---------------: |
| Easy            |         5         |
| Average         |        10         |
| Challenging     |        15         |
| Hard            |        20         |
| Formidable      |        25         |
## Challenge Test
Same as advanced test, with consequence for each failure. 
Determine how many times characters can fail at a challenge test before increasing the level of the consequences.
### Minor consequences
- Make the next test more difficult, increasing the target number by +2
- Increase the amount of time needed for each ability test
- Cause some minor complication
### Moderate consequences
- Make all future tests more difficult, increasing the target number by +2
- Eliminating half of your accumulated progress towards the success threshold
- Close off current avenue of progress, forcing you to adopt a new approach (may require change of focus)

### Major consequences
- Jeopardise the entire challenge test forcing characters to:
	- start the test over from the beginning
	- complete another advanced or challenge test in order to pick up where they left off

## Assisting Tests
If multiple characters work together on a task, one player is designated as the primary roller. Other characters who assist must have an applicable [[./Abilities and Focuses|Abilities and Focuses]] related to the test.

Bonus for Assistance – For each assisting character, the primary roller gains a +1 bonus to their roll, up to a maximum of +3.

## Probability of scores
| Score | Cumulative Probability (%) | Exact Probability (%) |
| :---: | :------------------------: | :-------------------: |
|   3   |             0              |           0           |
|   4   |             2              |           1           |
|   5   |             5              |           3           |
|   6   |             9              |           5           |
|   7   |             16             |           7           |
|   8   |             26             |          10           |
|   9   |             38             |          12           |
|  10   |             50             |          12           |
|  11   |             62             |          12           |
|  12   |             74             |          12           |
|  13   |             84             |          10           |
|  14   |             91             |           7           |
|  15   |             95             |           5           |
|  16   |             98             |           3           |
|  17   |            100             |           1           |
|  18   |            100             |           0           |
