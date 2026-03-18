# Video Prompts — fisken fanzine #2

## Format & Teknik
- **Verktyg**: Runway Gen-3, Pika Labs, eller Midjourney + Runway
- **Stil**: Premium 3D, cinematic lighting, motion design
- **Färger**: Mörk slate (#0a0a0f), ice blue (#5ac8fa), warm accents
- **Mood**: Mysterious, premium, slightly unsettling

---

## 1. HERO VIDEO — "The Void Waits"
**Längd**: 10-15 sekunder
**Användning**: Full-bleed hero background, loops

### Prompt:
```
Cinematic wide shot of an infinite ice rink stretching into darkness. 
The ice surface is perfectly smooth, reflecting subtle aurora lights in ice blue and deep purple. 
Camera slowly dollies forward, gliding over the ice. 
In the distance, a single curling stone sits perfectly still, casting a long shadow. 
Atmospheric fog rolls across the ice. 
Lighting: Dramatic side lighting with volumetric god rays. 
Color grade: Teal and orange, crushed blacks, lifted shadows. 
Style: Roger Deakins cinematography, Arri Alexa, anamorphic lenses. 
Mood: Eerie, beautiful, lonely, vast.
```

### Remotion-variant (kod):
```tsx
// Particle ice field with depth
const IceField = () => {
  // 1000 particles in 3D space
  // Camera moves through them
  // Occasional curling stone passes by
}
```

---

## 2. CHRONOSWEEP 3000 — Product Video
**Längd**: 8-12 sekunder
**Användning**: Produktkort, ersätter stillbild

### Prompt:
```
Extreme macro shot of a vintage brass and wood chronometer. 
The device has intricate clockwork mechanisms visible through glass panels. 
The hands move in slow motion, ticking backwards. 
Steam or cold breath fogs the glass slightly. 
Camera slowly orbits 360 degrees around the object. 
Lighting: Single hard light source creating dramatic shadows and brass reflections. 
Background: Deep black void. 
Surface: The device floats on a mirror-black surface with subtle ice crystal patterns. 
Style: Product photography, Apple-style lighting, teen engineering aesthetic.
```

### Remotion-variant:
```tsx
// 3D clock model rotating
// Steam particles animated
// Mechanical gears turning (reverse)
```

---

## 3. SLIDE-DON — Product Video
**Längd**: 10 sekunder
**Användning**: Produktkort, hover-to-play

### Prompt:
```
A taxidermied badger floating in black void. 
The animal is posed dynamically as if mid-slide on curling ice. 
One paw extends holding a modern minimalist brush handle (white, ergonomic design). 
Camera orbits slowly. 
Ice crystals form and melt on the fur in time-lapse. 
Lighting: Soft fill with sharp rim light creating fur detail. 
Particle effects: Dust motes float in light beams. 
Style: Surrealist product photography, Balenciaga campaign aesthetic meets nature documentary.
```

---

## 4. ÄLVDALSK REGELBOK — Product Video
**Längd**: 12 sekunder

### Prompt:
```
Ancient leather-bound book floating in darkness. 
The cover has intricate silver inlay forming curling-related runic symbols. 
The book slowly opens by itself, pages turning in phantom wind. 
Each page reveals diagrams and text that glow with ice-blue luminescence. 
Camera pushes in slowly as book opens. 
Lighting: Pages cast blue light on surroundings. 
Particles: Dust and magical sparkles float in the light. 
Style: Harry Potter aesthetic meets Scandinavian minimalism. 
Mood: Mysterious knowledge, ancient wisdom.
```

---

## 5. ISVAKTARENS TELEFON — Product Video
**Längd**: 15 sekunder
**Användning**: Phone section background

### Prompt:
```
Vintage black rotary telephone sits on pristine curling ice. 
The phone is covered in frost patterns that grow and recede in time-lapse. 
Steam rises from the receiver. 
Camera slowly pushes in. 
Suddenly, the phone begins to ring (visual only - receiver vibrates slightly). 
The rotary dial spins by itself, dialing numbers. 
Lighting: Cold, clinical with warm accent from phone's surface reflections. 
Background: Infinite ice field stretching to darkness. 
Style: Horror movie aesthetic, Kubrick symmetrical composition.
```

---

## 6. ATMOSPHERIC LOOP — "Ice Breathing"
**Längd**: 20 sekunder (seamless loop)
**Användning**: Bakgrund för stories-sektionen

### Prompt:
```
Abstract macro shot of ice crystals forming on glass surface. 
The crystals grow in intricate patterns resembling circuit boards or fingerprints. 
Water droplets freeze in time-lapse. 
Color shifts from deep blue to warm amber and back. 
Camera barely moves - subtle breathing motion. 
Style: Macro nature photography, BBC Planet Earth, scientific aesthetic. 
Mood: Frozen time, microscopic world, beautiful and cold.
```

---

## 7. FULL-BLEED SCROLL VIDEO — "The Sweep"
**Längd**: 30 sekunder
**Användning**: Ersätter full-bleed sektion, scroll-triggerad

### Prompt:
```
First-person perspective sliding on curling ice. 
Camera moves at high speed down the sheet toward the house (target circles). 
The broom/stone is visible in foreground (hands gripping). 
Ice crystals spray in slow motion. 
The house grows larger, details emerging - it's not painted lines but glowing runic symbols. 
As camera reaches the center, everything freezes and time stops. 
Camera pulls back to reveal the entire ice sheet from above - the glowing lines form an intricate pattern. 
Lighting: Dramatic overhead arena lights, volumetric fog. 
Style: POV action sequence meets cosmic revelation. 
Music sync: Build up to moment of impact, then silence.
```

---

## 8. CAR ADS — "The Last Saab"
**Längd**: 10 sekunder per bil

### Prompt (Saab):
```
Static shot of a dark blue Saab 9-5 in a snow-covered landscape at dusk. 
The car is covered in frost but headlights glow warm amber. 
Engine exhaust billows in cold air. 
Camera slowly trucks left, revealing the car's profile against a darkening sky with aurora. 
The car's reflection is perfect in the ice below (visual trick - car appears to hover over mirror surface). 
Style: Car commercial, Volvo aesthetic, Scandinavian melancholy.
```

### Prompt (Citroën):
```
Close tracking shot of a silver Citroën C5 driving on a winding forest road at night. 
Only the headlights illuminate the path ahead. 
Inside the car: faint blue glow from dashboard. 
In the back seat: barely visible shapes (curling equipment, taxidermy animals). 
Camera pulls back to aerial view showing the car as a single light moving through vast darkness. 
Style: Noir thriller, Drive (2011) aesthetic.
```

---

## 9. TRANSITION ELEMENTS
**Längd**: 2-5 sekunder varje

### "Stone to Ice"
```
Close-up of granite curling stone surface. 
Camera pushes through the stone as if it were liquid. 
Emerges on other side into ice cavern made of curling stone material. 
Seamless transition effect.
```

### "Page Turn"
```
Abstract: A page turns in extreme slow motion. 
The page is made of ice and shatters as it turns. 
Fragments form new scene. 
Style: Transition effect for editorial sections.
```

### "Particle Wipe"
```
Black screen. 
Ice-blue particles coalesce from left to right forming the next scene. 
Clean, tech aesthetic.
```

---

## 10. REMOTION-KOD TEMPLATE

```tsx
// Full-page scroll video composition
import { useScroll, useTransform } from 'framer-motion';

export const KatalogVideo = () => {
  const { scrollYProgress } = useScroll();
  
  // Transform scroll to video time
  const videoTime = useTransform(scrollYProgress, [0, 1], [0, 30]);
  
  return (
    <Sequence>
      <HeroIceField time={videoTime} />
      <ProductReveal product="chronosweep" time={videoTime} />
      <SweepPOV time={videoTime} />
      <CarReveal car="saab" time={videoTime} />
    </Sequence>
  );
};
```

---

## Genererings-Workflow:

1. **Runway Gen-3**: Använd ovanstående prompts
2. **Upscaling**: Topaz Video AI för 4K
3. **Color grading**: Matcha till webbplatsens palette i DaVinci
4. **Export**: H.265 för webb, fallback H.264
5. **Implementation**: 
   - Hero = autoplay muted loop
   - Produkter = scroll-triggered lazy load
   - Full-bleed = scroll-linked playback (scrollytelling)

---

## Mood Board Referenser:
- Teenage Engineering product videos
- Apple "Shot on iPhone" campaigns
- Studio Dumbar's kinetic type animations
- Röyksopp music videos (ice/cold aesthetic)
- Blade Runner 2049 cinematography

*Ge mig dessa videos, så bygger jag scroll-effekter som får en att tappa andan.*
