# Tiny Tapeout Verilog Project

## What is Tiny Tapeout?
[Tiny Tapeout](https://tinytapeout.com) is an **educational project** that makes it possible for students, hobbyists, and engineers to get their **digital or analog circuits manufactured** as real silicon chips — at very low cost.  
It lowers the barrier for learning and experimenting with **ASIC design and fabrication**.

---

##  Project Description

This project is part of my personal learning journey in **ASIC design and Verilog development**.  
The design was created using **Verilog HDL** and targets fabrication through the **Tiny Tapeout shuttle program**.  

### **Project Goal:**  
To implement and fabricate a simple digital design to solidify my understanding of RTL-to-GDSII workflows and ASIC hardware design.

---

##  Getting Started with This Project


---

### **Steps to Use This Project**

1.  **Edit Verilog Files**
    - Place your Verilog source code in the `src/` directory.

2.  **Update info.yaml**
    - Fill in:
        - `source_files`: list of your `.v` files.
        - `top_module`: name of your top-level module.
    - Validate the file using [Tiny Tapeout YAML migration tool](https://tinytapeout.com).

3.  **Document Your Project**
    - Edit `docs/info.md` to describe:
        - What your design does.
        - How to test it.
        - Any unique aspects of your implementation.

4.  **Write & Adapt Testbenches**
    - Place testbenches in `test/`
    - See `test/README.md` for guidance.

---

##  Building the Project
GitHub Actions are already configured.  
Once you push your changes:
1. The build flow runs **OpenLane**.
2. Your project will generate the required files for submission.

---

##  Enabling GitHub Pages
Once built, the results page will be available via GitHub Pages.

Go to **Repository Settings** > **Pages** > Enable pages from the `/docs` folder.

---

##  Resources
- [Tiny Tapeout Official Website](https://tinytapeout.com)
- [Digital Design Lessons](https://tinytapeout.com/digital-lessons/)
- [How Semiconductors Work](https://tinytapeout.com/how-semiconductors-work/)
- [Tiny Tapeout FAQ](https://tinytapeout.com/faq/)
- [Join the Community Discord](https://discord.gg/UDRY6p2)

---

##  Why This Project?
✅ Hands-on experience with ASIC flows  
✅ Practice writing Verilog for real hardware  
✅ Learn industry tools like OpenLane  
✅ Fabricate a real silicon chip for my portfolio  



