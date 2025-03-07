# Bin Packing Application (Stable version V7)

This project implements a **Bin Packing Algorithm**, a combinatorial optimization problem that efficiently packs a set of items into a limited number of containers (bins) while minimizing wasted space.

## Info

- **Board size**: 280 x 207 cm

## Features

- **Automatic list updates** when modifying measurements  
- **Dynamic board addition**: A new 280 x 207 cm board is added when no space is left in the previous board  
- **Save/Load system** for preserving data  
- **Excel data import** (columns must be titled `"Largeur"`, `"Hauteur"`)  

## Changelog

### 07/03/2025
- Added save/load system  
- Added Excel data import (columns: `"Largeur"`, `"Hauteur"`)  
- 🐛 **Standby Fixed bug**: Plank list was deactivated  

### 06/03/2025
- Automatic list updates when modifying measurements  
- Added dynamic board addition (new 280 x 207 cm board when needed)  

## TODO Features

- Display an error message when entered board measurements exceed the maximum panel size  

## Installation & Usage

1. Clone the repository:  
   ```bash
   git clone <repository_url>
   cd bin_packing
