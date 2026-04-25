

# M10 Bolt, Nut, and Washer Assembly (Fusion 360)

A precision-modeled mechanical assembly created in Autodesk Fusion 360. This project demonstrates top-down assembly modeling, component organization, and functional joint application.

## 🛠 Technical Specifications
- **Hardware Size:** M10 (Metric)
- **Thread Profile:** ISO Metric Profile
- **Thread Pitch:** 1.5 mm
- **Thread Type:** Physically modeled (not cosmetic)
- **Bolt Length:** 40 mm (Shank)
- **Drive Type:** Hexagonal ($16\text{ mm}$ across flats)

## 📁 Project Structure
The model is organized into three distinct components to allow for realistic movement and Bill of Materials (BOM) accuracy:
1.  **Washer:** $20\text{ mm}$ OD, $10.5\text{ mm}$ ID, grounded at the origin.
2.  **Bolt:** Hex-head with a modeled threaded shank.
3.  **Nut:** Hexagonal with internal modeled threads.

## ⚙️ Mechanical Motion
The assembly uses a **Cylindrical Joint** between the nut and the bolt shank.
- **Degrees of Freedom:** Allows for both translation (sliding) and rotation.
- **Interaction:** To test the motion, ensure the Washer component is "Grounded" and drag the Nut along the Z-axis of the Bolt.



<img width="1403" height="782" alt="design" src="https://github.com/user-attachments/assets/389e9238-c7ea-4ba9-a372-d4eb3c1a3a46" />
