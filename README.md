# GCI Process Map - Interactive Visual Diagram

## ?? Overview

This repository contains an interactive visual diagram of the GCI (Green Circle Industries) Process Map, showing the complete workflow from material sourcing through collection, processing, and payment. The diagram is implemented with **Odoo ERP integration** and includes auto-animating flow visualization.

## ?? Features

- **Interactive Visual Diagram** - Complete process flow visualization
- **Odoo Integration** - Shows how the workflow maps to Odoo Operation Types (MCR, BSP, FGD)
- **Auto-Animating Flow** - Continuous looping animation showing process flow
- **Desktop Optimized** - Large, readable text and professional UI
- **Complete Process Coverage** - All 3 phases: Supply Chain, Baling & Sorting, Reporting & Payment

## ?? Quick Start

### Local Viewing
1. **Open the HTML file** in any modern web browser:
   ```
   index.html
   ```

2. **View the diagram** - The animation starts automatically and loops continuously

3. **Compare with PPTX** - Use the diagram alongside `GCI_Process Map.pptx` to understand the complete workflow

### Deploy to Vercel

#### Option 1: Deploy via Vercel Dashboard (Recommended)
1. Go to [vercel.com](https://vercel.com) and sign in with GitHub
2. Click **"Add New Project"**
3. Import your GitHub repository: `mohammed16ibraheem/GCI-Process-Map`
4. Vercel will auto-detect the settings (no build command needed for static HTML)
5. Click **"Deploy"**
6. Your site will be live at `https://gci-process-map.vercel.app` (or your custom domain)

#### Option 2: Deploy via Vercel CLI
```bash
# Install Vercel CLI
npm i -g vercel

# Navigate to project directory
cd web

# Deploy
vercel

# Follow the prompts to link your project
```

## ?? Process Flow

### Phase 1: Supply Chain
- Material Type & Source Identification
- Purchase & Collection Planning
- Material Collection & Receiving (MCR)

### Phase 2: Baling & Sorting
- Baling Process (BSP)
- Sorting Process (OCC & Printing Press Materials)
- Finished Goods Preparation (FGD)

### Phase 3: Reporting & Payment
- Monthly Reporting
- Invoice Generation
- Payment Processing (Baling + Supply Chain)

## ?? Odoo Integration

The workflow is implemented in **Odoo ERP** with three Operation Types:

- **MCR** (Material Collection & Receiving)
  - Type: Receipt
  - Sequence Prefix: MCR
  - Company: NAMMA AL ENJAZ FACTORY FOR INDUSTRY COMPANY

- **BSP** (Baling & Sorting Process)
  - Type: Internal Transfer
  - Sequence Prefix: BSP
  - Reservation Method: At Confirmation

- **FGD** (Finished Goods Delivery)
  - Type: Delivery
  - Sequence Prefix: FGD
  - Reservation Method: At Confirmation

**Product Category:** Recyclable Materials (Costing Method: Standard Price)

## ?? Files

- `index.html` - Main interactive diagram file (serves as homepage)
- `GCI_Process_Map_Visual_Diagram.html` - Original diagram file
- `vercel.json` - Vercel deployment configuration
- `README.md` - This file

## ?? Visual Elements

- **Orange boxes** - OCC Materials
- **Green boxes** - Printing Press Materials
- **Red borders** - Residue/Disposal
- **Blue circles** - Finished Goods (FG)
- **Purple badges** - Odoo Operation Types
- **Blue arrows** - Process flow direction

## ?? Material Types Covered

### Paper-Based Materials:
- OCC, NCC, DUPLEX, KRAFT, SACK, BOOKS, TISSUE, PULP, MIX WASTE, OCC CORE

### Specialized Materials:
- POLY CUP, OINP, Printing Press materials (POC, BBC White/Gray, E Flute, Magazines, etc.)

## ?? Animation

The diagram features **auto-starting, continuous looping animation** that:
- Animates arrows sequentially through the entire process
- Shows the complete workflow flow automatically
- Loops continuously for easy understanding
- No user interaction required

## ?? Usage

1. Open `GCI_Process_Map_Visual_Diagram.html` in your browser
2. Watch the automatic animation flow through the process
3. Compare with the PPTX file for detailed process understanding
4. Use the Odoo badges to understand ERP implementation mapping

## ?? Company

**NAMMA AL ENJAZ FACTORY FOR INDUSTRY COMPANY**

## ?? License

This project is part of the GCI Process Map documentation.

## ?? Related Files

- `GCI_Process Map.pptx` - Original PowerPoint process map
- Process analysis documents in parent directory

---

**Created:** February 2026  
**Last Updated:** February 12, 2026
