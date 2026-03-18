# Video Prompts — fisken fanzine #2
## YEEZY / KANYE WEST EDITION

Ingen brass. Ingen steampunk. Ingen aurora. 
Bara: Concrete. Stone. Shadow. Silence.

---

## 1. HERO — "The Last Rink"
**Längd**: 15 sekunder loop

```
Wide shot of an abandoned Olympic curling stadium.
Concrete walls, brutalist architecture, brutal overhead lighting.
The ice is perfectly smooth but dusty, unused for years.
Single figure in oversized black puffer stands at the far end.
Camera slowly pushes forward through floating dust particles.
No music. Just the hum of industrial lights.
Color: Desaturated, almost black and white.
Style: Yeezy Season 1 lookbook meets abandoned Soviet stadium.
Texture: Concrete. Cold. Heavy.
```

---

## 2. CHRONOSWEEP — "Monolith"
**Längd**: 12 sekunder

```
Extreme close-up of a matte black monolith.
No buttons. No numbers. Just a single LED line that pulses slowly.
The surface is textured like cast concrete.
Camera orbits 360 degrees. 
The object floats in total darkness.
Reflection: Perfect mirror-black surface below.
Style: Rick Owens furniture meets Apple Watch Ultra.
Lighting: Single hard source from above. Sharp shadows.
Color: Black. Concrete grey. One white LED.
Sound: Low frequency drone.
```

---

## 3. SLIDE-DON — "The Relic"
**Längd**: 10 sekunder

```
A single taxidermied animal head (not cute - aggressive, raw).
Mounted on a brutalist concrete plinth.
The "brush" is just a carbon fiber rod extending from the skull.
Camera trucks past slowly. 
Dust motes in shaft of light.
Style: Damien Hirst installation meets hunting trophy.
Texture: Real fur. Raw concrete. Cold metal.
Color: Earth tones. Bone white. Shadow black.
Mood: Confrontational. Expensive. Uncomfortable.
```

---

## 4. ÄLVDALSK REGELBOK — "The Scripture"
**Längd**: 15 sekunder

```
Massive concrete book floating in void.
No leather. No decoration. Just raw concrete with carved symbols.
The pages are stone slabs.
As book opens, sand falls from the pages.
Camera pushes through falling sand.
Symbols glow faintly in single color (not rainbow - just warm amber).
Style: Brutalist architecture as object. Archeological dig.
Texture: Rough concrete. Sand. Stone.
Color: Concrete grey. Sand beige. Amber light.
```

---

## 5. ISVAKTAREN — "The Object"
**Längd**: 20 sekunder

```
Rotary phone cast in solid black concrete.
The receiver is just a heavy block.
It sits on a stainless steel pedestal.
Camera circles slowly.
Suddenly: the concrete cracks. Dust spills out.
From the cracks: warm light emerges.
Style: Anish Kapoor sculpture. Industrial decay.
Texture: Cracked concrete. Polished steel. Dust.
Color: Black. Grey. One warm light source.
Sound: Deep bass rumble. Crack. Silence.
```

---

## 6. FULL-BLEED SWEEP — "The Ritual"
**Längd**: 30 sekunder

```
POV: Walking through a concrete corridor.
Walls are raw, unfinished concrete.
Only light source: openings in ceiling creating light shafts.
Figure in all black walks ahead.
They carry something heavy (curling stone wrapped in black cloth).
Reach end of corridor: massive open space.
Hundreds of identical figures standing in grid formation.
All facing center.
Center: Single spotlight on ice.
Camera rises: aerial shot reveals perfect grid of black figures.
Style: Kanye West "Power" video. Mosh Ben Ari cinematography.
Color: Black. Concrete. One spotlight.
Sound: Heavy bass. Footsteps. Silence.
```

---

## 7. CAR AD — SAAB "The Last One"
**Längd**: 10 sekunder

