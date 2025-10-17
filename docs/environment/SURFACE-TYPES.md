# Surface Types

## Purpose

This document catalogs every surface type found in WWF No Mercy and the properties associated with each surface. Understanding surface properties is critical for recreating the environmental physics and gameplay feel of the original game.

Surface types affect:
- Move damage scaling
- Impact sounds
- Visual effects
- Bounce physics
- Character movement speed
- Collision behavior
- Available actions and interactions

## Surface Collision Types

All surfaces in WWF No Mercy fall into one of the following collision behavior categories:

| Surface Kind | Collision Behavior | Character Response | State After Impact | Examples |
|-------------|-------------------|-------------------|-------------------|----------|
| **Rope Surface** | Elastic bounce-back | Character bounces off and runs back in opposite direction | Running/momentum maintained | Ring ropes (top, middle, bottom) |
| **Hard Wall Surface** | Face-first collision | Character hits face-first, then either stands dazed or falls down based on damage/momentum | Standing dazed OR lying on floor | Brick walls, solid barriers |
| **Corner Turnbuckle Surface** | Auto-turn collision | Character turns around before impact, lands back-first against surface | Standing against surface, vulnerable to corner offense | Ring corner turnbuckles |
| **Barricade Surface** | Auto-turn collision | Character turns around before impact, lands back-first, remains standing and dazed | Standing dazed, vulnerable to strikes/grapples | Barricades, table sides, backstage barriers |
| **Edge/Ledge Surface** | Balance struggle | Character windmills arms attempting to maintain balance | Balance struggle state, vulnerable to back-grapples/strikes | Stage edges, elevated platform edges, ring apron edge (when applicable) |
| **Soft Barrier Surface** | No collision effect | Character simply stops upon contact, no reaction | Normal standing state | Entrance stage objects, locker room cubbyholes, locker room desk/chairs, backstage furniture |
| **Standard Floor** | Normal movement | Standard walking/running | Normal gameplay state | Ring mat, arena floor, ramps, stage surface |

### Detailed Surface Kind Behaviors

#### 1. Rope Surface
**Collision Mechanic:**
- Character makes contact with ropes
- Character bounces elastically off ropes
- Character runs back in the direction they came from
- Momentum is maintained or amplified

**Properties:**
- [Bounce force/speed - NEEDS MEASUREMENT]
- [Sound effect on contact - NEEDS DOCUMENTATION]
- [Can ropes be broken? - NEEDS RESEARCH]
- [Different rope heights (top/middle/bottom) behave differently? - NEEDS TESTING]

**Game Examples:**
- Top rope
- Middle rope  
- Bottom rope
- [Any other rope-type surfaces? - NEEDS VERIFICATION]

---

#### 2. Hard Wall Surface
**Collision Mechanic:**
- Character runs/is thrown toward surface
- Character collides face-first into wall
- **Outcome A** (lower damage/momentum): Character stands dazed for several moments
- **Outcome B** (higher damage/momentum): Character falls down and lies on floor

**Properties:**
- [Damage threshold for daze vs fall - NEEDS MEASUREMENT]
- [Daze duration based on damage state - NEEDS DOCUMENTATION]
- [Impact sound effect - NEEDS DOCUMENTATION]
- [Visual effect (stars, screen shake, etc.) - NEEDS OBSERVATION]

**Game Examples:**
- Brick walls (backstage areas)
- Solid barriers
- [Other hard wall surfaces - NEEDS DOCUMENTATION]

---

#### 3. Corner Turnbuckle Surface
**Collision Mechanic:**
- Character is Irish whipped toward corner
- Character automatically turns around just before collision
- Character lands back-first against turnbuckle
- Character remains in corner position for set duration
- Opponent can perform corner-specific offense

