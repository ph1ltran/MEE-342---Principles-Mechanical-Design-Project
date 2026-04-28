## Fabrication Details:
Number of Parts: 2

Units: inches

Dimensions (WxLxH):

Support: 6x6x7

Holder: 6x2x3

Infill Density: 100%

Color: Grey

Number of Reprints: None

## Assembly Procedure:
1. Align the hole of the device holder between the two holes of the angled support. Ensure that the holder has the correct orientation and is facing the right direction.

2. Insert the threaded bolt through the hole, joining the holder to the support.

3. Once the bolt has been completely inserted, thread the wingnut onto the end of the bolt and tighten until the holder is no longer loose and its position remains fixed.

4. To change the holder’s position, simply loosen the wingnut to adjust the position before tightening the wingnut once again.


## Assembly Challenges:
The first challenge encountered in the assembly process was exporting the CAD model to an STL file as required by the FSE 3D Print Lab. Since the original CAD model was designed using the student version of ANSYS DesignModeler in order to facilitate the FEA procedures in Phase 2, exporting to an STL file was initially not an option. Multiple remedies to this obstacle were considered, such as transferring the model over to SpaceClaim for export or finding individuals with the full version of ANSYS who could then export the model to an STL file. Eventually, it was decided to redesign the model in SolidWorks while referencing the ANSYS model for the original design dimensions. This allowed the model to finally be exported to an STL file for 3D printing.

The second challenge encountered was that the bolt was not able to be smoothly inserted into the hole joining the holder to the support, due to insufficient tolerance in the dimensions of the original design. However, this turned out to not be a significant problem, because applying sufficient force allowed the bolt to be completely inserted while firmly securing the holder to the support with the tightening of a wingnut.

## Test Procedures, Results, and Interpretation:
After assembling the 3D printed prototype, several different loads were applied to the structure in order to analyze its functionality. Not only was it able to withstand the weight of an iPhone, but also that of an iPad despite the decision to reduce its dimensions and change the intended load in Phase 2 of this project. The prototype is also capable of providing multiple viewing angles by simply loosening or tightening the wingnut and changing the position of the holder, as intended.

## Comparison with Phase 2 Predictions:
When discussing the risks associated with the stand, we were worried about the stand being too top-heavy and tipping. This was not an issue, since the material used to 3-D print was much sturdier than we anticipated. Although it was designed to hold a phone, it can successfully hold the weight of an iPad without tipping and without the bolt failing. We did not have to redesign the size of any part of the stand; they all worked as anticipated. The assessment of the factor of safety also seems accurate, since we tested the stand with heavier weights than the iPhone, and it did not tip or break.

## Detailed Discussion of Failures, Mistakes, and Surprises:
As mentioned previously, one surprise during the project was that the student version of ANSYS did not allow exporting the CAD model to an STL file. Fortunately, redesigning the model in SolidWorks solved this problem and allowed the project to proceed onwards with 3D printing. Another surprise happened after assembling the model and testing what it could hold. The material was much stronger than expected, and it was able to withstand more weight than was assumed.

## List of Design Changes for a Hypothetical “Version 2”:
If a second iteration of this project was run, some design changes/decisions that would be implemented in the future are:

1. Creating the model in SolidWorks first, then importing into ANSYS to avoid dealing with the issue of exporting to STL for 3D printing

2. The part of the stand that holds the phone should have a hole in the bottom to allow people to charge their phone while it's on the stand

3. The lip of the stand should be decreased in size because it blocks a lot of the phone screen. We were worried about the phone falling off the stand, but seeing how it functions, the large size of the lip is unnecessary

4. In general, the width of most parts of the stand could probably be decreased slightly to reduce the amount of material used

## Understanding of a Real World Hinged Device
In a device such as a laptop or adjustable phone stand, many different companies use different methods to achieve a self adjustable position. The most common design is frictional hinged rotation. This method uses a resistive torque to counteract any gravitational force or force applied from the weight of a phone. Inside the hinge, a central shaft is connected by two separate rotating bodies, while a series of frictional elements such as rubber, washers or clutching plates are compressed together from a loading. The compression then allows for a sort of rotating resistance, which can allow the hinge to move at a specified angle.

<img width="1093" height="575" alt="Example Laptop Hinge" src="https://github.com/user-attachments/assets/d38ccc0e-e680-447a-b2dd-18ec0bdd8ed4" />

The internal structure of a hinge (like the one in the image above) generally includes a cylindrical housing, a hardened steel shaft, friction components, and mounting brackets that attach to the device. The friction force is controlled by material selection and the amount of normal force applied between the contact surfaces. Materials such as stainless steel, brass, and polymer inserts are commonly used to balance durability, smooth motion, and wear resistance. In more advanced designs, additional elements such as torsion springs or damping systems may be included to improve performance, especially in heavier devices like laptops where maintaining screen position is critical.

From a mechanical perspective, the hinge operates by balancing applied torque with internal frictional resistance. When a user opens or adjusts the device, the applied torque exceeds the frictional torque, allowing rotation. Once the external force is removed, the friction within the hinge prevents further motion, effectively holding the device in position.

Hinges must also meet strict design requirements, including compact size, long-term durability, and consistent performance over thousands of cycles. Over time, as next-generation computing devices become increasingly thinner in order to satisfy consumer demands, hinge designs have become increasingly complex with smaller diameters and volume to meet size constraints.  
