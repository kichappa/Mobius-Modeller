# Hello there!
This is a repo of my work on the Möbius Modeller.

## Rotating Floor

In this script, a _building_ with rotating and resizing floors is generated. The sizes of the floor is controlled with a sine curve and the rotation is linearly mapped to the floor number. Here is the [working demo](https://mobius-08.design-automation.net/dashboard?file=https:%2F%2Fmobius.ramdon.team%2Fw1_s3_u3_demo_law_curves_exp.mob&defaultViewer=cad){:target="_blank"}.

<p align="center">
  <img src="/M%C3%B6bius%20Modeller%20-%20Example%201.png" alt="100 storey building with rotating and resizing floors."/>
</p>


<iframe width='100%' height='600px' style='border: 1px solid black;' src="https://mobius-08.design-automation.net/minimal?file=https:%2F%2Fmobius.ramdon.team%2Fw1_s3_u3_demo_law_curves_exp.mob&defaultViewer=cad"></iframe>


## Undulating Wall
This scrip generates, yes, a _wall_. The wall follows a sine curve along an arc of right angle. The wall also has direction selective thickness. You can see the [working demo](https://mobius-08.design-automation.net/dashboard?file=https:%2F%2Fmobius.ramdon.team%2FWeek1_Coding_Assignment.mob&defaultViewer=cad){:target="_blank"} here. 

More details:

- It generates an arc polyline.
- It offsets the positions along the arc outwards using a cosine Law Curve.
- It extrudes the deformed arc to form a set of vertical panels.


<p align="center">
  <img src="/M%C3%B6bius%20Modeller%20-%20Week%201.png" alt="Undulating walls with direction selective widths placed along a sine curve warped around an arc."/>
</p>

<iframe width='100%' height='600px' style='border: 1px solid black;' src="https://mobius-08.design-automation.net/minimal?file=https:%2F%2Fmobius.ramdon.team%2FWeek1_Coding_Assignment.mob&defaultViewer=cad"></iframe>asd

---
©️ kichappa, 2021-22