---
layout: project
title: MAE 2250
description: MAE 2250
technologies:
image:
---

# The Lanternfly Terminator

**Team:** _Bug-anators_

## Table of Contents
- [Client Design](#client-design)
- [Functional Prototype](#functional-prototype)
- [Client Report](#client-report)

---


<a id="client-design"></a>
# Client Design

**Team:** _Bug-anators_  
**Client(s):** Cornell CALS Extension / E\&J Gallo Winery / National Grape

## Problem statement

Grape farms supplying wineries and juice processors are increasingly impacted by Spotted Lanternflies (SLFs) during the growing and harvesting season. A Penn State-Cornell study found that more than 60% SLFs were harvested directly into 1.5-ton grape bins (up to 80% in some rows). Under current quality standards, a juice load may be rejected if just 1-2 insect fragments are detected in a 1,000-gram core sample. The grape vines also lose vitality after the SLF attaches to the vines. While current strategies focus on applying pesticides, they are too expensive as a constant preventive measure. Our plan focuses specifically on stopping adult SLFs from reaching and settling on vines by intercepting them at key hotspots and entry points in the vineyard.

## Impact

The NY grape industry is valued at $16.81 billion annually, but the increase in SLF infestations causes a significant decrease in this number. By keeping SLFs off grapevines pre-harvest, we reduce infestations. Once SLFs land on vines, they are difficult to control across an area and can rapidly degrade the quality of the harvest. Focusing on this issue lessens SLFs’ impact on product safety, taste, and the economic value of the harvested grapes.

### Concept: SLF Automated Scent Trap

**What it is:** Our concept is a scented (Tree of Heaven, etc.) SLF trap that attracts and eliminates them via an electric grid, adhesive, or mechanical suction trap. The device will be weather-proof and self-sufficient (power supply and SLF removal). The SLF would be collected in a section that the users can empty and switch out.

**How it would be used:**
- Set up a trap at hotspot; apply the mechanism
- Scent lures SLF away from the grapevines

**Why it’s better than the status quo:**
- Less Costly than Pesticides
- Avoids repeated harvester tool change

**End-of-semester proof-of-concept:** By the end of the semester, we aim to validate the functionality of our automated scent dispersion and elimination methods by testing flying objects similar to SLFs to get the desired response from the mechanism.

## Key risks / unknowns

- Potential ecological impact on non-target species: Our device’s mechanisms might attract and harm pollinators and beneficial predators, affecting the vineyards’ ecosystem. To derisk: we can use a scent that minimizes the harm done to pollinators and conduct small-scale field tests.
- Maintenance and Usability: Devices require routine maintenance (clear dead insects, refill chemicals, supply power) across many acres of land, thus needing additional labor to operate. To derisk, a bigger capacity can be used to reduce the required maintenance times.

## Questions for the client

Focus on questions they can answer from lived experience.

1. Is this design worth pursuing due to the complex nature of what attracts SLFs?
2. Could this design work to eliminate or minimize the amount of SLF on grape vines?
3. What scents could attract SLF better than grape vines and have minimal harm on pollinators?
4. How does one identify live hotspot locations for SLFs?
5. Can we hang this device on an existing Tree of Heaven/grape vine hotspot for SLF so we can eliminate the scent-releasing mechanism and focus on the trap/elimination method?

---

<a id="functional-prototype"></a>
# Functional Prototype



# 1. Design Documentation

## 1.1 Parts List Purchased

| Part Name | Description | Material | Source (McMaster Code or Amazon link) | Fabrication Method |
|---|---|---|---|---|
| T-Slotted Framing Rail | Single four-slot rail, 1" × 1", length = 6 ft | Aluminum | McMaster 47065T101 | Purchased & used |
| Aluminum U-Channel | 6063 aluminum, 1/16" wall, 3/8" × 5/8", length = 4 ft | Aluminum | McMaster 9001K787 | Purchased & used |
| Garden Mesh Netting | 4' × 10' fine bug netting for pest protection | Polymer mesh | mesh | Purchased but not used cause didn’t arrive on time |
| Expandable Coat Rack (Wall Hanger) | Wooden expandable peg rack, 14 hooks | Wood | l brackets | Purchased but not used cause didn’t arrive on time |
| Drive Wheels | 64 mm metal drive wheels, 6 mm inner diameter | Metal + rubber | wheel | Purchased but not used cause didn’t arrive on time |
| DC Gear Motor | 12V, 10 RPM high torque geared motor, 37 mm shaft | Metal/plastic | motor | Purchased but not used cause didn’t arrive on time |
| Corner Brackets (Set) | 2020 aluminum extrusion L-brackets with M5 bolts/nuts | Aluminum | corner brackets | Purchased but not used cause didn’t arrive on time |

## 1.2 Parts List That We Actually Used

| Part Name | Description | Material | Source (McMaster Code or Amazon link) | Fabrication Method |
|---|---|---|---|---|
| T-Slotted Framing Rail | Single four-slot rail, 1" × 1", length = 6 ft | Aluminum | McMaster 47065T101 | Purchased |
| Aluminum U-Channel | 6063 aluminum, 1/16" wall, 3/8" × 5/8", length = 4 ft | Aluminum | McMaster 9001K787 | Purchased |
| Scissor Linkage System | 8 sets of 2 × 12 planks created in a criss-cross manner with 3 pivot screws to contract and extend | Faux (Soft) Wood | TDS | Band saw, Drill press (fabricated) |
| L-brackets | ~1” × 1” L brackets | Aluminum | N/A | Spare part |
| Fasteners | 10-24 screws and nuts | Steel | N/A | Spare part |
| Driveshaft | ¼” cylindrical axle | Steel | N/A | Spare part |
| Wheel | ~2 inch diameter wheel | PLA | Filament N/A | 3D printed through the RPL |
| Wheel mount | Mounting structure to attach to framing rail | PLA | Filament N/A | 3D printed through the RPL |

## 1.2 Design Intent & Functionality

### Overview

The goal of this prototype is to create a protective enclosure for grapevines that prevents spotted lanternflies (SLFs) from reaching the crops while still allowing easy access for harvesting. The design uses a retractable mesh system supported by a rigid frame, allowing the enclosure to expand to cover the vines and contract when access is needed.

### Key Mechanisms

- **Retractable Scissor Mechanism (Top Frame)**  
  A scissor-link structure allows the system to expand and contract horizontally. This controls the mesh's motion and maintains its shape during operation.

- **Mesh Enclosure System** → Did not arrive on time for this prototype.  
  A fine insect mesh surrounds the structure, acting as a barrier to prevent SLFs from entering while still allowing airflow and light.

- **Motor + Wheel Drive System**  
  A motor connected to wheels enables the system to move or retract the mesh along the structure, reducing the need for manual operation.

- **Rigid Support Frame**  
  Aluminum vertical supports and horizontal members provide structural stability and keep the system aligned during expansion and contraction.

### Functional Description

The system operates by combining an expandable structure with a protective mesh enclosure:

- **Input:**  
  The user activates the system (manually or via motor), initiating movement in the wheel and scissor mechanisms. For our prototype, this will be done manually because we are still unsure about which motor to choose and have not ordered one yet.

- **Motion:**  
  The scissor mechanism expands or contracts, which moves the attached mesh along with it. The wheels and motor assist in guiding and controlling this motion.

- **Interaction:**  
  When expanded, the mesh fully encloses the grapevine area, preventing SLFs from entering. When contracted, the structure opens, allowing easy access for harvesting or maintenance.

- **Output:**  
  The system provides a controlled, reusable enclosure that protects crops while remaining adaptable to user needs.

## Figures

![Sketch]({{ "/assets/images/bug-1.jpg" | relative_url }}){: style="width: 600px"}

### CAD

![Sketch_CAD]({{ "/assets/images/bug-2.jpg" | relative_url }}){: style="width: 600px"}


## 1.3 Assembly Instructions

### Step-by-Step Assembly

1. Cut frame extrusions starting with 8020 bars (2 × 6 ft bars), cut each extrusion down to 2 ft lengths using the bandsaw in the machine shop. Mark each cut at 2 ft before cutting. This produces the pieces needed for the left and right rectangular frames (2 × 2 × 2 ft each).

2. Assembly the frame using L brackets, screws, and nuts, connecting the cut 2 ft extrusions on the inside corners of each frame. This forms two rigid rectangular frames.

3. Fabricate the wheel assembly (substitute parts — since amazon order did not come in time even with 1 week order processed). Since the components did not come in time, the wheel was fabricated in house using PLA material and Fusion 360.  
   a. Design and 3D print a wheel encasing to fit around the 8020 extrusion (fit with holes for the corresponding screws).  
   b. 3D print the wheel itself and print encasing components for both sides including the spacers.  
   c. Cut an aluminum shaft from spare stock using the bandsaw to serve as the wheel’s axle through the center of the wheel.  
   d. Assembly the encasing, wheel, and shaft together and mount to frame.

4. Fabricate the Scissor Link mechanism (substitution of parts which were again ordered on amazon but didn’t come yet). Since the purchased mechanism did not arrive yet, it was fabricated in-house from wooden slabs sourced from the Taylor Design Studio.  
   a. Mark and cut wood into 2 in × 12 in pieces using the bandsaw (16 pieces total).  
   b. On each slab, mark three hole locations at 1 in, 6 in, and 11 in from one end, centered on the width.  
   c. Drill press all marked holes on all 16 slabs.  
   d. Align 8 slabs in pars into X-shapes, lining up the center and then end holes.  
   e. Inset screws through the holes and fasten with nuts — this forms one scissor link row. Repeat for the renaming 8 slabs to produce a second row (one for each side of the frame).

5. Attach Scissor Linkage to Frame  
   a. Mount scissor linkage to upper frame rail. Insert a slider nut into the channel of the 8020 extrusion on the upper rail. Thread a screw through the uppermost hold of each scissor link end and into the slider nut, securing the linkage to the extrusion. Repeat this for all uppermost holes on both sides of the scissor linkage system.  
   b. Secure the linkage to the wheel side frame. On the frame that has the wheel assembly, insert an additional screw and nut through the corresponding scissor link hole and frame connection point. This fastening creates a coupling force between the wheel carriage and the frame, preventing the structure from tipping during extension and retraction.

6. Ground fixed frame to bottom rail  
   a. On the frame not housing the wheel assembly, the vertical extrusion must be secured to the bottom rail to prevent the structure from shifting (simulating the grounding into the soil). The ordered parts did not arrive so the connection was temporarily made using duct tape for this prototype.  
   b. **Note:** Replace duct tape with proper mechanical fasteners (slider nuts + screws into the 8020 channel, or a bracket) once McMaster parts arrive.

## Pictures from our assembly process!

![AssemblyPhotos]({{ "/assets/images/bug-3.jpg" | relative_url }}){: style="width: 600px"}

# 2. Design Tests

## 2.1 Testing Overview

Four different mechanisms are being tested in the design.

1. The first test is testing the scissor linkage’s structural integrity compared to the rest of the system using weights and testing the angle of tilt of the frames.
2. The second is the Wheel on a track rolling. If it were to misalign, the whole system and mesh may jam, so we need ways to prevent that and increase the efficiency of the system. The smoothness and then jammings were noted as observations.
3. The fifth is fastener security, ensuring L-brackets and bolts do not loosen. We have to torque spec them, and after every 10 cycles, we can check them for loosening. Identify how many require retightening.

## 2.2 Tests

### Test 1: Scissor-Linkage Structural Test

**Part/Mechanism Tested:**  
The system’s ability to stay intact while loads are put at the failure points of the system (this being the center of the scissor linkage system).

**What is Being Tested:**  
The structural integrity of the scissor linkage system in relation to the whole system, testing the tilt of the end frame with the wheel on it. This is needed to see if a different more structurally intact material is needed or this faux wood from the TDS can be reused for the next prototype.

**Testing Method:**  
To evaluate the stability of the scissor linkage under load, weights were incrementally added to both sides of the linkage. Specifically, equal masses were attached to each side to simulate loading conditions and test how the linkage responds to increasing force. The linkage was extended and held in position while weights of 88 g increments were applied symmetrically. At each load level, the angular deviation (tilt) of the linkage from its original plane was observed and recorded. The system was also monitored for any signs of structural failure, binding, or material stress (e.g., creaking).

**Results (Quantitative):**

| Weight (88 g each on each side of the scissor linkage) | Observations |
|---|---|
| 88 g | ~6° tilt observed |
| 176 g | ~10° tilt observed |
| 264 g | ~10° tilt, audible creaking in wood |
| 352 g | ~10° tilt, stabilized due to screw coupling |

![Sketch]({{ "/assets/images/bug-4.jpg" | relative_url }}){: style="width: 800px"}


**Conclusion / Next Iteration:**  
The scissor linkage was able to maintain functionality under increasing load; however, noticeable tilting began at relatively low weights (~88 g), and deformation plateaued around 10° at higher loads. The presence of creaking at 264 g indicates that the current wooden linkage is approaching its structural limits. While the screw coupling helped stabilize the system at higher loads, the overall stiffness of the linkage is insufficient for sustained or larger loads.

For the next iteration, the linkage should be redesigned using stronger and more rigid materials (e.g., aluminum instead of faux wood) to reduce deformation. Additionally, improving joint connections and increasing structural support along the linkage could help minimize out-of-plane motion and improve overall stability. A system where the wheels are able to make the moveable frame on the left stay upright would also need to be implemented as the tilt is mainly due to the torque of the frame.

### Test 2: Wheel-Rail System

**Part/Mechanism Tested:**  
Wheel and horizontal rail system

**What is Being Tested:**  
Smooth rolling motion and alignment along the rail without jamming or derailment

**Testing Method:**  
The system is moved along the full length of the rail multiple times. Motion is observed for interruptions, sticking, or misalignment. Time delays or stopping points are noted to evaluate the smoothness of motion.

**Results (Quantitative):**

| Iteration # moved back and forth | How many jams we had |
|---|---|
| 1 | 0 |
| 2 | 0 |
| 3 | 0 |
| 4 | 1 |
| 5 | 2 |
| 6 | 2 |
| 7 | 1 |
| 8 | 3 |
| 9 | 3 |
| 10 | 3 |

**Observations:**  
The system initially moved smoothly with no jamming in early iterations (1–3). While some jamming was observed in later iterations (up to 3 jams per cycle), the overall frequency remained relatively low compared to the number of cycles performed. Much of the jamming appeared to occur inconsistently and was likely influenced by human error during manual operation, such as uneven force or slight misalignment when moving the system back and forth.

**Conclusion / Next Iteration:**  
The wheel–rail system generally demonstrated smooth and reliable motion, with relatively minimal jamming across multiple cycles. The increase in jams in later iterations suggests some sensitivity to alignment; however, this was likely exacerbated by manual operation rather than inherent design flaws.

For the next iteration, improvements should focus on reducing sensitivity to user input by adding alignment guides or constraints to keep the system on track. Additionally, transitioning to motor-driven motion would provide more consistent movement and likely reduce jamming caused by uneven manual forces. Minor improvements, such as smoothing the rail surface or reducing friction, could further enhance performance.

### Test 3: Fastener Security

**Part/Mechanism Tested:**  
Fasteners (L-brackets, bolts, and joints)

**What is Being Tested:**  
Whether fasteners remain secure during repeated operation

**Testing Method:**  
All fasteners are tightened before testing. After ≥ 10 expansion/contraction cycles, each fastener is inspected for loosening. The number of fasteners requiring retightening is recorded.

**Results (Quantitative):**

| Iteration # moved back and forth | How many bolts unfastened |
|---|---|
| 1 | 0 |
| 2 | 0 |
| 3 | 1 |
| 4 | 1 |
| 5 | 2 |
| 6 | 2 |
| 7 | 2 |
| 8 | 3 |
| 9 | 4 |
| 10 | 4 |

**Observations:**  
Fasteners remained secure during the initial cycles, with little to no loosening observed in the first two iterations. However, as the number of cycles increased, more bolts began to loosen, reaching up to 4 loosened fasteners by iteration 9 and 10. The increase in loosening appears gradual and consistent, suggesting that repeated motion and vibration of the system contribute to fastener instability over time.

**Conclusion / Next Iteration:**  
The fasteners performed adequately during initial operation but showed increasing loosening under repeated cycling, indicating that the current fastening method is not sufficient for long-term use. While the system remained functional, the need for retightening multiple bolts suggests reduced reliability over time. For the next iteration, improvements should focus on preventing loosening under vibration. This could include using locking mechanisms such as lock nuts, washers, or thread-locking adhesive. Additionally, ensuring consistent torque during assembly and potentially redesigning joints to reduce vibration and movement at connection points could improve fastener reliability.

# 3. Success Criteria

## 3.1 Project Context

The goal of this project is to design a retractable protective enclosure that prevents spotted lanternflies (SLFs) from accessing grapevines while allowing easy expansion and contraction for harvesting. The system must be structurally stable, movable, and effective at enclosing the target area.

## 3.2 Criteria

### Criterion 1: Structural Stability

- **What it assesses:** whether the frame and scissor mechanism remain stable and do not collapse or deform during use
- **Quantitative requirement:**
  - Structure must remain upright with ≤ 5 in deflection under its own weight and during operation
  - No structural failure after 20 expansion/contraction cycles
- **How it is measured:**
  - Measure the displacement of the top frame using a ruler during operation
  - Perform repeated expansion/contraction cycles and observe deformation or failure
- **Priority:** High

### Criterion 2: Smooth motion of the system

- **What it assesses:** Whether the wheel system moves smoothly along the rail without jamming
- **Quantitative requirement:**
  - The system must travel the full rail length without derailment or jamming
  - Motion must be continuous with no stops longer than 5 seconds
- **How it is measured:**
  - Move the system along the rail and observe the motion
  - Time interruptions or sticking points
- **Priority:** High

### Criterion 3: Fastener Reliability

- **What it assesses:** Whether bolts and brackets remain secure during repeated use
- **Quantitative requirement:**
  - ≤ 10% of fasteners require retightening after 20 cycles
  - No complete fastener failure
- **How it is measured:**
  - Inspect all fasteners after cycling
  - Record number that loosened
- **Priority:** High

## 3.3 Exhibit Demonstration

**Chosen Criterion for Demo:** Smooth motion of the scissor linkage and wheel–rail system

**Demo Description:**  
The prototype will be demonstrated by performing multiple full expansion and contraction cycles along the horizontal rail. The system will be manually actuated, allowing the wheel–rail mechanism to guide the frame while the scissor linkage expands and retracts in sync. During the demonstration, the motion will be repeated several times to highlight consistency and reliability. Additionally, the time required to complete one full cycle will be recorded to provide a quantitative measure of performance.

**What the Audience Will Observe:**  
The audience will observe the structure transitioning smoothly between a fully enclosed state (protecting the grapevines) and a fully open state (allowing access for harvesting). They will see coordinated motion between the scissor linkage and the wheel–rail system, with minimal jamming or interruption. The mesh enclosure will maintain its tension and coverage throughout the motion, clearly demonstrating its ability to function as a protective barrier while remaining flexible and retractable.


---

<a id="client-report"></a>
# Client Report

## Project Context and Problem

Spotted lanternflies (SLFs) create a major problem for vineyards because they can enter grape bins during mechanical harvesting and contaminate the crop. During harvesting, studies found that up to about 60% of SLFs present on vines can be collected directly into grape bins. Even a small number of insect fragments in a sample can cause a juice load to be rejected, which creates economic loss for growers and processors.

Our client-facing problem is therefore not only how to remove SLFs after they appear, but how to prevent them from reaching the grapevines before harvest. Since mechanical harvesting does not allow for careful manual sorting during the process, the design must reduce SLF presence before grapes enter the harvesting system.

## Final Prototype Overview

Our final prototype is a retractable vineyard enclosure designed to protect grapevines from SLFs while still allowing access for harvesting and maintenance. The system uses a horizontally expanding scissor linkage connected to a wheel–rail system. When expanded, the structure supports a mesh barrier around the vines. When contracted, the enclosure opens so workers and harvesting equipment can access the vineyard row.

The main components of the prototype are:

- **Scissor linkage:** allows the enclosure to expand and contract using one primary motion
- **Mesh enclosure:** acts as the physical barrier preventing SLFs from reaching the vines
- **Wheel–rail system:** guides the moving frame during expansion and retraction
- **Rigid support frame:** keeps the structure upright and aligned
- **Fasteners and joints:** connect the frame, linkage, and moving components

<img src="assets/images/final_prot.png" width="600" />


## Design Application

In a real vineyard, this design would be placed along grapevine rows during the growing season. The enclosure would remain expanded when protection is needed, preventing SLFs from landing directly on the vines. Before harvesting or maintenance, the system could retract to allow access.

This approach focuses on prevention rather than reaction. Instead of relying only on pesticides or post-harvest sorting, the enclosure blocks SLFs before they become a contamination problem. The design also preserves airflow and sunlight, which are important for grapevine health.

## Testing Summary

We evaluated the prototype using three main tests: structural stability, wheel–rail motion, and fastener reliability.

### Test 1: Structural Stability

The scissor linkage was tested by adding weights to the center of the structure and observing tilt. The prototype began tilting under lower loads and eventually plateaued around a tilt angle of approximately 10 degrees.

This showed that the current linkage can still function, but it lacks enough stiffness for long-term outdoor use. The wooden/faux-wood linkage used in the prototype was useful for proof-of-concept testing, but a future version should use a stronger material such as Aluminum 6061.

<img src="assets/images/test_1.png" width="600" />

### Test 2: Wheel–Rail Motion

The wheel–rail system was tested through 10 expansion and contraction cycles. The system moved smoothly during the first few cycles, but jamming increased in later cycles.

This suggests that the concept works, but alignment is a major factor. Small misalignments can accumulate during repeated motion and cause the moving frame to jam. Future iterations should improve rail tolerances, add alignment guides, and use motorized actuation to create more consistent motion.

<img src="assets/images/test_2.png" width="600" />


### Test 3: Fastener Reliability

Fasteners were inspected after repeated motion cycles. The number of loosened bolts increased over time, especially in later cycles.

This showed that repeated motion and vibration can loosen the current fasteners. For a field-ready version, the design should use lock nuts, washers, thread-locking adhesive, or other locking mechanisms to improve reliability.

<img src="assets/images/test_3.png" width="600" />


## Client Recommendation

We recommend continuing development of the retractable enclosure design. The prototype successfully demonstrates the core concept: a reusable, retractable barrier that can protect grapevines from SLFs while still allowing access for harvesting.

However, the current prototype should be viewed as a proof of concept rather than a final field-ready product. The design is feasible, but it requires improvements in three main areas:

1. **Structural rigidity:** replace the current linkage material with stronger aluminum components
2. **Motion reliability:** improve wheel–rail alignment and reduce jamming
3. **Durability:** add locking fasteners and test the system under repeated outdoor use

## Next Steps

The next iteration should focus on making the system stronger, smoother, and more reliable. Specifically, we would:

- Replace the wooden scissor linkage with Aluminum 6061 or another stronger lightweight material
- Improve the wheel–rail system so the moving frame stays aligned during operation
- Add locking nuts, washers, or thread-locking adhesive to prevent fasteners from loosening
- Integrate motorized actuation for more consistent expansion and contraction
- Attach and test the mesh barrier under realistic loading and movement conditions
- Conduct small-scale field testing in vineyard conditions to evaluate performance outdoors

## Final Conclusion

Overall, the retractable enclosure is a promising prevention-based solution for reducing SLF contamination in vineyards. The prototype demonstrates that a scissor linkage and wheel–rail system can create a functional expanding and contracting barrier. While the current version needs improvements in stiffness, alignment, and fastener reliability, the design has a clear path toward becoming a scalable vineyard protection system.