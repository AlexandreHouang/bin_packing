# Bin Packing Application (Stable Version V10)

This project implements a **Bin Packing Algorithm**, a combinatorial optimization problem that efficiently packs a set of items into a limited number of containers (bins) while minimizing wasted space.

## Info

- **Board size**: 280 x 207 cm  
- **Item orientation**: The width of each item **is always placed horizontally**
- There is a **0.05 cm margin** between two adjacent planks due to a material loss of approximately 0.05 cm when the saw cuts through.

## Features

- **Dynamic board addition**: A new 280 x 207 cm board is automatically added when no space is left in the previous board  
- **Excel data import** (columns must be titled `"Largeur"`, `"Hauteur"`)  

## Changelog

### 13/03/2025
- Remove button "Sauvegarder locale" and "Chargement locale"
- Update button UI

### 10/03/2025
- Add tangram fonction
- Add a display measurement in cm on the planks
- desactived : planks list, local save & load

### 07/03/2025
- Added save/load system  
- Added Excel data import (columns: `"Largeur"`, `"Hauteur"`)  
- 🐛 **Fixed bug**: Plank list was deactivated  

### 06/03/2025
- Automatic list updates when modifying item measurements  
- Added dynamic board addition (new 280 x 207 cm board when needed)  

## TODO Features
- **Automatic list updates** when modifying item measurements  
- Display an error message when entered board measurements exceed the maximum panel size  

## Installation & Usage

1. Clone the repository:  
   ```bash
   git clone <repository_url>
   cd bin_packing
