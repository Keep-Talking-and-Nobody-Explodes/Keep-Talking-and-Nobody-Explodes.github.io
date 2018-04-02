---
permalink: '/v1/the-button'
---
# The Button

_The Button_ is a module which consists of 3 inputs: the button's color, the button's label, and (potentially) the color of the strip next to the button.

## The Bomb Manual's Instructions

Follow these rules in the order they are listed. Perform the first action that applies:

1. If the button is blue and the button says "Abort", hold the button and refer to "Releasing a Held Button".
2. If there is more than 1 battery on the bomb and the button says "Detonate", press and immediately release the button.
3. If the button is white and there is a lit indicator with label CAR, hold the button and refer to "Releasing a Held Button".
4. If there are more than 2 batteries on the bomb and there is a lit indicator with label FRK, press and immediately release the button.
5. If the button is yellow, hold the button and refer to "Releasing a Held Button".
6. If the button is red and the button says "Hold", press and immediately release the button.
7. If none of the above apply, hold the button and refer to "Releasing a Held Button".

## Unofficial Instructions

Worst case, the Bomb Manual requires 7 steps to get to the default case - we strive to reduce that as much as possible, so this unofficial diagram will take no more that 4 steps. Align the color and label of the button, then follow the steps that apply **IN ORDER**.

**NOTE**: Count the number of batteries on the bomb before beginning a button phase. 

|           |Abort|Detonate|Hold   |(Other)|
|:----------|----:|-------:|------:|------:|
|   **Blue**|HOLD |1, 3    |3      |3      |
|  **White**|2, 3 |1, 2, 3 |2, 3   |2, 3   |
| **Yellow**|3    |1, 3    |3      |3      |
|    **Red**|3    |1, 3    |RELEASE|3      |
|**(Other)**|3    |1, 3    |3      |3      |

1. If there are at least 2 batteries, **press and immediately release**.<!-- DETONATE -->
2. If there is a lit 'CAR' indicator, **press and hold**.<!-- WHITE -->
3. If there are less than 3 batteries, **press and hold**.<!-- FRK -->
  - If there is a lit 'FRK' indicator, **press and immediately release**.
  - Otherwise, **press and hold**.

## Releasing a Held Button

If you start holding the button down, a colored strip will light up on the right side of the module. Based on its color you must release the button at a specific point in time:

* Blue: release when the countdown timer has a 4 in any position.
* Yellow: release when the countdown timer has a 5 in any position.
* Other: release when the countdown timer has a 1 in any position.
