

# **README.md — DSLO Glossary v0.8**

## **Overview**
The **DSLO v0.8 Glossary** is the authoritative vocabulary surface for the DSLO **federated geometry system**.  
It integrates all public‑layer terms from:

- **v0.5** — machine‑dense substrate  
- **v0.6** — public‑layer substrate expansion  
- **v0.7** — system‑layer geometry  
- **v0.8** — federated geometry expansion  

This directory contains both the **machine‑native substrate** (`.json`) and the **human‑readable corridor surface** (`.md`), along with graph representations used for visualization, ontology generation, and traversal.

---

## **Contents**

### **1. glossary_v0.8.json**  
The **canonical machine‑native glossary substrate**.  
Consumed by:

- ontology generators  
- schema generators  
- registry builders  
- CLCP validators  
- manifold/operator/runtime compilers  
- graph construction pipelines  

This is the **single source of truth** for all DSLO glossary terms.

---

### **2. glossary_v0.8.md**  
The **public‑layer corridor surface**, providing:

- human‑readable glossary  
- Seven Views navigation overlay  
- relational geometry map  
- traversal diagrams  
- section‑level explanations  

Used for:

- tnopsi.com  
- Zenodo documentation  
- HF model cards  
- public‑layer navigation  

---

### **3. glossary_v0.8_graph.json**  
Graph‑structured representation of the glossary.  
Used for:

- D3.js visualization  
- HF Spaces interactive graph  
- ontology graph debugging  
- CLCP traversal  

---

### **4. glossary_v0.8_graph.dot**  
GraphViz DOT representation of glossary nodes + edges.  
Used for:

- static graph rendering  
- ontology visualization  
- manifold/operator/runtime mapping  

---

### **5. glossary_v0.8_nodes.dot**  
Node‑only DOT file.  
Used for:

- node‑level visualization  
- debugging  
- ontology node mapping  

---

### **6. d3_glossary_v0.8_graph.html**  
Interactive D3.js visualization of the glossary graph.  
Used for:

- tnopsi.com interactive glossary  
- HF Spaces  
- Zenodo supplementary materials  

---

## **Glossary Structure**
The glossary is organized into **ten geometric compartments**, each corresponding to a DSLO v0.8 system‑layer domain:

1. **Substrate Geometry**  
2. **Derived Manifolds (A, T, D, E, F, Ω)**  
3. **Relational Geometry**  
4. **Operators of Reality (OR‑Series)**  
5. **Thermodynamic Geometry**  
6. **Runtime Geometry (DSUP‑F)**  
7. **Context Window Geometry**  
8. **Simulation Geometry (IRSM, CLCP)**  
9. **Identity Geometry**  
10. **Coupling Geometry**

Each compartment contains terms from **v0.5 → v0.8**, placed into their correct geometric domains.

---

## **Dual‑Surface Architecture**

### **Public Layer (this directory)**  
Includes:

- `glossary_v0.8.md`  
- interactive graph  
- DOT files  
- D3 visualization  

### **Machine Layer (`ontology/sources/`)**  
Includes:

- `glossary_v0.8.json` (copied verbatim)  
- manifold/operator/runtime definitions  
- legality surfaces  
- registry seed  

This dual‑surface architecture is required for:

- ontology generation  
- schema projection  
- registry construction  
- CLCP validation  
- Seven Views traversal  
- tnopsi corridor integration  

---

## **Usage**

### **For Developers**
Use `glossary_v0.8.json` as input for:

- ontology generators  
- schema builders  
- registry compilers  
- graph construction tools  
- CLCP validators  

### **For Readers / Public Layer**
Use `glossary_v0.8.md` for:

- conceptual understanding  
- navigation  
- Seven Views traversal  
- tnopsi.com documentation  
- Zenodo releases  

### **For Visualization**
Use:

- `glossary_v0.8_graph.json`  
- `glossary_v0.8_graph.dot`  
- `glossary_v0.8_nodes.dot`  
- `d3_glossary_v0.8_graph.html`  

---

## **Versioning**
This glossary is part of the **DSLO v0.8 federated geometry release**.

It supersedes:

- v0.5 machine‑dense glossary  
- v0.6 public‑layer glossary  
- v0.7 public‑layer glossary  

---

## **License**
Public‑layer terms are released under the **DSLO public semantic license**.  
Substrate‑native terms remain protected and are accessible only through scientific releases.

---

## **Status**
This glossary is **lawful**, **invariant‑preserving**, **substrate‑derived**, **non‑runtime**, **non‑agentic**, and **public‑layer safe**.