**Properties:**
- [Auto-turn timing/distance from corner - NEEDS MEASUREMENT]
- [Duration character remains in corner - NEEDS DOCUMENTATION]
- [Does damage/momentum affect duration? - NEEDS TESTING]
- [Can character escape corner early? - NEEDS RESEARCH]
- [Available offensive moves in this state - NEEDS DOCUMENTATION]

**Game Examples:**
- Ring corner turnbuckles (all four corners)
- [Are there other corner-type surfaces? - NEEDS VERIFICATION]

---

#### 4. Barricade Surface
**Collision Mechanic:**
- Character is Irish whipped toward barricade
- Character automatically turns around just before collision
- Character lands back-first against barricade
- Character remains standing, dazed
- Daze duration depends on damage and momentum
- Character is vulnerable to standard strikes and grapples

**Properties:**
- [Auto-turn timing/distance from barricade - NEEDS MEASUREMENT]
- [Daze duration formula (damage + momentum) - NEEDS DOCUMENTATION]
- [Can character recover/move during daze? - NEEDS TESTING]
- [Damage taken from barricade impact - NEEDS MEASUREMENT]
- [Sound effect on impact - NEEDS DOCUMENTATION]

**Game Examples:**
- Ring barricades (crowd barriers)
- Table sides (when table is set up)
- Backstage barriers
- [Other barricade-type surfaces - NEEDS DOCUMENTATION]

---

#### 5. Edge/Ledge Surface
**Collision Mechanic:**
- Character is Irish whipped toward edge/ledge
- Character enters "balance struggle" animation
- Arms swing in circular windmill motion
- Character attempts to maintain balance
- Character is vulnerable to back-grapples and strikes
- **If struck**: Character falls to floor below (if applicable)
- **If at boundary**: Character cannot fall (no lower surface exists)

**Properties:**
- [Balance struggle duration - NEEDS MEASUREMENT]
- [Can character self-recover from balance struggle? - NEEDS TESTING]
- [Which attacks cause fall? All strikes/grapples or specific ones? - NEEDS DOCUMENTATION]
- [Fall damage calculation - NEEDS MEASUREMENT]
- [Distance from edge that triggers balance struggle - NEEDS MEASUREMENT]

**Game Examples:**
- Stage edges (entrance stage to ramp)
- Elevated platform edges
- Ring apron edge (in certain contexts)
- [Other edge surfaces - NEEDS DOCUMENTATION]

---

#### 6. Soft Barrier Surface
**Collision Mechanic:**
- Character runs/is Irish whipped toward surface
- Character simply stops upon making contact
- No bounce, no daze, no special animation
- Character remains in normal standing state
- No gameplay effect from collision

**Properties:**
- [Does collision make any sound? - NEEDS DOCUMENTATION]
- [Is there any visual feedback? - NEEDS OBSERVATION]
- [Can character immediately act after stopping? - NEEDS TESTING]
- [Does this surface type cause any damage? - NEEDS VERIFICATION]

**Game Examples:**
- Entrance stage objects/decorations
- Locker room cubbyholes
- Locker room desk and chairs
- Backstage furniture and set pieces
- [Other soft barrier surfaces - NEEDS DOCUMENTATION]

---

#### 7. Standard Floor Surface
**Collision Mechanic:**
- Normal surface with no special collision behavior
- Character can walk, run, perform moves normally
- Standard gameplay state

**Properties:**
- [Movement speed - NEEDS MEASUREMENT]
- [Friction values - NEEDS DOCUMENTATION]
- [Footstep sound effects - NEEDS DOCUMENTATION]
- [Does surface type affect damage? - NEEDS TESTING]

**Game Examples:**
- Ring mat (canvas)
- Arena floor (ringside)
- Entrance ramp
- Stage floor
- Backstage floors
- [Other standard surfaces - NEEDS DOCUMENTATION]

## Surface Categories

### Ring Surfaces

#### Ring Mat (Canvas)
The primary wrestling surface inside the ring.

