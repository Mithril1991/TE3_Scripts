# TE3 (C#) Script Repository

## Overview
This repository contains a collection of TE3 (Tabular Editor 3) C# scripts that can be used to automate and enhance workflows when working with Analysis Services Tabular models, Power BI datasets, and related projects.

The scripts are written in C# and are designed to help developers and consultants save time by automating repetitive tasks, enforcing best practices, and improving productivity when working with TE3.

## Purpose
The goal of this repository is to:
- Provide ready-to-use scripts for common tasks in Tabular Editor 3
- Serve as a knowledge base for both internal company use and the broader BI community
- Encourage collaboration and knowledge sharing across developers

## Getting Started
1. Clone or download this repository:
   ```bash
   git clone https://github.com/your-org/te3-scripts.git
### Getting Started
2. Open Tabular Editor 3
3. Load or copy the desired script into the Advanced Scripting window
4. Run the script and review the changes

### Repository Structure
- `Scripts/` — Main C# scripts for TE3
- `Examples/` — Example usage and demonstrations
- `Docs/` — Detailed explanations of selected scripts

### Example Script
Here is a simple example that lists all measures in the current model:

    foreach (var m in Model.AllMeasures)
    {
        Output.WriteLine(m.DaxObjectName);
    }

### Audience
- Power BI developers and consultants
- BI teams working with Analysis Services Tabular
- Anyone using Tabular Editor 3 and looking to automate or extend functionality

### Contributing
We welcome contributions, but trying to keep it tidy. Keep descriptions
