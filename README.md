# Mission Ares — interactive prototype

Ares translates technical space-agency data into clear, age-appropriate explanations and choices for young explorers, while linking back to original sources.

A browser-based prototype built with plain HTML, CSS, and JavaScript. Open `index.html` in a modern browser; no installation is required.

The opening uses the supplied Mission Ares title screen. The opening music is attempted on page load and continues until the player presses the start button; browsers that block autoplay show a sound-on control. During gameplay, normal music plays when sound is enabled and switches to the tense track when the crew status reaches the red/critical emergency state; the header button can mute or restore gameplay music. The interface is designed for portrait mobile screens, with meters kept visible. The base and mission scenes use concept art for the aerial view, central hub, commons, science and growing, and engineering.

## Included gameplay
- Arrival at the base and an autonomy decision.
- A message to Earth and an illustrative communication delay.
- Crew rest and commons choices.
- Mission 1 unfolds across two sols: a dust-storm scenario, energy-saving decisions, and a celebratory milestone when the crew preserves power for recovery.
- Robotic panel cleaning, structural inspection, and battery maintenance.
- Energy, knowledge, health, and morale meters affected by player choices.
- Mission 2 unfolds across two sols: a solar-response exercise covering radiation risk, oxygen, food, and freeze-dried reserves. The recovery stage adds a simulated crop loss, rationing, and increased use of freeze-dried food while the greenhouse recovers, followed by a mission-complete recognition of the crew's supply strategy.
- A “Where did this come from?” note explains which details are sourced science, which are fictional scenario elements, and which resource levels are gameplay scales.
- Crew-status labels reflect morale and resource pressure. The five supplied front-facing portraits remain visible in every state; subtle, state-driven brow and mouth overlays shift from concern to visible distress during alerts and emergencies. Crew members without matching portraits retain their existing emoji icons with the same expression cue.

## Science and scenario boundaries
The solar exercise is inspired by NASA DONKI record FLR 49015/3, an M6.7 flare recorded on October 8, 2026. The game does not convert flare class into a dose or claim the record confirms a particle storm. Crop loss, resource meters, and player outcomes are explicitly presented as exercise scenarios, not measurements from the event record.

The dust-storm context references NASA/JPL reporting on the 2018 global storm and the Opportunity rover. Ares Base and its crew are fictional.

## Use of AI
The project team selected the challenge and established the core idea; artificial intelligence was used as a supporting tool, not to originate the project idea. AI assisted with game code, English-language wording and narrative refinement, and generated concept-art illustrations. The science-event facts are linked to primary sources; game meters and consequences are fictional teaching scenarios, not generated measurements. AI-generated scene art is visibly labeled in the interface. The opening MP4 was supplied by the project team; whether it contains AI-generated media has not been confirmed. Check the clip before submission and add a visible AI watermark if it contains AI-generated imagery or video.

## Sources
- [NASA DONKI — FLR 49015/3](https://ccmc.gsfc.nasa.gov/DONKI/view/FLR/49015/3)
- [NOAA — Solar Radiation Storms](https://www.spaceweather.gov/phenomena/solar-radiation-storm)
- [NASA/JPL — Opportunity During the 2018 Dust Storm](https://www.jpl.nasa.gov/news/opportunity-hunkers-down-during-dust-storm)
