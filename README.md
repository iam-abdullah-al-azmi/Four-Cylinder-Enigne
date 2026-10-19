# 3D Modelling and Assembly of an Inline Four-Cylinder Engine's Reciprocating Mechanism

## Summary

The inline four-cylinder engine is the most common layout in passenger cars because it is compact, mechanically simple and fairly smooth. Its core is the reciprocating mechanism: pistons slide in the cylinders, connecting rods link them to the crankshaft, and the crankshaft converts their straight-line motion into rotation. In a typical inline-four, the crank throws are arranged so that one cylinder fires every 180° of rotation, giving two power strokes per revolution.

In this project, I modelled this mechanism in SolidWorks (Student Version). I designed six parts individually: the piston, piston ring, crankshaft, connecting rod, connecting rod cap and piston pin. I then combined them in one assembly. For every part and for the final assembly, I produced standard orthographic and isometric views, and a section view to show the internal geometry.

The model has several limitations. It covers only the reciprocating mechanism, so the engine block, cylinder head, valve train, flywheel, bearings and lubrication system are not included. The assembly contains no bolts, bearings or other fasteners, and no manufacturing tolerances are defined. I did not run a motion study or a structural analysis, so the loads and stresses are not verified.

Future work could add the missing engine parts, apply real materials and fits, run a motion study for kinematics and balance, carry out finite element analysis of the crankshaft and connecting rod, and prepare manufacturing drawings.

## Computational Design

### 1. Piston

#### 1.1 Views

|   View    |                     Image                      |
| :-------: | :--------------------------------------------: |
| Isometric | ![Isometric](images/piston_isometric_view.JPG) |
|   Left    |      ![Left](images/piston_left_view.JPG)      |
|   Back    |      ![Back](images/piston_back_view.JPG)      |
|    Top    |       ![Top](images/piston_top_view.JPG)       |
|  Bottom   |    ![Bottom](images/piston_bottom_view.JPG)    |
|  Section  |   ![Section](images/piston_section_view.JPG)   |

#### 1.2 Feature Tree

| No  |      Name      |
| :-: | :------------: |
| 01  |  Boss Extrude  |
| 02  |  Cut Extrude   |
| 03  | Linear Pattern |
| 04  |      Dome      |
| 05  |     Fillet     |
| 06  |     Mirror     |

#### 1.3 Feature Tree Image

| No  | Image |
| :-: | :---: |
| 01  | ![Piston Feature Tree](images/piston_feature_tree.png) |

### 2. Piston Ring

#### 2.1 Views

|   View    |                        Image                        |
| :-------: | :-------------------------------------------------: |
| Isometric | ![Isometric](images/piston_ring_isometric_view.JPG) |
|   Front   |     ![Front](images/piston_ring_front_view.JPG)     |
|    Top    |       ![Top](images/piston_ring_top_view.JPG)       |
|  Section  |   ![Section](images/piston_ring_section_view.JPG)   |

#### 2.2 Feature Tree

| No  |     Name     |
| :-: | :----------: |
| 01  | Boss Extrude |

#### 2.3 Feature Tree Image

| No  | Image |
| :-: | :---: |
| 01  | ![Piston Ring Feature Tree](images/piston_ring_feature_tree.png) |

### 3. Crankshaft

#### 3.1 Views

|   View    |                       Image                        |
| :-------: | :------------------------------------------------: |
| Isometric | ![Isometric](images/crankshaft_isometric_view.JPG) |
|   Left    |      ![Left](images/crankshaft_left_view.JPG)      |
|   Right   |     ![Right](images/crankshaft_right_view.JPG)     |
|   Back    |      ![Back](images/crankshaft_back_view.JPG)      |
|   Front   |     ![Front](images/crankshaft_front_view.JPG)     |
|  Section  |   ![Section](images/crankshaft_section_view.JPG)   |

#### 3.2 Feature Tree

