# L-System Coral and Seaweed Branching Fractal Canvas

An L-system fractal renderer with turtle graphics focused on underwater coral and seaweed themes.

## Features
- Full L-system string rewriting engine
- Turtle graphics renderer on HTML5 canvas
- 6 presets: Coral Branching, Seaweed, Kelp, Sea Fan, Bush, Barnsley Fern Variant
- Depth slider (1–7, capped per preset complexity)
- Gradient coloring: dark brown/red at base to green/cyan at tips
- Animated drawing mode (step-by-step render)
- Canvas pan (drag) and zoom (scroll wheel)
- "Random variant" button: randomizes angle slightly for organic variation
- Line length control

## Usage
Open `index.html` in any modern browser. No server required.

## L-System Presets
| Preset | Axiom | Notes |
|---|---|---|
| Coral Branching | F | Classic coral fractal |
| Seaweed | F | Alternating sub-branches |
| Kelp | X | Two-symbol complex growth |
| Sea Fan | FFFF | Symmetrical fan |
| Bush | Y | Compact multi-layer bush |
| Barnsley Variant | X | Tropical foliage variant |
