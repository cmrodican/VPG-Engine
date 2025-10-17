# Grappling System

## Overview

The grappling system was the core mechanic and what set the AKI Engine (and soon our VPG Engine) apart from other wrestling games. 

The system emphasizes timing, positioning, and strategic decision-making over button mashing.

The grappling system operates on two strength levels (light/weak and heavy/strong) combined with directional inputs, creating a deep and varied moveset for each character based on position and context.

## Core Mechanics

### Grapple Button (A Button)

The A button is used to initiate and execute grapples:

- **Tap A** = Light/Weak Grapple (quick, less damage, faster recovery)
- **Hold A** = Heavy/Strong Grapple (powerful, more damage, longer animation, more vulnerable to reversals)

### Initiation and Positions

Grappling is initiated by pressing the grapple (A) button. The available moves depend on the position from which the grapple is initiated:

#### Front Grapple
Standard face-to-face lock-up position, initiated by approaching and grappling from the front of your opponent by pressing the grapple (A) button, or by switching to Front Grapple from Back Grapple using the L or R buttons.
#### Back Grapple  
When approaching and grappling from behind the opponent, or using L or R to switch to Back Grapple from Front Grapple. Limited moveset compared to front position.
##### Switching
Switching between front and back grapple may initiated by using the L Button.  The player may switch between front and back grapple a limited number of times in a single lock-up.
##### Breaking
The player may break a front or back grapple using the R button.
#### Corner/Turnbuckle Grapple
Special grappling position when opponent is against the turnbuckles. Has unique weak and strong grapple variations for both front and back positions.

### Move Execution System

Once a grapple is initiated, the player inputs a **direction + grapple strength** combination to execute a specific move:

#### Front Weak Grapple Moves (Tap A)
Players can execute **10 different moves** from a front weak grapple:

1. **Neutral (no direction)** + A
2. **Up** + A  
3. **Down** + A
4. **Left** + A
5. **Right** + A
6. **Up + Left** + A
7. **Up + Right** + A
8. **Down + Left** + A
9. **Down + Right** + A
10. **[Additional input combination]** [NEEDS DOCUMENTATION]

*Example from The Rock:*
- Neutral + Tap A = Headlock and Punch
- Up + Tap A = Snapmare
- Down + Tap A = Eye Rake
- Left/Right + Tap A = Neck Breaker 02

#### Front Strong Grapple Moves (Hold A)
Players can execute **10 different moves** from a front strong grapple:

1. **Neutral (no direction)** + Hold A
2. **Up** + Hold A
3. **Down** + Hold A
4. **Left** + Hold A
5. **Right** + Hold A
6. **Up + Left** + Hold A
7. **Up + Right** + Hold A
8. **Down + Left** + Hold A
9. **Down + Right** + Hold A
10. **[Additional input combination]** [NEEDS DOCUMENTATION]

*Example from The Rock:*
- Neutral + Hold A = Scoop Slam
- Up + Hold A = Headlock Takedown
- Down + Hold A = Suplex
- Left/Right + Hold A = Shoulder Breaker

Strong grapples typically:
- Deal more damage
- Have longer animations
- Create larger reversal windows
- Can transition to power moves

#### Back Weak Grapple Moves (Tap A)
Players can execute **4 different moves** from a back weak grapple:

1. **Neutral (no direction)** + Tap A
2. **Up or Down** + Tap A
3. **Left** + Tap A
4. **Right** + Tap A

*Example from The Rock:*
- Neutral + Tap A = Falling Back Drop
- Up/Down + Tap A = Surfboard Stretch
- Left + Tap A = Shin Breaker
- Right + Tap A = Atomic Drop

#### Back Strong Grapple Moves (Hold A)
Players can execute **4 different moves** from a back strong grapple:

1. **Neutral (no direction)** + Hold A
2. **Up or Down** + Hold A
3. **Left** + Hold A
4. **Right** + Hold A

*Example from The Rock:*
- Neutral + Hold A = Falling Back Drop
- Up/Down + Hold A = Surfboard Stretch  
- Left + Hold A = Shin Breaker
- Right + Hold A = Atomic Drop

### Special/Finisher System

When a wrestler has built sufficient **momentum** (indicated by the "Special" mode activation), they can execute their signature finishing move:

**Execution**: Get into a **strong grapple** (Hold A) and press the **Analog Stick** (N64 control stick)

*Example from The Rock:*
- Strong Grapple + Analog Stick = Rock Bottom (Finisher)

*Example from Stone Cold:*
- Strong Grapple + Analog Stick = Stone Cold Stunner (Finisher)

This requires the wrestler to be in "Special" mode, achieved through building momentum with successful offensive maneuvers.

### Priority System

When both wrestlers attempt a grapple simultaneously:

