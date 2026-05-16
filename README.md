docs/
  ├── equipment-specifications.md
  └── process-flow-details.md
# 🍫 Chocolate Factory Layout

## Industrial Engineering Facilities Planning & Layout Design

-----

## 📋 Project Overview

This comprehensive industrial engineering project focuses on designing an **efficient and optimized facility layout for a medium-scale chocolate manufacturing plant**. The design incorporates systematic layout planning (SLP), equipment analysis, process flow optimization, and line balancing to maximize throughput while minimizing material handling costs.

**Target Capacity:** 5,000 kg/day | **Working Hours:** 8 hours/day (480 min) | **Building Footprint:** 30 m × 28 m ≈ 840 m²

-----

## 🎯 Project Objectives

✅ **Design an efficient factory layout** that maximizes throughput and minimizes material handling costs  
✅ **Analyze product specifications** and production volumes for three chocolate product lines  
✅ **Optimize process flows** with detailed time studies and cycle analysis  
✅ **Select and dimension equipment** with proper spacing and accessibility  
✅ **Apply line balancing techniques** to achieve ≥85% workstation efficiency  
✅ **Ensure GMP compliance** with quality control and food safety measures

-----

## 🍫 Product Portfolio

The factory manufactures **three main product lines:**

|Product                   |Unit Weight|Daily Volume|Dimensions      |Key Packaging           |
|--------------------------|-----------|------------|----------------|------------------------|
|**Milk Chocolate Bar**    |100 g      |2,000 kg/day|150 × 75 × 10 mm|Foil wrap + paper sleeve|
|**Dark Chocolate Truffle**|12 g/piece |1,500 kg/day|Ø 25 × 22 mm    |Gold foil wrap, boxed   |
|**Chocolate-Coated Wafer**|45 g       |1,500 kg/day|120 × 30 × 15 mm|Flow-wrap plastic       |

-----

## ⚙️ Process Flow Analysis

The production process follows an **8-stage continuous flow:**

|Stage|Process                        |Time  |Key Parameters                           |
|-----|-------------------------------|------|-----------------------------------------|
|1️⃣    |**Raw Material Receiving & QC**|—     |Sampling for quality specs               |
|2️⃣    |**Mixing & Blending**          |45 min|40–50 °C, moisture controlled            |
|3️⃣    |**Conching**                   |12 hrs|Flavor development, texture refinement   |
|4️⃣    |**Tempering**                  |30 min|Cycle: 50°C → 27°C → 31°C                |
|5️⃣    |**Moulding / Enrobing**        |20 min|31 °C, conveyor belt coating             |
|6️⃣    |**Cooling Tunnel**             |15 min|10–12 °C, controlled demoulding          |
|7️⃣    |**Packaging & Labelling**      |5 min |Automated wrap, seal, label, weight check|
|8️⃣    |**Finished Goods Storage**     |—     |18 °C, 50% RH, FIFO rotation             |

-----

## 🏭 Equipment Specifications

|Equipment                  |Qty|Capacity      |Power (kW)|Footprint (m)|
|---------------------------|---|--------------|----------|-------------|
|Mixing & Blending Vessel   |2  |500 kg/batch  |15        |2.0 × 1.5    |
|Conching Machine           |3  |1,000 kg/batch|45        |4.0 × 2.0    |
|Tempering Machine          |2  |800 kg/hr     |22        |3.5 × 1.2    |
|Bar Moulding Line          |1  |2,000 bars/hr |35        |8.0 × 1.0    |
|Chocolate Enrober          |1  |300 kg/hr     |18        |5.0 × 1.5    |
|Cooling Tunnel             |2  |500 kg/hr ea. |12        |10.0 × 1.2   |
|Flow-Wrap Packaging Machine|3  |120 pcs/min   |8         |3.0 × 1.0    |
|Truffle Depositor          |1  |150 kg/hr     |10        |2.5 × 1.0    |
|Foil Wrapping Machine      |2  |200 pcs/min   |7         |2.0 × 0.8    |
|QC Checkweigher            |3  |Inline        |1         |1.0 × 0.6    |

**Total Equipment Area:** ≈ 45.7 m²

-----

## 📐 Final Layout Design

### Layout Strategy: **U-Shape Configuration** ✓

The U-shaped layout was selected after evaluating three alternatives (Linear, U-Shape, and L-Shape) for:

- **Compact footprint** (~840 m²)
- **Receiving & dispatch adjacency** (minimal backflow)
- **Flexible multi-skilled workforce**
- **Optimal material handling efficiency**
- **Average travel distance:** 42 m between adjacent departments

### Department Allocation:

```
┌─────────────────────────────────────────────────┐
│  RECEIVING & INSPECTION (72 m²)  ────→ DISPATCH│
│        ↓                                      │
│  MIXING & BLENDING (80 m²)                    │
│        ↓                                      │
│  CONCHING (144 m²)                           │
│        ↓                                      │
│  TEMPERING (60 m²)                           │
│        ↓                                      │
│  MOULDING & ENROBING (90 m²)    PACKAGING (90 m²)
│        ↓                              ↑
│  COOLING TUNNEL (72 m²)              │
│        └──────────→─────────────────┘
│
│  QC LAB (24 m²)  |  UTILITIES (24 m²)  |  FINISHED GOODS (115 m²)
└─────────────────────────────────────────────────┘
```