| No  |      Name      |
| :-: | :------------: |
| 01  |  Boss Extrude  |
| 02  |     Plane      |
| 03  |     Mirror     |
| 04  | Body Move/Copy |
| 05  |    Combine     |
| 06  |     Fillet     |

#### 3.3 Feature Tree Image

| No  | Image |
| :-: | :---: |
| 01  | ![Crankshaft Feature Tree](images/crankshaft_feature_tree.png) |

### 4. Connecting Rod

#### 4.1 Views

|   View    |                         Image                          |
| :-------: | :----------------------------------------------------: |
| Isometric | ![Isometric](images/connecting_rod_isometric_view.JPG) |
|   Left    |      ![Left](images/connecting_rod_left_view.JPG)      |
|   Front   |     ![Front](images/connecting_rod_front_view.JPG)     |
|    Top    |       ![Top](images/connecting_rod_top_view.JPG)       |
|  Bottom   |    ![Bottom](images/connecting_rod_bottom_view.JPG)    |
|  Section  |   ![Section](images/connecting_rod_section_view.JPG)   |

#### 4.2 Feature Tree

| No  |     Name     |
| :-: | :----------: |
| 01  | Boss Extrude |
| 02  | Cut Extrude  |
| 03  |    Plane     |
| 04  |    Fillet    |
| 05  |    Mirror    |

#### 4.3 Feature Tree Image

| No  | Image |
| :-: | :---: |
| 01  | ![Connecting Rod Feature Tree](images/connecting_rod_feature_tree.png) |

### 5. Connecting Rod Cap

#### 5.1 Views

|   View    |                           Image                            |
| :-------: | :--------------------------------------------------------: |
| Isometric | ![Isometric](images/connecting_rod_cap_isometric_view.JPG) |
|   Left    |      ![Left](images/connecting_rod_cap_left_view.JPG)      |
|   Front   |     ![Front](images/connecting_rod_cap_front_view.JPG)     |
|    Top    |       ![Top](images/connecting_rod_cap_top_view.JPG)       |
|  Bottom   |    ![Bottom](images/connecting_rod_cap_bottom_view.JPG)    |
|  Section  |   ![Section](images/connecting_rod_cap_section_view.JPG)   |

#### 5.2 Feature Tree

| No  |     Name     |
| :-: | :----------: |
| 01  | Boss Extrude |
| 02  |    Plane     |
| 03  | Cut Extrude  |
| 04  |    Fillet    |

#### 5.3 Feature Tree Image

| No  | Image |
| :-: | :---: |
| 01  | ![Connecting Rod Cap Feature Tree](images/connecting_rod_cap_feature_tree.png) |

### 6. Piston Pin

#### 6.1 Views

|   View    |                       Image                        |
| :-------: | :------------------------------------------------: |
| Isometric | ![Isometric](images/piston_pin_isometric_view.JPG) |
|   Front   |     ![Front](images/piston_pin_front_view.JPG)     |
|    Top    |       ![Top](images/piston_pin_top_view.JPG)       |
|  Section  |   ![Section](images/piston_pin_section_view.JPG)   |

#### 6.2 Feature Tree

| No  |     Name     |
| :-: | :----------: |
| 01  | Boss Extrude |
| 02  |   Chamfer    |

#### 6.3 Feature Tree Image

| No  | Image |
| :-: | :---: |
| 01  | ![Piston Pin Feature Tree](images/piston_pin_feature_tree.png) |

### 7. Final Design (Assembly)

#### 7.1 Views

|   View    |                        Image                         |
| :-------: | :--------------------------------------------------: |
| Isometric | ![Isometric](images/final_design_isometric_view.JPG) |
|   Left    |      ![Left](images/final_design_left_view.JPG)      |
|   Back    |      ![Back](images/final_design_back_view.JPG)      |
|   Front   |     ![Front](images/final_design_front_view.JPG)     |
|    Top    |       ![Top](images/final_design_top_view.JPG)       |
|  Bottom   |    ![Bottom](images/final_design_bottom_view.JPG)    |
|  Section  |   ![Section](images/final_design_section_view.JPG)   |

