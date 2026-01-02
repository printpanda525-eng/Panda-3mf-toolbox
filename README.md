# Panda 3MF Toolbox

**Panda 3MF Toolbox** is a lightweight Blender add-on for importing and exporting **3MF files** with correct real-world scale in millimeters.

This add-on provides a simple and reliable 3MF workflow inside Blender, focused on scale accuracy and compatibility with modern slicers.

This add-on does not modify Blender units or scene scale and works directly with millimeter-accurate data.


---

## Features

- Import 3MF files into Blender
- Export 3MF files with correct millimeter scale
- Quick export workflow using the current .blend file location
- Designed for real-world 3D printing workflows

---

## Typical Use Case

1. Import or model geometry in Blender
2. Verify object size
3. Export as 3MF
4. Open the file in your preferred slicer

---

## Free vs Accurate Version


| Feature | Panda 3MF Toolbox (Free) | Panda 3MF Accurate Toolbox |
|------|--------------------------|----------------------------|
| 3MF Import / Export | ✔ | ✔ |
| Correct millimeter scale | ✔ | ✔ |
| Batch Export (Plates) | ✖ | ✔ |
| Virtual Build Plate | ✖ | ✔ |
| Transform Tools | Limited | ✔ |
| Real Size Measurements | ✔ | ✔ |
| Advanced Printing Workflow | ✖ | ✔ |

The Free version focuses on reliable 3MF import and export with correct real-world scale.
Advanced production and batch workflows are available in the Accurate version.

<div align="center">

<img src="images/3mf-toolb.png" width="420" />
&nbsp;&nbsp;&nbsp;
<img src="images/accurate-3mf.png" width="420" />

</div>

---

## Limitations

- This add-on does not fix or validate geometry
- No batch export or build plate management
- Final print validation is performed by the slicer
- Geometry is exported exactly as it exists in the scene

---

## Blender Extensions

Panda 3MF Toolbox is currently under review for Blender Extensions.

The version available on Blender Extensions may lag behind the GitHub repository during the review process.

---

## Support

Please report bugs or issues using **GitHub Issues**.

---

## Credits

Developed and maintained by **Panda Print**.
