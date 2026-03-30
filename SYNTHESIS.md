# Synthesis: 20 Deranged Pretext Demos

## The Landscape

Twenty demos, six researchers, one throughline that kept surfacing like a refrain: pretext's `layoutNextLine()` is not a text layout function. It is a programmable boundary condition that converts any signal into typographic space at 60fps. The ideas here range from a graduate typography seminar compressed into a slider to a self-narrating strange loop that solves fixed-point equations every frame. What they collectively reveal is that text layout has been mistaken for a solved problem when it is actually an unexplored medium -- one that sits at the intersection of language, physics, data, the body, and computation itself.

The possibility space breaks roughly into four territories: text as historical/cultural artifact (Gutenberg Variations, Rosetta Engine, Babel Columns), text as instrument responding to live input (Phonetic Topography, Cymatics, Soma Text), text as autonomous agent with behaviors and dispositions (The Flinch, A Treated Document, Ouroboros), and text as structural analog to non-textual systems (Jacquard Loom, Mycelium Messenger, Planetary Pulse). The most interesting demos live at the borders between these territories.

## The Full 20

1. **The Gutenberg Variations** -- Drag a slider from 1440 to 2026 and watch a single article reflow through 600 years of typographic history at 60fps. *(Archivist)*
2. **Concrete Poetry Machine** -- Type a sentence and it renders as a concrete poem in the shape of its own meaning, live. *(Archivist)*
3. **The Rosetta Engine** -- Three writing systems (Latin, Arabic, CJK) reflow simultaneously in an interlocking triptych, each respecting its own typographic rules. *(Archivist)*
4. **Text Tectonics** -- Two paragraphs drift, collide, and subduct like tectonic plates, deforming at the typographic level. *(Archivist)*
5. **Phonetic Topography** -- Your voice reshapes a paragraph in real time via the Web Audio API -- the text is simultaneously a spectrogram and a transcript of what you're saying. *(Strategist)*
6. **The Panopticon Reader** -- Eye-tracking pools text toward your gaze point; text dissolves into letter-soup in your blind spots, revealing how small your window of comprehension really is. *(Strategist)*
7. **Babel Sieve** -- Words have mass proportional to their measured width and fall through oscillating slots; short words drain like sand, long words dam up. A typographic Galton board. *(Strategist)*
8. **Cymatics Typograph** -- Live audio drives Chladni nodal patterns and text flows into the calm zones, forming sound-driven mandalas of words at 60fps. *(Connector)*
9. **The Jacquard Text Loom** -- Weave text on a loom in your browser. Warp and weft are characters interlacing according to a punch card pattern you draw. *(Connector)*
10. **Mycelium Messenger** -- Words flow through a procedurally generated mycorrhizal network, branching and merging through channels whose widths are computed in real time. *(Connector)*
11. **Labanotation Text Choreography** -- Load a real Laban dance score and watch paragraphs perform the choreography, reflowing as they move because their container width changes mid-arabesque. *(Connector)*
12. **The Flinch** -- Text recoils from your cursor. The prose about trust flees from the reader at 60fps. Hold still and it cautiously creeps back. *(Contrarian)*
13. **A Treated Document** -- A page of text procedurally erases and reflows itself into new coherent sentences, inspired by Tom Phillips' *A Humument* but live and different every visit. *(Contrarian)*
14. **Babel Columns** -- Three columns in different scripts display the same passage but their layouts are adversarially coupled -- where one widens, another narrows. Same content, disagreeing bodies. *(Contrarian)*
15. **Planetary Pulse** -- Climate data rendered as flowing text whose line widths map to temperature anomalies and CO2 concentrations. The paragraph IS the data. *(Futurist)*
16. **Babel Drift** -- Multiplayer canvas where text streams in different languages merge, and an LLM generates pidgin words at the collision boundaries. Real-time glottogenesis. *(Futurist)*
17. **Soma Text** -- Biometric feedback loop: your blink rate, breathing, and micro-expressions reshape the text layout, which changes your state, which changes the text. Somatic therapy with a paragraph. *(Futurist)*
18. **Ouroboros -- Text That Reads Itself** -- A passage that describes its own layout in real time. Resize the window and it rewrites itself to remain a true self-portrait. A fixed-point equation at 60fps. *(Unhinged)*
19. **The Tower of Babel** -- Massively multiplayer physics sim where typed text in any language falls, stacks, and builds a tower that eventually collapses under its own structural weight. *(Unhinged)*
20. **The Rosetta Runtime** -- A live-coding language where the source code IS the visual output. Write "flow around circle radius 100" and the text does it. The program is its own artifact. *(Unhinged)*