```
Static shot. Abandoned concrete parking garage.
Single Saab 900 in matte black wrap.
Wheels removed. Car sits on concrete blocks.
Doors welded shut.
Camera slowly pushes in.
Reflection in puddle: upside down car.
Style: Wolfgang Tillmans photography. Post-industrial decay.
Color: Matte black. Concrete grey. Water reflection.
Text on screen (if any): Just coordinates. No words.
```

---

## 8. CAR AD — CITROËN "The Transport"
**Längd**: 12 sekunder

```
Night. Desert road. No lights except car headlights.
Citroën DS in matte sand color.
Windows blacked out.
Drives slowly past camera.
In back seat: silhouette of something large (taxidermy animal).
Car continues into darkness.
Taillights disappear.
Style: David Lynch. "Lost Highway" aesthetic.
Color: Sand. Black. Red tail lights.
Sound: Engine hum fades to silence.
```

---

## 9. ATMOSPHERIC LOOP — "The Wait"
**Längd**: 20 sekunder seamless loop

```
Extreme close-up of concrete surface.
Water slowly seeps through porous material.
Forms patterns. Evaporates. Forms again.
Time-lapse texture study.
No camera movement.
Just surface breathing.
Style: James Turrell light study meets concrete brutalism.
Color: Grey. Wet grey. Dry grey.
Mood: Oppressive. Meditative. Heavy.
```

---

## 10. TRANSITION — "The Void"
**Längd**: 5 sekunder

```
Black screen.
Sound: Deep bass drop.
Concrete cracks appear from center.
Spread outward.
Light pours through cracks.
Screen flashes white.
New scene fades in from white.
Style: Kanye West DONDA listening event.
Color: Black → White. No gradients.
Sound: Sub-bass. Crack. White noise.
```

---

## REMOTION IMPLEMENTATION

```tsx
// Minimal, brutalist composition
export const KanyeRink = () => {
  return (
    <AbsoluteFill style={{ background: '#0a0a0a' }}>
      <Video src={staticFile('concrete-rink.mp4')} />
      <AbsoluteFill style={{
        background: 'linear-gradient(180deg, transparent 0%, #0a0a0a 100%)',
      }} />
      <h1 style={{
        fontFamily: 'Helvetica Neue, sans-serif',
        fontWeight: 300,
        fontSize: '15vw',
        color: '#f5f5f7',
        letterSpacing: '-0.05em',
        position: 'absolute',
        bottom: '10%',
        left: '5%',
        margin: 0,
      }}>
        FISKEN
      </h1>
    </AbsoluteFill>
  );
};
```

---

## COLOR PALETTE

```
Background: #0a0a0a (not pure black - warm black)
Surface: #1a1a1a (concrete grey)
Accent: #f5f5f7 (off-white, not pure white)
Warm light: #ff9500 (amber, minimal use)
No neons. No rainbows. No gradients (unless subtle).
```

---

## KEY REFERENCES

- Kanye West DONDA listening events (Mercedes-Benz Stadium)
- Yeezy Season 1-8 lookbooks
- Rick Owens furniture and stores
- Tadao Ando concrete architecture
- Anish Kapoor sculptures
- "Blade Runner 2049" Wallace HQ (not the neon parts)
- Wolfgang Tillmans photography
- Mosh Ben Ari music videos

---

## WHAT TO AVOID

❌ Brass, gold, copper
❌ Steampunk gears
❌ Victorian anything
❌ Neon colors
❌ Retro-futurism
❌ "Gamer aesthetic" (RGB, angular fonts)
❌ Cyberpunk neon city
❌ Aurora borealis
❌ Steam, fog (unless minimal)

✅ Concrete, stone, dust
✅ Single light sources
✅ Heavy shadows
✅ Minimal color
✅ Brutalist architecture
✅ Expensive minimalism
✅ Silence and weight

*Ge mig dessa videos, så bygger jag en sajt som Kanye skulle vilja äga.*
