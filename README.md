# Fundamentals of Culvert Design

_A simple, practical introduction to culvert hydraulics, flow types, and design fundamentals with HY-8 examples._

---
**Mohsen Tahmasebi Nasab, PhD**  
- 🌐 [Website](https://www.hydromohsen.com/)  
- 💼 [LinkedIn](https://www.linkedin.com/in/hydromohsen/)  
- 📺 [YouTube Channel](https://www.youtube.com/@HydroMohsen)

---

## 📚 Learning Objectives

- Understand basic culvert hydraulics: Identify how culverts convey flow under a road and why headwater (upstream depth) builds up.
- Distinguish flow control types: Explain inlet control vs. outlet control, including what determines each and how they differ (supercritical vs. subcritical flow, weir/orifice behavior, etc.).
- Headwater vs. Tailwater influence: Learn how upstream (headwater) and downstream (tailwater) conditions affect culvert capacity and design.
- Appreciate real-world factors: Acknowledge the importance of culvert maintenance (debris blockage, sedimentation) on performance and safety.
Intro to design tools: Gain a basic familiarity with FHWA culvert design guidelines and how to use HY-8 software to analyze culvert performance.

## 1. Introduction to Culverts
- A culvert is a buried conduit designed to hydraulically convey surface water runoff or streamflow beneath a highway, roadway, railroad, or other embankment. Typically composed of structural materials around their full perimeter, culverts may also include bottomless designs. 
- They are distinguished from bridges unless their opening width is 10 feet or greater along the roadway centerline. Regardless of structure type, culverts are analyzed using hydraulic design principles to ensure they safely manage flow without disrupting transportation routes.

<p align="center">
  <img src="Images/Bridge%20vs%20Culvert.jpg" alt="Bridge vs Culvert" width="600"/>
</p>

**Culvert collapses** can cause major safety hazards, disrupt transportation, damage ecosystems, and require costly emergency repairs. Many road washouts during storms are directly linked to culvert blockages, under-sizing, or structural failure.

---
## 🎥 Culvert Failure to Watch"

- **"Culvert Failure - Road Washout "** (YouTube):  
  [Watch Here](https://youtube.com/shorts/J7mJAjFQG8Y?si=I3MZugXmWgXUVPAu)  
  *Real footage of road collapsing due to culvert failures during floods.*
---

## Culvert Design Criteria — Concise Checklist

> *Goal:* understand **what** each criterion means and **why** it matters for flow.  

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

## Aquatic Organism Passage (AOP) Criteria

**Goal:** Ensure fish and aquatic life can move freely through the culvert, maintaining natural stream conditions.

**Key Design Practices:**
- **Match culvert slope** to the natural stream slope.
- **Align** the culvert with the stream channel (no sharp angles).
- **Size the width** to be at least the **bankfull width** of the stream.
- **Maintain flow depth and velocity** similar to the natural channel.
- **Provide a continuous sediment bed** inside the culvert (gravel, cobble).
- **Allow sediment and debris transport** through the culvert.
- **Embed the culvert** below the streambed if possible (for natural bottom).

## Culvert Analysis — Flow Controls

At any discharge a culvert is limited by **one** of two possible control points:

| Control type | What limits the flow? | Typical barrel condition | Key variables |
|--------------|----------------------|--------------------------|---------------|
| **Inlet control** | The entrance opening behaves as a weir/orifice and chokes the flow **before** it can fill the barrel. | Barrel runs super-critical and usually *part-full*. | inlet area & shape, edge geometry, headwater depth |
| **Outlet control** | The downstream water level or barrel losses consume the available head; the barrel can’t pass what the inlet could supply. | Barrel runs sub-critical and often *full*. | tailwater elevation, barrel length/slope/roughness, entrance & exit losses |

### Understanding Inlet and Outlet Control (Simple Examples)

**Inlet Control:**  
- Imagine trying to pour water into a small funnel.  
- The size of the funnel opening limits how much water can get through — **even if the pipe underneath is huge**.
- It doesn’t matter how long or rough the pipe is; **the entrance itself** controls the flow.  
- ➔ *Inlet control = the opening is the bottleneck.*  
- **Real-world feel:** Small door on a big hallway. No matter how wide the hall, you can only get in as fast as the door lets you.

**Outlet Control:**  
- Now imagine water flowing through a long, rough garden hose.  
- The water easily gets into the hose, but the hose is so long and rough that **friction slows it down**.  
- Plus, if the hose is pointed into a bucket already full of water, the bucket’s water level **pushes back** and makes it harder for water to escape.
- ➔ *Outlet control = the whole journey (hose friction + exit conditions) limits the flow.*
- **Real-world feel:** Running on a treadmill with strong wind blowing against you — it’s not just starting that’s hard, it’s the whole trip!

---

### 📝 Quick Takeaway:
- **Inlet control:** entrance matters most.  
- **Outlet control:** barrel, roughness, tailwater, and friction matter most.

---

### Illustrative Scenarios

| Scenario | What you’d see | Why it behaves this way |
|----------|---------------|-------------------------|
| **Inlet-control example** | Shallow tailwater + steep pipe. Water shoots out freely; only the inlet submerges. Barrel is part-full. | Head loss is dominated by the entrance; barrel offers little resistance. |
| **Outlet-control example** | High tailwater or a long, corrugated pipe. Upstream pool rises until the barrel flows full or even backs up. | Energy is lost in friction & exit losses; downstream water “pushes back.” |

<p align="center">
  <a href="https://youtu.be/lbElfCcSknU?si=zLASZHqNI9iKuRhx" target="_blank">
    <img src="https://img.youtube.com/vi/lbElfCcSknU/0.jpg" alt="Understanding Inlet and Outlet Control in Culverts" width="300"/>
  </a>
</p>

<p align="center">
  👉 [Click to watch: *Understanding Inlet and Outlet Control in Culverts (Short FHWA Summary)*](https://youtu.be/lbElfCcSknU?si=zLASZHqNI9iKuRhx)

---




## 🚧 Maintenance & Real-World Issues

* **Design ≠ Done.** Culverts must be inspected and cleaned; debris, sediment—or even beaver dams—can halve the effective opening or block it entirely.  
* **Analogy:** A leaf-stuffed funnel: pour water in and it backs up, then spills everywhere. A culvert inlet clogged with sticks does the same—water ponds and can overtop the road.  
* **Real case (Oregon, Jan 2012):** Storm-driven mud blocked highway culverts, eroded the shoulder, and flooded the roadway. Field studies show small culverts (< 6 m span) are most likely to plug during major storms, leading to washouts.  
* **Design & O&M takeaway:**  
  * Include a debris allowance or trash rack where clogging is likely.  
  * Plan regular inspections, especially after big storms.  

<p align="center">
  <img src="Images/Blocked%20Culverts.png" alt="Blocked Culverts" width="700"/>
</p>

<p align="center">
  <em>Source: <a href="https://www.mdpi.com/2076-3417/11/16/7561" target="_blank">MDPI - Applied Sciences Journal</a></em>
</p>


---

## 💻 HY-8 Software Snapshot

* **What it is:** Free FHWA program that automates the inlet-control / outlet-control checks you just learned.  
* **Why it matters:** Pre-computer era = nomographs + trial-and-error; HY-8 now runs the equations instantly, tests multiple pipes, and plots performance curves.  
* **Demo outline:** enter site data → pick pipe size/shape → view headwater, outlet velocity, and roadway overtopping results → tweak and re-run.  



## 📚 References

1. **Minnesota Department of Transportation (MnDOT).**  
   *Drainage Manual: Chapter 5 – Culvert Design.*  
   Minnesota Department of Transportation, 2024.  

2. **Federal Highway Administration (FHWA).**  
   *Hydraulic Design Series No. 5 (HDS-5): Hydraulic Design of Highway Culverts.*  
   FHWA Publication No. FHWA-HIF-12-026, U.S. Department of Transportation, 2012.  

3. **Culvert Design Guidelines for Ecological Function.**  
   *Stream Simulation: An Ecological Approach to Culvert Design.*  
   U.S. Forest Service, National Technology & Development Program, Publication No. 0877 1801, 2008.


---

