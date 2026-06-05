<h1 align="center">Matrix Transformation Visualizer</h1>
An interactive C++ project built with SFML that allows users to explore and understand 2D linear transformations visually and intuitively. <br>
This project combines the power of object-oriented programming with graphical rendering to animate how matrices transform vectors in a 2D coordinate space.

---
## 🌟 Key Features
### 1️. Core Matrix Operations:
 - Matrix Creation & Input
 - Transformations with OOP:
  -  ✨ Rotation
  -  ✨ Scaling
  -  ✨ Shearing
  -  ✨ Reflection
  -  ✨ Matrix Addition
  -  ✨ Matrix Subtraction
  -  ✨ Matrix Projection
    
### 2. Graphical Visualization (via SFML): 
- Grid and Axes Renderer
- Vector Drawing
- Dynamic Input Panel
- Interactive Keyboard Control
### 3. See real-time graphical feedback as transformations are applied.
### 4. Maintain a memory stack of the operations performed
---

## Visual Demo 🖥️
<div align="center">
  <img src="https://github.com/user-attachments/assets/b7fd8432-1ca8-47d8-bb4e-2ff379978e92" width="200" alt="Initial Grid with Vectors"/>
  <br/>
  <em><strong>⚙️ CONTROLS TAB :</strong> Quick-access guide for all transformations and key shortcuts.</em>
</div>
</br>
<div align="center">
  <img src="https://github.com/user-attachments/assets/e4a9a2ed-4513-41c0-8505-fa38c1572e3c" width="400" alt="Initial Grid with Vectors"/>
  <br/>
  <em><strong>📝 INPUT PANEL :</strong> Enter vectors and matrices - see them come alive on the grid instantly.</em>  
</div>
</br>
<div align="center">
  <img src="https://github.com/user-attachments/assets/27e06d6a-3bcd-4b45-82b5-6f8be8409427" width="400" alt="Initial Grid with Vectors"/>
  <img src="https://github.com/user-attachments/assets/56dbdce4-dd2e-4b16-8223-c3589797ac4b" width="400" alt="Initial Grid with Vectors"/>
  <br/>
  <em><strong>💡 HELP PANEL :</strong> Need a hint? This section gives real-time tips and input formats to guide you.</em>
</div>
</br>
<div align="center">
  <img src="https://github.com/user-attachments/assets/e3c5c5d2-d1c5-4324-abbc-79e5899cec4e" width="600" alt="Initial Grid with Vectors"/>
  <br/>
  <em><strong>🎯 GRID PANEL :</strong> Your interactive vector playground - draw, transform, and explore in real time!</em>
</div>
<br/>
<div align="center">
  <img src="https://github.com/user-attachments/assets/e341df6c-b562-4bb5-9c94-527662c6d547" width="600" alt="Adding vectors"/>
  <br/>
  <em> <strong>INPUT VECTORS :</strong> X & Y values</em>
</div>
<br/>
<div align="center">
  <img src="https://github.com/user-attachments/assets/d62b0eb9-7a02-4f95-848f-af59a02d0887" width="600" alt="Rotation"/>
  <br/>
  <em><strong>🔄 ROTATE :</strong> Spin your vectors smoothly to any desired angle.</em>
</div>
<br/>
<div align="center">
  <img src="https://github.com/user-attachments/assets/94105726-6b70-4a7e-b5f0-31ecec3945fb" width="600" alt="Shearing"/>
  <br/>
  <em><strong>🍥 SHEAR :</strong> Skew your shapes horizontally or vertically with ease.</em> 
</div>
<br/>
<div align="center">
  <img src="https://github.com/user-attachments/assets/f8d9f461-53ae-48ac-9fcf-a565ba8f51c2" width="600" alt="Scaling"/>
  <br/>
 <em><strong>📏 SCALE :</strong> Stretch or shrink vectors along the X and Y axes.</em>  
</div>
<br/>
<div align="center">
  <img src="https://github.com/user-attachments/assets/540972d6-1aa1-48e3-9be1-047fb768bb39" width="600" alt="Reflection"/>
  <br/>
<em><strong>🪞 REFLECT :</strong> Flip your vectors across the X or Y axis like a mirror reflection.</em>  
</div>
<br/>
<div align="center">
  <img src="https://github.com/user-attachments/assets/ae4dd7c7-8331-445f-9789-4c76b934bc8d" width="600" alt="Addition"/>
  <br/>
  <em><strong>➕ ADDITION :</strong> Combine two vectors instantly and see the resulting direction!</em>  
</div>
<br/>
<div align="center">
  <img src="https://github.com/user-attachments/assets/6769d307-045c-49d0-b4e2-889692a2a2d2" width="600" alt="Subtraction"/>
  <br/>
  <em><strong>➖ DIFFERENCE :</strong> Visualize the precise distance and direction between two vectors.</em>  

</div>
<br/>
<div align="center">
  <img src="https://github.com/user-attachments/assets/bad97d35-5d7e-415d-8010-1aadd7b71575" width="600" alt="Projection"/>
  <br/>
  <em><strong>✖️ PROJECTION:</strong> Instantly project one vector onto another and visualize their alignment.</em>
</div>
<br/>

---

 ## Steps to build and run the project 👨‍💻

### 🍎 macOS

```bash
# Install SFML
brew install sfml

# Clone and build
git clone https://github.com/your-username/Matrix-Transformation-Visualizer.git
cd Matrix-Transformation-Visualizer
mkdir build && cd build
cmake ..
make

# Run it!
./matrixSFML
```

### 🐧 Linux (Ubuntu/Debian)

```bash
# Install dependencies
sudo apt update
sudo apt install libsfml-dev cmake build-essential

# Clone and build
git clone https://github.com/your-username/Matrix-Transformation-Visualizer.git
cd Matrix-Transformation-Visualizer
mkdir build && cd build
cmake ..
make

# Run it!
./matrixSFML
```
### 🪟 Windows (Using MinGW or MSVC)

Install Tools:

- CMake

- SFML for Windows

- A C++ compiler (MSVC or MinGW)

Build with PowerShell:

```powershell
cd Matrix-Transformation-Visualizer
Remove-Item -Recurse -Force build
mkdir build
cd build
cmake .. -G "MinGW Makefiles"
mingw32-make

# Run the executable: 
./matrixSFML.exe
```