## Convergences

**"Text as instrument" emerged independently from four researchers.** The Archivist called `layoutNextLine()` "an instrument nobody is playing yet." The Strategist called it "a spatial synthesizer." The Futurist said pretext turns text "from a solved problem into an unsolved instrument." The Unhinged researcher said "materials that can be shaped fast enough stop being products and start being instruments." Nobody coordinated this. They all arrived at the same word.

**Multilingual collision as a theme appeared three times.** The Archivist proposed the Rosetta Engine (scripts coexisting harmoniously), the Contrarian proposed Babel Columns (scripts antagonistically coupled), and the Futurist proposed Babel Drift (scripts merging into new languages). Same structural premise -- three different arguments about what happens when writing systems share space.

**Live audio as input showed up twice.** Phonetic Topography (Strategist) and Cymatics Typograph (Connector) both pipe microphone data into text layout, but through completely different lenses -- one is a spectrogram of your voice, the other is a Chladni plate made of words.

**The body as input channel** connects the Panopticon Reader (gaze tracking), Soma Text (biometric feedback), and Phonetic Topography (voice). All three treat the human body as a live data source that drives layout.

**Text with agency** threads through the Contrarian's entire set (The Flinch, A Treated Document) and the Unhinged researcher's Ouroboros. Text that flees, text that erases itself, text that narrates its own existence -- all depend on pretext's speed being fast enough to give text behaviors, not just positions.

## Surprises

**The Jacquard Loom connection is not a metaphor.** The Connector made a genuinely structural argument: the Jacquard loom is a per-row variable-width layout engine for thread. `layoutNextLine()` is a per-row variable-width layout engine for text. Same algorithm, different medium. The history-closing-a-loop framing is startling.

**Ouroboros is computationally unprecedented.** Text that describes its own layout and must solve a fixed-point convergence problem every frame -- where changing the description changes the layout which changes the description -- is something nobody has attempted because it sounds impossible. The Unhinged researcher's insight that the text can narrate its own failure to converge is genuinely brilliant.

**Labanotation choreography came out of nowhere.** Mapping Rudolf Laban's 1928 dance notation system to text reflow parameters is a connection nobody would predict, and the structural mapping (direction = position, level = width, duration = easing) actually holds up.

**The Contrarian's inversion of every premise** was the most productive act of disagreement in the set. Every other researcher asked "what can pretext make text do?" The Contrarian asked "what can pretext make text refuse to do?" The Flinch is the same technical demo as the Editorial Engine obstacle-avoidance, but with the emotional register completely inverted.

## The Spectrum

From most grounded to most unhinged:

1. The Gutenberg Variations -- a typography history slider
2. Concrete Poetry Machine -- semantic shape generation
3. The Rosetta Engine -- trilingual simultaneous reflow
4. A Treated Document -- procedural erasure poetry
5. Babel Columns -- adversarial multilingual layout
6. Planetary Pulse -- climate data as text topography
7. Babel Sieve -- word-mass physics sorting
8. The Jacquard Text Loom -- browser-based textile weaving with characters
9. Labanotation Text Choreography -- text performing dance scores
10. Text Tectonics -- paragraphs with geological collision physics
11. Mycelium Messenger -- words flowing through fungal network channels
12. The Flinch -- text that flees from the reader's cursor
13. Cymatics Typograph -- voice-driven Chladni word patterns
14. Phonetic Topography -- your paragraph is a spectrogram of your voice
15. The Panopticon Reader -- gaze-tracking text that performs your perception
16. Babel Drift -- multiplayer language collision birthing pidgin scripts
17. Soma Text -- biofeedback typography loop with your nervous system
18. Ouroboros -- self-describing text solving fixed-point equations at 60fps
19. The Tower of Babel -- multiplayer physics sim building and collapsing a glyph tower
20. The Rosetta Runtime -- a programming language whose source code is its own visual output

