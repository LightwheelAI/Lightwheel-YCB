# Lightwheel-YCB

Lightwheel-YCB is a high-quality simulation asset benchmark built upon the [YCB Benchmarks](http://www.ycbbenchmarks.com/) - Object and Model Set. It features 125 meticulously crafted simulation-ready assets across three categories: Deformable, Articulated, and Rigid. Each asset is available in both MJCF and USD formats, ensuring compatibility with popular simulation frameworks.

---

## 🎯 Mission

Lightwheel-YCB aims to provide the embodied AI community with an easily accessible simulation asset benchmark, enabling researchers to:

- Build realistic simulation scenes using top-quality SimReady assets
- Design complex tasks based on accurate physics interactions
- Develop robust simulation frameworks
- Test sim-to-real transfer capabilities (all assets are digital twins of real YCB objects)
- Establish standardized benchmarks for evaluating AI models across simulation and real-world environments

---

## ✨ Key Features

### What We Accomplished for YCB → Now Lightwheel-YCB  

### 1. Complete Coverage – Added missing simulation assets for all YCB objects  
*Example: The original YCB contained 106 objects, with 30+ objects either missing scanned models or having low-quality scans. Lightwheel-YCB recreated high-quality SimReady assets for all 106 objects. In addition, Lightwheel-YCB introduces 19 new objects (block cubes) together with their corresponding SimReady assets.*  

### 2. Visual Enhancement – Optimized visual quality to minimize sim-to-real appearance gap  
*Example: The original YCB scanned models had significant visual defects, such as broken or uneven meshes and missing PBR materials. Lightwheel-YCB comprehensively enhanced them to achieve photo-level realism.*  

### 3. Physics Accuracy – Added appropriate physical properties to reduce sim-to-real physics gap  
*Example: The original YCB scans contained no physical parameters other than dimensions. Lightwheel-YCB supplements each asset with mass, friction, density, friction loss, damping, stiffness, and armature parameters, tailored to the object’s mode of interaction.*  

### 4. Dynamic Behaviors – Created deformable and articulated variants based on real object characteristics  
*Example: Lightwheel-YCB goes beyond rigid bodies by including 2 deformable assets and 16 articulated assets, all exhibiting physically accurate dynamic behaviors during interaction.*  

### 5. Optimized Collisions – Manually crafted collision bodies balancing accuracy, computational efficiency, and simulation stability  
*Example: The original YCB scans used visual meshes directly as collisions. Lightwheel-YCB rebuilt all collisions from scratch, balancing accuracy, computational efficiency, and stability. Notably, Lightwheel-YCB created collisions for the bottle and cap threads, enabling realistic unscrewing behaviors.*  

### 6. Quality Assurance – All assets tested through teleoperation in simulation environments  
*Example: All assets have been validated through teleoperation in Isaac Lab and MuJoCo to ensure correct interaction with robots, making them suitable for teleoperation data collection and synthetic data generation.*  

### 7. Standardized Formats – Unified USD and MJCF formats for plug-and-play use in Isaac Sim and MuJoCo  
*Example: The original YCB assets were limited to basic 3D formats (OBJ, PLY, STL). Lightwheel-YCB converts them into fully SimReady formats: USD for Isaac Sim and Isaac Lab, and MJCF for MuJoCo. Among them, 123 assets support both formats, while 2 deformable assets are USD-only.*  

## Key Results
- Transformed 106 original YCB objects (30+ previously unusable) into **125 SimReady assets**  
- Bridged the **sim-to-real gap** through enhanced visual fidelity and accurate physics modeling  
- Enabled **seamless integration** across major simulation platforms  


---

## 📥 Download

**[👉 Download Lightwheel-YCB Assets](https://lightwheel.ai/)**  

Visit our website to download the complete collection of **106 simulation-ready assets** in both USD and MJCF formats.

---

## 📊 Asset Information

| **Total Assets** | **Categories** | **Formats** | **Base Dataset** |
|------------------|----------------|--------------|-------------------|
| 125 | Deformable / Articulated / Rigid | USD (Isaac Sim) & MJCF (MuJoCo) | [YCB Benchmarks](http://www.ycbbenchmarks.com/) |

---

## 📄 License

This work is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License**.

---

## 📧 Contact

For questions or suggestions, please open an issue on GitHub or contact us:

**huang.yang@lightwheel.ai**

---

> **Note**: Star ⭐ this repository to stay updated with the latest improvements!
