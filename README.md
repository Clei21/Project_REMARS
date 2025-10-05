# REMARS — Recycling & Manufacturing for Mars Sustainability

## 🚀 Overview
**REMARS** is an intelligent recycling system designed for long-term Mars missions.  
During multi-year expeditions, astronauts generate large amounts of inorganic waste such as packaging, textiles, and structural materials.  
Our goal is to classify, recycle, and repurpose these materials to produce 3D printing filaments and modular parts — reducing resupply needs and increasing mission autonomy.

---

## 🧩 Main Features
1. **Image-Based Waste Classification**  
   Detects and classifies materials (plastic, metal, textile, composite) using visual heuristics based on saturation, brightness, and edge detection.

2. **Recycling Pipeline Planner**  
   Generates an optimized recycling process with estimated **energy consumption** and **time per material**, supporting ISRU (In-Situ Resource Utilization) ratios.

3. **3D Part Generation (SCAD)**  
   Produces parametric designs of printable components — such as LEGO-like blocks and origami panels — directly in `.scad` format, ready for OpenSCAD printing.

4. **3D Visualization Preview**  
   Automatically renders and displays 3D previews of the generated pieces for fast visual inspection.

5. **Production Queue Simulator**  
   Simulates the scheduling of production jobs, including material type, mass, and ISRU percentage.

6. **Interactive Web Interface**  
   Built entirely with **Gradio**, allowing real-time interaction, generation, and visualization.

---

## 🌐 Live Demo
Access the live Gradio demo here:  
👉 **[https://b879567508f560d9ab.gradio.live/](https://b879567508f560d9ab.gradio.live/)**

---

## ⚙️ Tech Stack

**Languages & Libraries**
- Python 3.10  
- OpenCV (cv2)  
- NumPy  
- Pillow (PIL)  
- Matplotlib  
- Gradio  
- JSON, Tempfile, UUID, Pathlib  

**Frameworks & Concepts**
- Heuristic-based material classification  
- Energy & time optimization pipeline  
- 3D parametric modeling in `.scad`  
- Production queue simulation  
- Interactive UI with Gradio Blocks  

**Environment**
- Google Colab / Jupyter Notebook  
- Gradio Live  
- OpenSCAD  
- GitHub for version control  

---

## 🧠 System Workflow
1. **Upload Image:** The user uploads a photo of a waste object.  
2. **Classification:** The system detects the most probable material.  
3. **Recycling Plan:** An optimized recycling process is generated with energy and time estimates.  
4. **3D Generation:** The user creates `.scad` files for printable blocks or panels and visualizes the preview.  
5. **Simulation:** Jobs are added to a production queue, showing the recycling throughput and processing order.

---

## 👩‍🚀 Team
**Team:** Tambackins  
**Project:** REMARS — *Recycling & Manufacturing for Mars Sustainability*

**Members:**
- Leonor Joana Ramos Oliveira  
- Cleidiana Manoel Alves  
- Rayane Farias  
- Jonatas da Silva Santos  

---

## 🪐 Mission Statement
> REMARS integrates computer vision, 3D modeling, and automation to make future Martian missions more sustainable through intelligent waste recycling and in-situ resource utilization.

---

## 📄 License
This project was developed for the **NASA Space Apps Challenge 2025**  
and is open for educational and research purposes under the MIT License.
# Project_REMARS
