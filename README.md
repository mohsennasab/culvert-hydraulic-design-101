# Fundamentals of Culvert Design

_A simple, practical introduction to culvert hydraulics, flow types, and design fundamentals with HY-8 examples._

---

**by:**  
**Mohsen Tahmasebi Nasab, PhD**  
- 🌐 [Website](https://www.hydromohsen.com/)  
- 💼 [LinkedIn](https://www.linkedin.com/in/hydromohsen/)  
- 📺 [YouTube Channel](https://www.youtube.com/@HydroMohsen)

---

## 📚 Learning Objectives

- Understand basic culvert hydraulics: Identify how culverts convey flow under a road and why headwater (upstream depth) builds up.
- Distinguish flow control types: Explain inlet control vs. outlet control, including what determines each and how they differ (supercritical vs. subcritical flow, weir/orifice behavior, etc.).
- Recognize flow regimes: Describe scenarios of unsubmerged vs. submerged flow through a culvert and the role of critical flow (critical depth) in transitions.
- Headwater vs. Tailwater influence: Learn how upstream (headwater) and downstream (tailwater) conditions affect culvert capacity and design.
- Appreciate real-world factors: Acknowledge the importance of culvert maintenance (debris blockage, sedimentation) on performance and safety.
Intro to design tools: Gain a basic familiarity with FHWA culvert design guidelines and how to use HY-8 software to analyze culvert performance.

### 1. Introduction to Culverts
- A culvert is a buried conduit designed to hydraulically convey surface water runoff or streamflow beneath a highway, roadway, railroad, or other embankment. Typically composed of structural materials around their full perimeter, culverts may also include bottomless designs. 
- They are distinguished from bridges unless their opening width is 10 feet or greater along the roadway centerline. Regardless of structure type, culverts are analyzed using hydraulic design principles to ensure they safely manage flow without disrupting transportation routes.

### Culvert Design Criteria — Concise Checklist
## MnDOT Drainage Manual – Chapter 5

# Key Culvert Design Criteria (Plain-Language Guide)

> *Goal:* understand **what** each criterion means and **why** it matters for flow.  
> *Audience:* first- or second-year civil/environmental engineering students.

| Criterion | What It Really Means | Simple Example of Its Impact on Flow |
|-----------|---------------------|--------------------------------------|
| **Design Frequency** | The size of storm (recurrence interval) a culvert is expected to handle without the road flooding—e.g., a “25-year storm.” | If you design for only a 10-year storm but a 25-year storm arrives, the culvert may be undersized and water could back up over the road. Designing for a rarer (bigger) storm means a larger (more expensive) culvert but less chance of overtopping. |
| **Allowable Headwater (HW)** | How high water is allowed to pond upstream of the culvert during the design storm. HW supplies the energy (pressure) to push flow through. | Raise the road, and you can tolerate a deeper pond (higher HW); the same culvert then passes more flow. Lower HW limits force you to pick a larger culvert so water doesn’t back up as much. |
| **Tailwater (TW)** | The water depth just downstream of the culvert. TW can act like “back-pressure” on the barrel. | If a culvert outlets into a deep river pool (high TW), the pipe may run full and switch to **outlet control**, needing more headwater to pass the same flow. With low TW (free outfall) the pipe can run partly full and often needs **less** headwater. |
| **Upstream Storage** | Any temporary ponding area upstream that can store runoff and reduce peak flow through the culvert. | A farm field depresses behind the road; by *allowing* some storage, you might keep the culvert smaller. But longer ponding could harm crops or the embankment. |
| **Outlet Velocity** | How fast water shoots out of the culvert. Velocities that are too high can erode the channel. | A steep, smooth pipe may discharge at 12 ft/s and scour the ditch. Adding a rougher material or flared outlet slows water, or you install riprap to absorb the energy. |
| **Minimum Size** | A practical lower limit so debris, ice, or sediment won’t clog the pipe. | A 6-inch pipe under a driveway will fill with leaves every fall; a 15-inch pipe is less likely to block and easier to flush. |
| **Shape / Configuration** | Choosing between circular, box, or arch barrels, and whether to use one or several. Shape affects capacity, cover requirements, and habitat. | A *box* culvert gives more width for shallow flows and fish passage, but a *round* pipe of the same area usually costs less. Multiple smaller pipes may carry less flow than one large box because debris can settle between them. |
| **Material & Roughness** | Pipe material (concrete, corrugated steel, plastic) sets structural life **and** hydraulic roughness (Manning’s *n*). Rougher pipes need more HW for the same flow. | Swap a smooth HDPE pipe (low *n*) for corrugated metal (higher *n*): flow capacity drops, headwater rises, or you must upsize the metal pipe. |
| **End Sections / Inlets** | The entrance shape—square, beveled, flared—controls how easily water gets in. | A beveled/​flared inlet acts like a funnel: for the same headwater it passes more flow than a sharp-edged pipe. Great when inlet control governs. |
| **Outlet Protection** | Measures (riprap, stilling basins) that prevent scour where water exits. | Without protection, a culvert that empties onto bare sand forms a plunge pool and undermines its own outlet. Add riprap: the rock breaks the jet and protects the bank. |
| **Site Factors (Alignment, Debris, Ice)** | Placement in plan/profile, cover depth, and local debris/ice conditions. | If you skew the culvert across the channel, flow makes a bend, drops sediment, and capacity falls over time. Aligning with the natural channel keeps flow smooth and reduces clogging. Adding a trash rack upstream stops big logs but needs maintenance. |

---

### How These Criteria Interact

* **Headwater, tailwater, shape, and roughness** together decide whether the culvert runs under **inlet control** (entrance is the bottleneck) or **outlet control** (barrel + tailwater are the bottleneck).  
* **Design frequency** and **allowable HW** set the target flow you must convey—changing either forces a change in size or number of barrels.  
* **Outlet velocity** and **site erosion potential** influence whether you add energy dissipation.  
* **Debris / ice potential** can override hydraulic efficiency—sometimes you upsize or add relief openings just so the system stays open.

**Big takeaway:** each design choice tweaks the flow-vs-headwater curve. Understanding the criteria lets you predict those shifts before you pour concrete.



### 3. Flow Control Types and Transitions
- How flow transitions from inlet control to outlet control
- Critical depth and flow regime shifts
- Visual performance curves (HW vs. Q) — when does control change?

### 4. Design Criteria Overview (Based on MnDOT/FHWA Standards)
- Design frequency selection (minor vs. major culverts)
- Allowable headwater requirements and roadway freeboard
- Tailwater estimation and its impact on flow
- Outlet velocity targets and protection strategies
- Minimum culvert sizing guidelines

### 5. Real-World Considerations
- Importance of culvert maintenance (debris, sediment, ice risks)
- Examples of culvert failures due to blockage
- Practical design adjustments for resilience

### 6. Introduction to HY-8 Software
- Overview of HY-8 and its use in culvert design
- Input parameters (culvert geometry, materials, slopes, discharges)
- How HY-8 determines inlet vs. outlet control automatically

### 7. HY-8 Live Example Walkthrough
- Simple culvert setup (circular pipe, given slope and flow)
- Explore impacts of tailwater, inlet changes, and larger flows
- How to read and interpret HY-8 output reports

### 8. Summary and Key Takeaways
- Always check both inlet and outlet control
- Headwater and tailwater both matter in design
- Maintenance is essential for culvert performance
- HY-8 simplifies analysis but good engineering judgment is critical

---

## 📌 Optional Additions if Time Allows
- Aquatic Organism Passage (AOP) design considerations
- Use of performance curves for flood resiliency planning
- Brief mention of advanced modeling (HEC-RAS, flood routing)

---
