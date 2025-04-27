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

| # | Category | Key Requirements | Notes / Limits |
|---|----------|------------------|----------------|
| 1 | **Design Frequency** | *Minor culvert* (≤ 48 in dia./span): 50-yr (2 % exceedance).<br>*Entrance* culvert: 10-yr.<br>*Local/side road* (AADT < 1500): may use 25-yr.<br>*Major culvert* (> 48 in): evaluate 2- to 500-yr (or overtopping flood) with a formal **Risk Assessment**; minimum overtopping frequency depends on AADT (2- to 50-yr). | Sizing is iterative; start with existing pipe where possible. |
| 2 | **Allowable Headwater (HW)** | Center-line culverts: ≥ 1 ft freeboard below shoulder P.I.<br>Entrance culverts: no overtopping at design event nor roadway flooding at minimum overtopping event.<br>If HW / D > 1.5 → check velocity, erosion, ponding duration. | Must avoid damage to roadway, properties, traffic, culvert, and meet regulatory stage-increase limits. |
| 3 | **Upstream Storage** | If using embankment storage to reduce peak flow, verify HW criteria and embankment integrity; limit pond area/duration; secure ROW/easements; plan sediment maintenance. |  |
| 4 | **Tailwater (TW)** | Compute TW for design & check storms via channel back-water analysis or critical-depth approximation: TW ≈ (d<sub>c</sub> + D) / 2 for free outfall.<br>Account for downstream controls, adjacent water bodies, joint-probability floods. |  |
| 5 | **Outlet Velocity & Protection** | Target ≤ 6 fps (vegetation or no protection).<br>Provide riprap apron per Table 5-5 or energy dissipator if velocity > limits.<br>Maintain ≥ 2.5 fps (2-yr flow) for self-cleaning of minor culverts (unless AOP). |  |
| 6 | **Minimum Size** | Interstate / trunk highway: ≥ 24 in.<br>CSAH & local center-line: ≥ 18 in.<br>Ramps / loops / rest areas: ≥ 18 in.<br>Side culverts, median drains, entrances, non-roadway: 15–18 in (see Table 5-3). | Chosen to reduce clogging and maintenance. |
| 7 | **Shape & Configuration** | Common shapes—circular, box, arch / pipe-arch.<br>Select for cost, cover, hydraulic limits, environmental needs.<br>Multi-barrel limit: ≤ 3 barrels or 48 ft total span unless deeper analysis/CFD justifies more. | Fit barrels to channel; avoid excessive spacing; recess one barrel for low-flow/AOP if needed. |
| 8 | **Material & Roughness** | Choose for structural stability, durability, hydraulic capacity, corrosion/abrasion resistance.<br>Use MnDOT design Manning’s *n* (e.g., 0.012 for RCP; 0.024 for 2 × ½ CMP). | Document choice on culvert design form. |
| 9 | **End Sections / Inlets** | Provide apron, headwall, beveled or improved inlets as required.<br>Follow entrance-loss coefficients (*k*<sub>e</sub>) in Tables 5-4 & 5-6.<br>Install safety aprons / grates when ends lie inside the roadside clear zone. | Anchor flexible pipes against flotation; evaluate piping/buoyancy where HW high. |
|10 | **Outlet Protection** | Apply riprap class & filter per outlet velocity (Table 5-5) or select dissipator (ring, SAF basin, impact basin, etc.). |  |
|11 | **Site Criteria** | Align culvert with natural channel; keep ends outside clear zone or protect with safety treatments.<br>Respect min/max cover; assess debris & ice potential; provide relief openings or racks as needed.<br>Plan for multiple-use culverts and AOP (bankfull width, embedded barrel) when required. |  |
|12 | **Analysis Tools** | Always check both inlet & outlet control; develop rating/performance curves for major culverts.<br>Tools: HY-8, HEC-RAS, nomographs, hand calcs. |  |

> **Rule of Thumb:** Size for the higher HW of inlet vs. outlet control, keep the road dry at design flow, manage velocities and blockage risk, and match culvert geometry to site, regulatory, and maintenance needs.


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
