# FOVisor (Field of View Visualizer)

**A visualization tool for designing multi-sensor arrays.**

This JavaScript app allows engineers and hobbyists to visualize overlapping fields of view (FOV) for cameras and sensors. It's useful when designing arrays of multiple overlapping sensors, such as RGB and depth sensors, where determining the precise overlap area at varying depths is critical.

#### 🚀 [Run the App Live](https://foleyj.github.io/FOVisor/)

---

## Key Features
* **Real-time Visualization:** Visualizes sensor frustums and 2D coverage areas on an HTML5 Canvas.
* **Overlap Calculation:** Automatically calculates the percentage of overlap between multiple sensors.
* **Dynamic Adjustments:**
    * **Depth:** Adjust the target distances and zoom to see how the overlap changes (e.g., from 0.4m to 4m).
    * **FOV & Aspect Ratio:** Configure individual sensor parameters (horizontal/vertical FOV, aspect ratio).
    * **Offsets:** Move sensors horizontally or vertically relative to the origin.
* **Visual Aids:** Toggle grids, diagonal FOV circles, and frustum triangles to assist with layout planning.

## How to Use
1.  **Launch the App:** Click the [Live Link](https://foleyj.github.io/FOVisor/).
2.  **Configure Sensors:** Use the control panel to enable/disable up to 4 sensors.
3.  **Adjust Parameters:** Input your sensor specifications (Aspect Ratio, FOV in degrees, Offset in cm).
4.  **Analyze Coverage:** Use the "Depth" slider to visualize effective coverage at different distances. The "Overlap" section will display the shared surface area.

## Technical Details
* **Core:** Vanilla JavaScript (ES5+)
* **Rendering:** HTML5 Canvas API (2D Context)
* **No Dependencies:** Lightweight and runs entirely in the browser.

## Author
**Jim Foley**
* [Portfolio](https://jimfoley.net) 
* [LinkedIn Profile](https://www.linkedin.com/in/jimfoley3/)