**Properties:**
- [Impact absorption - NEEDS DOCUMENTATION]
- [Move damage modifier - NEEDS DOCUMENTATION]
- [Bounce physics - NEEDS DOCUMENTATION]
- [Friction coefficient - NEEDS DOCUMENTATION]
- [Sound effects - NEEDS DOCUMENTATION]

**Observations:**
- Standard surface for most in-ring action
- [Movement speed compared to other surfaces - NEEDS TESTING]
- [Does mat condition degrade during match? - NEEDS RESEARCH]

#### Ring Apron
The narrow platform outside the ropes but still part of the ring structure.

**Properties:**
- [Impact damage modifier - NEEDS DOCUMENTATION]
- [Bounce behavior - NEEDS DOCUMENTATION]
- [Friction - NEEDS DOCUMENTATION]
- [Sound effects - NEEDS DOCUMENTATION]
- [Available moves/actions - NEEDS DOCUMENTATION]

**Observations:**
- Harder surface than ring mat
- Unique grapple and attack options available
- [Falls from apron - behavior and damage - NEEDS TESTING]

### Outside Ring Surfaces

#### Arena Floor (Ringside)
The floor surrounding the ring where announcers and equipment are located.

**Properties:**
- [Impact damage modifier - NEEDS DOCUMENTATION]
- [Bounce physics - NEEDS DOCUMENTATION]
- [Movement speed - NEEDS DOCUMENTATION]
- [Sound effects - NEEDS DOCUMENTATION]

**Observations:**
- Appears to be concrete or similar hard surface
- Higher damage from moves compared to ring mat
- [Count-out timer behavior - NEEDS DOCUMENTATION]

#### Entrance Ramp
The walkway from entrance stage to ring area.

**Properties:**
- [Surface material - NEEDS DOCUMENTATION]
- [Impact damage modifier - NEEDS DOCUMENTATION]
- [Movement properties - NEEDS DOCUMENTATION]
- [Slope/incline effects - NEEDS DOCUMENTATION]

**Observations:**
- [Does ramp incline affect movement or physics? - NEEDS TESTING]
- [Available actions on ramp vs floor - NEEDS DOCUMENTATION]

#### Entrance Stage
The elevated platform at the top of the entrance ramp.

**Properties:**
- [Surface material - NEEDS DOCUMENTATION]
- [Impact damage modifier - NEEDS DOCUMENTATION]
- [Fall damage from stage - NEEDS DOCUMENTATION]
- [Height difference effects - NEEDS DOCUMENTATION]

**Observations:**
- [Can wrestlers fight on stage? - NEEDS VERIFICATION]
- [Special moves or interactions available - NEEDS DOCUMENTATION]

### Interactive Surfaces

#### Announce Table
The commentary table at ringside that can be interacted with.

**Properties:**
- [Destructible behavior - NEEDS DOCUMENTATION]
- [Impact damage when used - NEEDS DOCUMENTATION]
- [Break threshold - NEEDS DOCUMENTATION]
- [Sound and visual effects - NEEDS DOCUMENTATION]

**Observations:**
- Can be broken by certain moves
- [Which moves break the table? - NEEDS TESTING]
- [Does table provide damage bonus? - NEEDS RESEARCH]

#### Steel Steps
The metal stairs used to enter the ring.

**Properties:**
- [Material hardness - NEEDS DOCUMENTATION]
- [Impact damage modifier - NEEDS DOCUMENTATION]
- [Moveable object physics - NEEDS DOCUMENTATION]
- [Sound effects - NEEDS DOCUMENTATION]

**Observations:**
- Can be used as weapon
- [Can steps be moved/positioned? - NEEDS TESTING]
- [Collision with steps during movement - NEEDS DOCUMENTATION]

#### Barricade
The barrier between ringside area and audience.

**Properties:**
- [Impact damage modifier - NEEDS DOCUMENTATION]
- [Collision behavior - NEEDS DOCUMENTATION]
- [Irish whip interaction - NEEDS DOCUMENTATION]
- [Destructible or static? - NEEDS DOCUMENTATION]