## Threads Worth Pulling

**Ouroboros (18).** This is the demo that would break the internet. A text that describes its own layout, rewrites itself when the layout changes, and narrates its own convergence failures is philosophically devastating and technically unprecedented. It is also a contained, single-page demo with no external dependencies beyond pretext itself. The fixed-point convergence problem is genuinely interesting computer science. Worth pulling because it proves something nobody thought was possible and requires nothing but pretext and cleverness.

**Phonetic Topography (5).** Voice as input is immediate, visceral, and universally accessible. The pipeline is clean: Web Audio API frequency data into `layoutNextLine()` width parameters. The Speech Recognition API for live transcription means the content IS the input IS the shape. This is the demo that makes people say "I need to build something with this library." Worth pulling because it is the shortest path from "cool demo" to "I understand why this matters."

**The Flinch (12).** Technically identical to existing obstacle-avoidance demos but emotionally inverted. Text that flees from the reader is funny, unsettling, and memorable. It requires the least new engineering of any idea on this list -- the reflow-around-cursor behavior already exists in the Editorial Engine demo. Worth pulling because the best demo is sometimes the one that reframes what you already built.

**The Jacquard Text Loom (9).** The structural argument is airtight and the visual result would be unlike anything on the internet. A punch card UI driving interlaced text weaving is historically resonant, technically novel, and visually stunning. Worth pulling because it makes the deepest argument about what `layoutNextLine()` actually is -- not a text API but a universal row-by-row distribution engine.

**Babel Drift (16).** The multiplayer angle makes this shareable, the LLM-generated pidgin at language boundaries is genuinely generative, and the bidirectional text collision zones would produce visual artifacts that look like undiscovered writing systems. Worth pulling because it is the most social demo on the list and the one most likely to produce emergent behavior nobody predicted.

## The Throughline

Every researcher, from every angle, landed on the same insight: `layoutNextLine()` is not a text layout function. It is a universal adapter between computation and space. Feed it audio and text becomes a spectrogram. Feed it physics and text becomes a geological body. Feed it biometric data and text becomes a mirror of your nervous system. Feed it dance notation and text becomes choreography. Feed it its own output and text becomes self-aware.

The single biggest realization across all twenty demos is that pretext has accidentally created a new medium. Not a better way to render text -- a way to make text behave as a real-time spatial material that responds to any input at the speed of perception. The word every researcher converged on independently was "instrument." Text has been treated as output for five thousand years. Pretext makes it a material you can play. These twenty demos are not twenty ways to show off a library. They are twenty existence proofs that text layout, unshackled from the DOM and measured in microseconds, becomes something that has no name yet -- somewhere between typography, data visualization, musical instrument, and living system. The demos that will matter most are the ones that make people feel like they are encountering text for the first time.

## Raw Materials
- [1-archivist.md](1-archivist.md) -- Historical lineages (demoscene, editorial, creative coding) and the gaps pretext fills; demos grounded in typographic history and concrete poetry
- [2-strategist.md](2-strategist.md) -- Live input streams as the strategic unlock; demos that turn voice, gaze, and physics into typographic instruments
- [3-connector.md](3-connector.md) -- Structural analogs between `layoutNextLine()` and non-text systems: looms, cymatics, mycorrhizal networks, dance notation
- [4-contrarian.md](4-contrarian.md) -- The case for adversarial text; demos where layout serves the text's autonomy rather than the reader's comprehension
- [5-futurist.md](5-futurist.md) -- Text as living substrate for planetary data, language evolution, and somatic feedback; the post-screen future
- [6-unhinged.md](6-unhinged.md) -- Self-referential strange loops, multiplayer civilization-building, and a programming language that is its own output
