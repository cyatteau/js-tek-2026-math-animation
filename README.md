# JS Tek 2026 Math Animation Demos

Slides and demos from my JS Tek 2026 talk:

**Equation to Animation: Crafting Dynamic Math Visuals on the Web**

This talk explores how small math rules can become interactive visual experiences on the web. The demos move from familiar function graphs to transforms, calculus, probability, chaos, and maps.

## Slides

- [Slides PDF](./slides.pdf)

## Demos

| Demo | Topic | Main idea | Open |
|---|---|---|---|
| 1 | Function Playground | Changing parameters changes behavior | [Open demo](./demo-1-function-playground.html) |
| 2 | Transformation Playground | Matrix changes become visible motion | [Open demo](./demo-2-transformation-playground.html) |
| 3 | Calculus Motion Lab | Limits and accumulation as motion | [Open demo](./demo-3-calculus-motion-lab.html) |
| 4 | Observable Plot | Repeated samples become a distribution | [Open demo](./demo-4-observable-plot.html) |
| 5 | Chaos Explorer | One tiny rule becomes surprising behavior | [Open demo](./demo-5-chaos-explorer-presenting.html) |
| 6 | Chicago Map Radius Explorer | Distance becomes reachability | [Open demo](./demo-6-chicago-map-radius-explorer.html) |

## Run locally

These demos are standalone HTML files.

Clone the repo, then run a local server from the project folder:

```bash
npx serve .
```

Or use the **Live Server** extension in VS Code.

A local server is especially useful for the map demo, since map tiles and browser security rules can behave differently when opening a file directly with `file://`.

## Talk framework

The demos use the **GRAPH** framework:

- **Graph** the rule
- **Respond** to input
- **Animate** change
- **Probe** relationships
- **Highlight** patterns

The math changes from demo to demo, but the interaction pattern repeats:

```text
input → rule → state → render → explain
```

## Demo stack

| Demo | Main tools |
|---|---|
| Function Playground | Chart.js |
| Transformation Playground | SVG, CSS transforms, Web Animations API |
| Calculus Motion Lab | D3.js |
| Observable Plot | Observable Plot |
| Chaos Explorer | Canvas, requestAnimationFrame |
| Chicago Map Radius Explorer | Leaflet |

## About the talk

Math on the web does not have to feel static. A formula does not have to stay on paper. A function does not have to stay as notation. A rule can become something people can move, test, inspect, and understand through interaction.

This talk shows a repeatable way to turn math rules into interactive visual experiences using JavaScript and web visualization tools.

## Author

**Courtney Yatteau**  
Developer Advocate at Esri

## Notes

This repo is meant as a conference resource and demo reference. The examples are intentionally small so they can be reused, remixed, or expanded into labs, tutorials, workshops, or experiments.