**Observations:**
- Wrestlers can be thrown into or over barricade
- [Special moves involving barricade - NEEDS DOCUMENTATION]
- [Does barricade break? - NEEDS TESTING]

### Match-Specific Surfaces

#### Ladder
Metal ladder used in ladder matches.

**Properties:**
- [Set-up positions - NEEDS DOCUMENTATION]
- [Climb speed - NEEDS DOCUMENTATION]
- [Fall damage from ladder - NEEDS DOCUMENTATION]
- [Impact damage when used as weapon - NEEDS DOCUMENTATION]
- [Durability/break threshold - NEEDS DOCUMENTATION]

**Observations:**
- Can be climbed, moved, and used as weapon
- [Collision behavior when placed - NEEDS TESTING]
- [Maximum height for falls - NEEDS MEASUREMENT]

#### Table
Breakable tables used in matches.

**Properties:**
- [Break threshold - NEEDS DOCUMENTATION]
- [Which moves break tables? - NEEDS DOCUMENTATION]
- [Set-up requirements - NEEDS DOCUMENTATION]
- [Impact damage bonus - NEEDS DOCUMENTATION]
- [Surface before breaking - NEEDS DOCUMENTATION]

**Observations:**
- Must be set up before breaking
- [Can wrestlers stand on unbroken table? - NEEDS TESTING]
- [Visual/audio effects on break - NEEDS DOCUMENTATION]

#### Steel Chair
Metal folding chair weapon.

**Properties:**
- [Impact damage value - NEEDS DOCUMENTATION]
- [Durability - NEEDS DOCUMENTATION]
- [Stun duration - NEEDS DOCUMENTATION]
- [Sound effects - NEEDS DOCUMENTATION]

**Observations:**
- Most common weapon
- [Different attack types with chair? - NEEDS DOCUMENTATION]
- [Does chair degrade or break? - NEEDS TESTING]

#### Cell (Hell in a Cell)
The steel cage structure in Hell in a Cell matches.

**Properties:**
- [Mesh surface properties - NEEDS DOCUMENTATION]
- [Climbing behavior - NEEDS DOCUMENTATION]
- [Top of cell surface - NEEDS DOCUMENTATION]
- [Break points/weak spots - NEEDS DOCUMENTATION]
- [Collision with cell walls - NEEDS DOCUMENTATION]

**Observations:**
- Can be climbed
- Top of cell is separate fighting surface
- [Fall damage from top of cell - NEEDS MEASUREMENT]
- [Can cell be broken? Where? - NEEDS DOCUMENTATION]

#### Cage (Steel Cage Match)
The chain-link or bar cage used in cage matches.

**Properties:**
- [Wall collision behavior - NEEDS DOCUMENTATION]
- [Climbing speed - NEEDS DOCUMENTATION]
- [Throwing opponent into cage - NEEDS DOCUMENTATION]
- [Escape requirements - NEEDS DOCUMENTATION]

**Observations:**
- Wrestlers can climb to escape
- [Damage from hitting cage - NEEDS TESTING]
- [Different cage types/materials? - NEEDS RESEARCH]

## Surface Property Framework

### Universal Properties to Document

For each surface type, we should document:

1. **Material Type**
   - Visual appearance
   - Texture
   - Material classification (soft, hard, metal, wood, etc.)

2. **Physics Properties**
   - Friction coefficient
   - Bounce/rebound behavior
   - Impact absorption
   - Collision detection boundaries

3. **Damage Modifiers**
   - Base damage multiplier
   - Does surface increase move damage?
   - Critical hit threshold

4. **Sound Properties**
   - Impact sound effects
   - Footstep sounds
   - Material-specific audio cues

5. **Visual Effects**
   - Impact visual effects
   - Surface damage/wear
   - Particle effects