#### 7.2 Feature Tree

| No  |       Name        |
| :-: | :---------------: |
| 01  | Concentric Mates  |
| 02  | Coincident Mates |
| 03  |    Width Mates    |
| 04  |   Local Pattern   |

## Software Used

| Purpose |             Name             |
| :-----: | :--------------------------: |
| Design  | SolidWorks (Student Version) |

## Applications

- **Education:** a reference model for teaching how a slider-crank mechanism converts reciprocating motion into rotation in an internal combustion engine.
- **Design practice:** a worked example of multi-part modelling and assembly in SolidWorks.
- **Further engineering work:** a starting geometry for motion studies, finite element analysis, 3D printing of a demonstration model and animated or rendered presentations.
- **Engine development:** a base model that can be extended into a complete engine, such as a car or motorcycle powertrain.

## Limitations

- Only the reciprocating mechanism is modelled. The engine block, cylinder head, valve train, flywheel, main bearings, oil pump and intake and exhaust systems are not included.
- The assembly has no bolts, bearings or other fasteners, and no manufacturing tolerances, fits or surface finish are defined.
- No motion study or finite element analysis was done, so the kinematics, balance and stresses under combustion and inertia loads are not verified.
- Material properties and real engine dimensions were not applied to the parts.
- The assembly is a static model and does not simulate the four-stroke cycle or the firing order.

## Future Improvements

- Complete the engine with the block, head, camshaft, valves, flywheel, bearings and sump.
- Assign real materials, such as forged steel or aluminium alloy, and add tolerances and fits.
- Run a SolidWorks Motion study to check piston travel, velocity and acceleration and the 1-3-4-2 firing sequence.
- Analyse the crankshaft and connecting rod with finite element analysis under combustion and inertia loads.
- Study the secondary imbalance of the inline-four layout and add balance shafts to the model.
- Prepare detailed manufacturing drawings and a bill of materials, and render or animate the engine.

## Acknowledgements

I thank my course instructors and the Islamic University of Technology (IUT) for the SolidWorks learning opportunity. I also thank the online engineering community for the open educational resources used as references.

## References

1. J. B. Heywood, *Internal Combustion Engine Fundamentals*, 2nd ed. New York, NY, USA: McGraw-Hill Education, 2018.
2. Wikipedia, "Straight-four engine." [https://en.wikipedia.org/wiki/Straight-four_engine](https://en.wikipedia.org/wiki/Straight-four_engine)
3. Wikipedia, "Firing order." [https://en.wikipedia.org/wiki/Firing_order](https://en.wikipedia.org/wiki/Firing_order)
4. Wikipedia, "Crankshaft." [https://en.wikipedia.org/wiki/Crankshaft](https://en.wikipedia.org/wiki/Crankshaft)
5. Wikipedia, "Connecting rod." [https://en.wikipedia.org/wiki/Connecting_rod](https://en.wikipedia.org/wiki/Connecting_rod)
6. Wikipedia, "Piston ring." [https://en.wikipedia.org/wiki/Piston_ring](https://en.wikipedia.org/wiki/Piston_ring)
7. Wikipedia, "Gudgeon pin." [https://en.wikipedia.org/wiki/Gudgeon_pin](https://en.wikipedia.org/wiki/Gudgeon_pin)
8. Perkins, "Piston rings have triple purpose." [https://www.perkins.com/en_GB/aftermarket/overhaul/overhaul-components/cylinder-components/piston-rings.html](https://www.perkins.com/en_GB/aftermarket/overhaul/overhaul-components/cylinder-components/piston-rings.html)
9. FIRGELLI Automations, "Four Cylinder Motor Mechanism: How It Works, Diagram, Parts, Firing Order and Uses Explained." [https://www.firgelliauto.com/blogs/mechanisms/four-cylinder-motor](https://www.firgelliauto.com/blogs/mechanisms/four-cylinder-motor)
10. Dassault Systèmes, "SolidWorks." [https://www.solidworks.com](https://www.solidworks.com)

