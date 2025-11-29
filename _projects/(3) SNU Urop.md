---
name: The Design and Fabrication of a Fully Collapsible Origami Wheel
tools: [Mechanism Design, SCM Fabrication]
image: "/assets/img/origamiwheel.png"
description: Developed a origami wheel achieving high deformation ratio so that it can be collapsed as robot thickness.
section: graduate-research
---

## The Design and Fabrication of a Fully Collapsible Origami Wheel
### ㅤ

In 2023 Summer, I worked as an undergraduate research intern at Biorobotics Lab, SNU before starting my masters program. Existing deformable wheel designs, such as complex linkages or Waterbomb origami patterns, often suffer from mechanical fragility, manufacturing difficulties, or the coupling of wheel width with diameter changes. This project aims to develop a fully foldable wheel that overcomes these limitations, ensuring structural integrity and compact storage.


<img src="/assets/img/origami_pattern.png" alt="Detection-Modules" style="width:80%;">

To maximize load-bearing capacity, I selected a radial tetrahedral origami pattern. The structure was fabricated using a composite layering technique: a fabric layer sandwiched between two PET facet layers. These layers were laser-cut and bonded via heat pressing using alignment pins, ensuring precise folding hinges. The final wheel structure is assembled by interlocking the folded facets.

<img src="/assets/img/origamiwheel_design.png" alt="Detection-Modules" style="width:80%;">

A key challenge was the physical interference between the spokes and the origami structure during folding. I designed a vertically offset linkage system with thin pins at the rotational ends. This configuration allows the links to overlap without collision, significantly reducing the thickness of the wheel when fully folded.

<img src="/assets/img/origamiwheel_fold.png" alt="Detection-Modules" style="width:80%;">

Actuating the folding mechanism required a motor inside the rotating wheel. Since commercial hollow slip rings were too large (OD > 22mm) for the design, I engineered a custom compact slip ring. By utilizing ball bearings as conductive interfaces for power transmission, I successfully delivered power to the central motor through the rotating shaft within a minimized form factor.