6. **Movement Properties**
   - Movement speed on surface
   - Running behavior
   - Can wrestler stand/walk on surface?

7. **Interaction Properties**
   - Available moves on surface
   - Special interactions
   - Destructible behavior
   - Moveable/static

8. **Gameplay Rules**
   - Count-out behavior
   - Pin availability
   - Submission availability
   - Special match rules

## Research Methodology

### Testing Protocol

To document surface properties accurately:

1. **Visual Inspection**
   - Screenshot each surface type
   - Note texture and appearance
   - Document color and material indicators

2. **Physics Testing**
   - Test identical moves on different surfaces
   - Measure bounce behavior (if applicable)
   - Test character movement speed across surfaces
   - Document collision boundaries

3. **Damage Testing**
   - Execute same move on different surfaces
   - Compare damage dealt
   - Test if damage varies by surface type
   - Document any visible damage differences

4. **Audio Documentation**
   - Record sound effects for each surface
   - Note impact sounds
   - Document footstep variations
   - Identify material-specific cues

5. **Interaction Testing**
   - Test all possible actions on each surface
   - Document which moves are available/unavailable
   - Test special interactions
   - Verify destructible behavior

## Open Questions

### General Surface Mechanics
- [ ] Is there a universal damage multiplier system for surface types?
- [ ] Do surfaces have durability that degrades during matches?
- [ ] Are there hidden surface properties not visible to player?
- [ ] Do weather/arena conditions affect surface properties?

### Ring Mat Specific
- [ ] Does the mat have different properties in different ring areas?
- [ ] Are there "sweet spots" or "danger zones" on the mat?
- [ ] Does repeated impact affect mat properties?

### Hard Surfaces (Floor, Apron, etc.)
- [ ] What is the exact damage multiplier for hard surfaces vs mat?
- [ ] Do different arena floors have different properties?
- [ ] Is there a "critical hit" threshold on hard surfaces?

### Interactive Objects
- [ ] Do weapons degrade with use?
- [ ] What determines when an object breaks?
- [ ] Can all objects be moved/positioned?
- [ ] Are there weight physics for objects?

### Match-Specific
- [ ] Do surface properties change in specialty matches?
- [ ] Are there surfaces unique to specific arenas?
- [ ] Do surface types affect AI behavior?

## Related Documentation

- [Ring Dimensions](ring-dimensions.md) - Measurements and layout of ring surfaces
- [Interactive Objects](interactive-objects.md) - Detailed object properties and behavior
- [Collision Points](collision-points.md) - Collision detection for surfaces
- [Damage Scaling](../mechanics/damage-scaling.md) - How surface types affect damage
- [Physics System](../mechanics/physics-system.md) - Overall physics engine behavior

## Contributing

To contribute surface type documentation:

1. **Choose a surface** type from the list above
2. **Test systematically** using the research methodology
3. **Record observations** with specific examples and measurements
4. **Document properties** in the appropriate section
5. **Note uncertainties** - mark what needs verification
6. **Submit findings** via pull request

Testing tools that may help:
- Video capture for frame-by-frame analysis
- Audio recording for sound documentation
- Screenshot tools for visual reference
- Practice/exhibition modes for controlled testing

## Data Structure

Surface properties should eventually be formalized in JSON schemas:

```json
{
  "surface_id": "ring_mat",
  "display_name": "Ring Canvas",
  "category": "ring_surface",
  "material_type": "soft",
  "properties": {
    "friction": 0.0,
    "bounce": 0.0,
    "damage_multiplier": 1.0,
    "movement_speed_modifier": 1.0,
    "sound_profile": "mat_impact",
    "allows_pinfall": true,
    "allows_submission": true,
    "destructible": false
  }
}
```

See [surface-template.json](../../data/schemas/surface-template.json) for the complete schema.

---

**Last Updated**: [Date]  
**Contributors**: [Names will be added as people contribute]  
**Status**: 🚧 Initial structure - extensive research and testing needed
