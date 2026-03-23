## Overview of Final Design (w/ key CAD images)
TBD

## Description of Major Design Decisions/Changes from Phase 1
Since the completion of Phase 1 of this project, a few major decisions as well as design changes have been made by the team in order to satisfy printability and CAD requirements. 

Firstly, it was decided that the CAD model as well as the 3D-printed prototype of the adjustable iPad stand will be significantly scaled down compared to the original product. In addition, an iPhone will be used as the reference load instead of an iPad, even though the reverse-engineered product is meant to be an adjustable iPad stand. These decisions were made because the Fulton Schools 3D Print Lab has limited the max build plate size to dimensions of 250 x 210 x 210 mm, which restricts the dimensions of the device holder because some iPads have dimensions which exceed these limits. For example, the iPad Pro 13-inch has dimensions of 281.6 x 215.5 x 5.1 mm, so designing a steady holder for this model (without the possibility of the device tipping off the sides of the holder) using the 3D Print Lab would be difficult.

Secondly, it was decided that the angled support of the iPad stand will need to be designed with fillets in the angled part. The initial sketch of this component in Phase 1, which is shown in the figure below, did not include any fillets in this area and would therefore have resulted in stress singularities in the CAD/FEA model. However, it is known from finite element analysis that a common technique to prevent stress singularities in sharp corners is to add fillets. This technique will be utilized in this project in order to prevent this potential issue from occuring during the CAD testing phase.

![Phase 1 Sketch of Angled Support](https://github.com/user-attachments/assets/afd44ad9-bd02-4d22-aa63-78e97bb26810)

## Detailed Explanations of Required Analyses, Assumptions, and Results
TBD

## Discussion of Design for Assembly and 3D Printing
The assembly consists of four 3D-printed components: the stand, the iPad holder, a bolt, and a nut. The stand serves as the base structure, providing stability, while the iPad holder is designed to securely support the device at the desired angle. These two primary components are connected using the bolt, which passes through aligned holes in both the stand and the holder. The nut is then fastened onto the bolt to secure the connection, allowing the assembly to remain stable while also enabling easy adjustment or disassembly if needed. The nut and bolt system allows the holder to be “locked” at the desired position.

## Updated List of Anticipated Risks/Weaknesses to be Addressed in Prototyping
	The first risk that had to be considered in designing the stand was making sure it was not too top-heavy, or else it would tip over. The starting design for the part of the stand that holds the phone is a J-shaped piece with a height of 7 inches, a width of 4 inches, and a thickness of 0.25 inches. These measurements will give the phone enough support while still having a reasonable weight. During prototyping, this will be tested to see if any changes need to be made to the dimensions of the holder. Another risk that was found during phase one is making sure the angled base does not snap at the corner. The increased risk is due to the corner being a stress concentration, both in the FEA model and in the physical one. To remove this stress concentration, a fillet was added to the inside of the base, decreasing the amount of stress placed on that area.

