# Quiz 8 Design Research
## Part 1. Imaging Technique Inspiration
### Our chosen artwork: Piet Mondrian 'Broadway Boogie Woogie'
I find inspiration from the 9 Squares Project, a collaborative motion design experiment where artists animate abstract geometric compositions within a 3×3 grid.
The project uses squares, lines, and color rhythm to create playful yet structured motion.
I find this technique interesting and suitable for our project because it visualizes order and rhythm through geometric animation.
It helps inspiring how we can translate static grid into dynamic motion, balancing simplicity, variation, and visual energy.
<p align="center">
  <img src="https://raw.githubusercontent.com/Gina0937/quiz8-design-research/refs/heads/main/9-squares-1.gif">
</p>

## Part 2: Coding Technique Exploration
**Technique:** The top-left image shows Geometric Abstraction, defined by layered, rotated, and overlapping shapes with a flat color palette.  
I think p5.js transformation functions (`rotate()`, `push()`, `pop()`) could be tried to explore this effect.  
They might help control each shape’s angle and layering independently.  
Combined with `fill()` and `noStroke()`, this approach could potentially recreate the clean and dynamic geometric style seen in the reference.


- #### 🌀 Rotate Example
![Rotate Example](https://github.com/Gina0937/quiz8-design-research/blob/main/rotate.png)  
*This example demonstrates how the `rotate()` function in p5.js can rotate individual shapes around a pivot point, allowing angled geometric compositions similar to the reference image.*

#### 🔄 Scale Example
![Scale Example](https://raw.githubusercontent.com/Gina0937/quiz8-design-research/refs/heads/main/scale.png)  
*The `scale()` function enlarges or shrinks shapes proportionally, helping to explore size rhythm and variation inspired by the “9 Squares” animation.*

#### ↔️ Translate Example
![Translate Example](https://raw.githubusercontent.com/Gina0937/quiz8-design-research/refs/heads/main/translate.png)  
*The `translate()` function shifts the origin of the coordinate system, making it possible to position and animate shapes independently while maintaining structural balance.*

---

**Example code links:**  
- [p5.js – Rotate Example](https://p5js.org/examples/transformation-rotate/)  
- [p5.js – Scale Example](https://p5js.org/reference/p5/scale/)  
- [p5.js – Translate Example](https://p5js.org/examples/transformation-translate/)