**Building Dimensions:** 30 m × 28 m | **Total Area:** 771.2 m² (equipment + aisles + clearances)

-----

## ⚖️ Line Balancing Analysis

### **Moulding/Enrobing Line**

- **Workstations:** 3 WS
- **Bottleneck:** WS-2 (Cooling + Demoulding: 33 min)
- **Line Efficiency:** 77.3%
- **Recommendation:** Add one conching machine to balance WS-2

### **Packaging/Assembly Line**

- **Workstations:** 4 WS
- **Bottleneck:** WS-1 (Primary Wrapping: 10.5 min)
- **Line Efficiency:** 72.9%
- **Recommendation:** Add a second flow-wrap machine to reduce wrapping cycle time

-----

## 📊 Activity Relationship Analysis

### Material Flow (From-To Chart):

- **Zero backflow:** All material moves forward in production sequence
- **Peak throughput:** 5,000 kg/day
- **Flow path:** Receiving → Mixing → Conching → Tempering → Moulding → Cooling → Packaging → Dispatch

### Activity Relationship Codes:

- **A** = Absolutely Necessary
- **E** = Especially Important
- **I** = Important
- **O** = Ordinary Closeness
- **U** = Unimportant
- **X** = Undesirable

-----

## ✅ Quality Control & Compliance

✓ **QC Laboratory:** Centrally located with access to all production lines  
✓ **Metal Detectors:** Inline safety checks at packaging stage  
✓ **Checkweighers:** 3 units for weight verification (GMP compliance)  
✓ **Vision QC:** Automated color & shape inspection  
✓ **Temperature Control:** Cold storage at 18 °C, 50% RH for finished goods  
✓ **FIFO Rotation:** Proper stock rotation before dispatch

-----

## 🚀 Future Expansion Roadmap

The U-shaped layout design allows for **+30% capacity expansion** without disrupting existing operations:

- **Extend the top production arm eastward** to accommodate additional equipment
- **Pre-sized utilities zone** ready for increased power and cooling demands
- **Modular workstation design** enables incremental staffing increases
- **Scalable packaging line** can accommodate future product additions

-----

## 📁 Project Contents

- **`Chocolate_Factory_Layout_Complete2.pptx`** — Full presentation with visual layouts, diagrams, and detailed specifications
- **`README.md`** — Project documentation (this file)
- **`LICENSE`** — MIT License (Open for educational and professional use)
- **Supporting files:**
  - Equipment specifications & technical datasheets
  - Process flow diagrams
  - Activity relationship charts
  - Line balancing calculations
  - Material flow analysis (From-To charts)

-----

## 🛠️ Technologies & Methodologies

- **Systematic Layout Planning (SLP)** — Standard facility design framework
- **Activity Relationship Diagrams** — Departmental proximity optimization
- **Line Balancing Techniques** — Workstation efficiency analysis
- **CAD Layout Design** — Professional facility visualization
- **Material Handling Analysis** — Distance & cost optimization
- **GMP/Food Safety Standards** — Compliance-driven design

-----

## 📚 Key Deliverables

✅ Product analysis with specifications and volumes  
✅ Detailed process flow with time studies  
✅ Equipment selection and dimensioning  
✅ Activity relationship analysis  
✅ Multiple layout alternatives evaluation  
✅ **Final U-shaped layout design** (840 m²)  
✅ Line balancing for production & packaging  
✅ Quality control integration  
✅ Expansion roadmap

-----

## 👥 Project Team

**Supervised by:** Dr. Aziz Ezzat  
**Presented by:**

- Shahd Elsanet
- Abdelrahman Hatem

-----

## 📖 How to Use This Project

1. **Review the presentation** (`Chocolate_Factory_Layout_Complete2.pptx`) for visual layouts and detailed diagrams
1. **Study the equipment specifications** to understand manufacturing requirements
1. **Analyze the process flow** and production timeline
1. **Examine the final U-shaped layout** for facility arrangement
1. **Use as a reference** for chocolate manufacturing facility planning projects
1. **Apply SLP methodology** to similar industrial engineering challenges

-----

## 🎓 Educational Value

This project demonstrates:

- **Practical application** of industrial engineering principles
- **Real-world facility planning** with production constraints
- **Trade-off analysis** between space, efficiency, and cost
- **Line balancing optimization** for continuous production
- **GMP compliance integration** in manufacturing design
- **Scalability and flexibility** in facility planning

-----

## 📜 License

This project is licensed under the **MIT License** — open for educational and professional use.  
See the LICENSE file for complete terms.

-----

## 🔗 Repository

📌 **GitHub:** [Shahdelsanet249/Chocolate-Factory-Layout](https://github.com/Shahdelsanet249/Chocolate-Factory-Layout)

-----

## 📞 Questions & Support

For questions about this project, please refer to the detailed presentation and specifications included in this repository. This project serves as a comprehensive reference for industrial engineering facility planning and chocolate manufacturing operations.

-----

**Last Updated:** 2026 | **Project Type:** Industrial Engineering | **Status:** Complete ✓

-----

> **Note:** This README provides a comprehensive overview of the chocolate factory facility planning project. For detailed technical specifications, visual layouts, and step-by-step analysis, please refer to the complete PowerPoint presentation included in this repository.