1. **Strong beats Weak**: Hold A (strong grapple) has priority over Tap A (weak grapple)
2. **Timing matters**: If both use the same strength, the player who pressed slightly earlier gets control
3. **Position influence**: [NEEDS RESEARCH - does positioning near ropes/corners affect priority?]

### Grapple Reversals

Strong grapples have larger reversal windows due to their longer animations. Light grapples are faster and harder to reverse.

**Reversal Mechanics:**
- Must be input during a specific frame window in the opponent's move animation
- [NEEDS DOCUMENTATION - exact button press for reversals]
- [NEEDS DOCUMENTATION - visual/audio cues for reversal timing]
- Different move types have different reversal window sizes

**Counter Types Observed:**
- Counter Elbow Strike (back weak grapple counter)
- Counter Grapple (back strong grapple counter)
- Counter Groin Kick
- Counter Stunner
- [More counter types need documentation]

### Irish Whip Grapples

Irish Whip attacks create a special grappling scenario:

**Setup**: Apply a grapple → Whip opponent into ropes → Grapple them as they return

**Irish Whip Grapple Options:**
- **Tap A (Weak)**: Quick counter move as opponent bounces back
- **Hold A (Weak)**: Slightly stronger counter move  
- **Tap A (Strong)**: Power move counter
- **Hold A (Strong)**: Maximum damage counter move
- **Special**: Can execute finisher if in Special mode

*Example from The Rock:*
- Irish Whip + Hold A (Strong) = Tilt-A-Whirl Driver

### Running Grapples

Running grapples have their own unique moveset:

**Execution**: Run + Press A when near opponent

**Variations:**
- **Run + A (Front)**: Running front grapple move
- **Run + A (Back)**: Running back grapple move  
- **Run + Up + A**: Additional running grapple variant
- **Run + Down + A**: Additional running grapple variant

*Example from The Rock:*
- Run + A (Front) = Rock Spinning DDT

Running grapples bypass the normal tie-up phase and execute immediately.

## Observations

### Grapple vs Strike Interaction
- Grapples and strikes operate on separate button systems (A for grapple, B for strike)
- [NEEDS RESEARCH - What happens when a grapple and strike are attempted simultaneously?]
- [NEEDS RESEARCH - Can strikes interrupt grapple attempts?]

### Light vs Strong Grapples
- **Light grapples** (Tap A):
  - Execute faster
  - Smaller reversal windows
  - Less damage output
  - Faster recovery time
  - Better for maintaining offensive pressure

- **Strong grapples** (Hold A):
  - Longer execution time
  - Larger reversal windows (more vulnerable)
  - Higher damage output
  - Longer recovery time
  - Better for finishing sequences

### Position-Based Movesets
- Front grapples offer the most variety (10 weak + 10 strong = 20 total moves)
- Back grapples are more limited (4 weak + 4 strong = 8 total moves)
- Each character has a completely unique moveset
- Moves marked as "FAVORITE" in character data [PURPOSE NEEDS RESEARCH]

### Grapple Range and Magnetism
- Grapples have a "magnetic" quality where wrestlers snap into position
- Distance threshold exists for grapple initiation [MEASUREMENT NEEDED]
- Different approach angles may trigger different grapple positions
- Corner proximity affects available moves

### Special Grapple States
- **Corner/Turnbuckle Grapples**: Unique weak and strong grapple options
- **Apron Grapples**: Special grapples from ring apron
- **Irish Whip Grapples**: Special counter-grapple system
- **Running Grapples**: Bypass normal grapple tie-up
- **Counter Grapples**: Defensive grapple reversals

## Open Questions

### Core Mechanics
- [ ] Exact frame count for tie-up initiation phase
- [ ] Input buffer window (how early can you input direction + button?)
- [ ] Does holding a direction during approach affect grapple position?
- [ ] What determines which 10 directional combinations are used for front grapples?

### Priority and Collision
- [ ] Exact priority rules when both players press A simultaneously at same strength
- [ ] Does positioning (near ropes, corners) affect grapple priority?
- [ ] How does momentum meter affect grapple priority?
- [ ] Collision detection specifics for grapple initiation range

### Reversal System
- [ ] Exact button input for reversals (is it A, B, or context-dependent?)
- [ ] Frame-perfect timing windows for each move type
- [ ] Do light and strong grapples have different reversal windows?
- [ ] Visual/audio cues for reversal timing
- [ ] Can you reverse a reversal?
- [ ] Does momentum affect reversal difficulty?

### Special Mode / Finishers
- [ ] Exact momentum threshold required to enter Special mode
- [ ] Does Special mode expire or persist?
- [ ] Can finishers be reversed like normal grapples?
- [ ] Is the finisher input always Analog Stick, or character-specific?

