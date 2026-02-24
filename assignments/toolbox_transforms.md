<!-- SVG transforms: rotate, translate, and scale -->

# Personal Toolbox - Recode Vera Molnar

In this assignment, you will continue building your own library for drawing with SVG. This assignment asks you to implement SVG transforms: rotate, translate, and scale.

Your goal is to write a program that generates an SVG file that replicates one of [Vera Molnar's](https://dam.org/museum/artists_ui/artists/molnar-vera/) algorithmic artworks.

## Choose Your Artwork

You may choose to recode **any** of Vera Molnar's pieces, but here are some recommended options:

### Option 1: _Interruptions_ (1968-1969) - Recommended
<div align="center">
    <img src="./assets/interruptions.png" width="400">
</div>

A grid of lines with progressive interruption using rotation and displacement. Demonstrates transforms with increasing randomness.

[View Interruptions at DAM](https://dam.org/museum/artists_ui/artists/molnar-vera/interruptions/)

### Option 2: _(Des)Ordres_ (1974)
<div align="center">
    <img src="./assets/des_ordres.png" width="400">
</div>

Grid of squares with progressive disorder through rotation and displacement.

[View (Des)Ordres at DAM](https://dam.org/museum/artists_ui/artists/molnar-vera/des-ordres/)

### Option 3
Browse the [Vera Molnar collection at DAM](https://dam.org/museum/artists_ui/artists/molnar-vera/) and choose another piece that interests you. Many of her works demonstrate transforms beautifully.

## Transform Requirements

To recreate your chosen artwork, you will need to implement reusable program components that can represent each of these SVG transforms:
- **translate** - move elements in x and y
- **rotate** - rotate elements around a point
- **scale** - resize elements (optional for most Molnar pieces)

Your transform components should:
- Work with any SVG element representation
- Be composable (apply multiple transforms to the same element)
- Behave correctly when combined (e.g., rotate 30° then rotate -30° = no change)

## Learning Goals
- Master SVG transform composition
- Practice writing reusable, composable code components
- Understand how simple transforms create complex visual effects
- Expand your SVG toolbox library

## Deliverables

- **SVG file(s)** that replicate your chosen Vera Molnar artwork
- **One or more variations** - experiment with different parameters, transforms, or compositions
- **Your program** containing your transform library components
- **README.md** explaining:
  - How to run your program
  - Which Molnar piece you chose and why
  - Where to find your transform components
  - Any important design decisions

> _All of the above should be committed to a GitHub repository; submit the URL of this repository._

## Grading Criteria

> _So long as you attend the critique, work may be redone and resubmitted for a higher grade._

<table>
    <tr>
        <td>A</td>
        <td>
            <li>Your recreation captures the essence of the original artwork.</li>
            <li>Your variations are interesting and demonstrate creative risk-taking.</li>
            <li>Your transform components are reusable and work correctly.</li>
            <li>Your readme is clear and explains your approach.</li>
        </td>
    </tr>
    <tr>
        <td>B</td>
        <td>
            <li>One of the required components is missing or incomplete.</li>
            <li>Recreation is present but doesn't fully capture the original.</li>
        </td>
    </tr>
    <tr>
        <td>C</td>
        <td>
            <li>You did not participate in critique, or the work does not reflect your capacity.</li>
            <li>Multiple deliverables are missing or incomplete.</li>
        </td>
    </tr>
    <tr>
        <td>D</td>
        <td><li>Significant portions of the work are missing.</li></td>
    </tr>
    <tr>
        <td>F</td>
        <td><li>Work is incomplete, clearly phoned in, or not submitted.</li></td>
    </tr>
</table>

## Tips

- **Start with _Interruptions_** if you're unsure which piece to choose - it's a great showcase for transforms
- **Test your transforms individually** before combining them
- **Parameter exploration** - try different values to see how transforms affect the composition
- **Document your variations** - explain what you changed and why in your README

## Resources

- [Vera Molnar at DAM](https://dam.org/museum/artists_ui/artists/molnar-vera/) - Browse her complete collection
- [MDN: SVG transform](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/transform) - Technical reference
- Week 6 Truchet demo - Example of transform composition using string templates