### Advanced Mechanics
- [ ] What are "FAVORITE" moves and do they have special properties?
- [ ] Chain grappling - can you buffer next grapple during current move animation?
- [ ] Stamina system interaction with grapple effectiveness
- [ ] Ground transition mechanics from standing grapples
- [ ] Position advantages after successful grapples

### Move Properties
- [ ] Damage scaling between light and strong grapples
- [ ] Recovery frames after executing moves
- [ ] Recovery frames after receiving moves
- [ ] Body part targeting system (which moves damage which body parts?)
- [ ] Do some moves have automatic follow-ups or transitions?

## Related Systems

- [Strike System](strike-system.md) - The B button strike mechanics that parallel grappling
- [Momentum (Attitude) Meter](momentum-attitude.md) - Building momentum to unlock Special mode
- [Reversal Windows](reversal-windows.md) - Detailed timing mechanics for counters
- [Damage Scaling](damage-scaling.md) - How damage affects grapple effectiveness  
- [Irish Whip System](irish-whip-system.md) - The unique bouncing grapple mechanic
- [Ground Game](ground-game.md) - Transition from standing grapples to ground
- [Running Mechanics](running-mechanics.md) - Movement and running attack system

## Data Structure

### Character Grapple Movesets

| Front Weak Grapple [Tap A]        | Front Strong Grapple [Hold A]       |
|-----------------------------------|-------------------------------------|
| A                                 | A                                   |
| LEFT / RIGHT + A                  | LEFT / RIGHT + A                    |
| UP + A                            | UP + A                              |
| DOWN + A                          | DOWN + A                            |
| B                                 | B                                   |
| LEFT / RIGHT + B                  | LEFT / RIGHT + B                    |
| UP + B                            | UP + B                              |
| DOWN + B                          | DOWN + B                            |
|                                   | SPECIAL (CONTROL STICK)             |

| Back Weak Grapple [Tap A]         | Back Strong Grapple [Hold A]        |
|-----------------------------------|-------------------------------------|
| A                                 | A                                   |
| D-PAD + A                         | D-PAD + A                           |
| B                                 | B                                   |
| D-PAD + B                         | D-PAD + B                           |
|                                   | SPECIAL (CONTROL STICK)             |



| REVERSALS                         |(Quickly tapping L, R, A and B)      |
|-----------------------------------|-------------------------------------|
| Back Weak Grapple Counter         | Back Strong Grapple Counter         |
|                                   |                                     |




```
Front Weak Grapple (Tap A):
  - A
  - Up + A  
  - Down + A
  - Left or Right + A
  - B
  - Up + B
  - Down + B
  - Left or Right + B

Front Strong Grapple (Hold A):
  - A
  - Up + A  
  - Down + A
  - Left or Right + A
  - B
  - Up + B
  - Down + B
  - Left or Right + B
  - Control Stick = Finisher

Back Weak Grapple (Tap A):
  - A
  - Up + A  
  - D-Pad + A
  - B
  - D-Pad + B

Back Strong Grapple (Hold A):
  - A
  - Up + A  
  - D-Pad + A
  - B
  - D-Pad + B
  - Control Stick = Finisher
```

See [move-template.json](../../data/schemas/move-template.json) for the full data structure used to define grapple moves.

## Research Needed

1. **Reversal system mechanics** - Button inputs and timing windows?
2. **Priority resolution** - All edge cases for simultaneous grapples?
3. Frame data for grapple phases (initiation, execution, recovery)
4. Reversal window timing for light vs strong grapples
5. Complete moveset documentation for multiple characters (Data currently on Fandom and GameFAQ)
6. Grapple range and collision thresholds
7. Damage values and scaling for grapple types
8. Position transition logic after moves
9. Body part targeting system
10. Animation frame counts
11. Audio cue timing
12. Visual effect details

## Contributing

To contribute to this documentation:

1. **Select a character** in No Mercy and test their grapple moveset
2. **Document systematically** - Test each input combination methodically
3. **Record observations** - Note timing, damage, transitions, and behavior
4. **Test edge cases** - Try unusual situations and combinations
5. **Update this doc** - Submit PR with findings added to appropriate sections

**Testing Protocol Example:**
- Boot up Exhibition Mode
- Select character to test
- Practice Mode recommended for frame-accurate observation
- Test front weak and strong grapples
- Test back weak and strong grapples
- Document damage, timing, additional mechanics, etc
- Note any special properties (FAVORITE designation, transitions, etc.)



## References

- WWF No Mercy Fandom Wiki - Character Move Data
  - [The Rock Moveset](https://wwfnomercy.fandom.com/wiki/The_Rock#Moves)
  - [Steve Austin Moveset](https://wwfnomercy.fandom.com/wiki/Steve_Austin#Moves)
- In-game testing and observation


---

**Last Updated**: [Date]  
**Contributors**: [Names will be added as people contribute]  
**Status**: 🚧 In Progress - Core structure documented, detailed frame data and testing needed
