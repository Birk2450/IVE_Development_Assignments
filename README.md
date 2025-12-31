# IVE Development Assignments

This repository contains deliverables for the course  
**Intelligent Virtual Environments: Technologies, Architectures and Applications**.

---

## Repository Structure

```text
IVE_Development_Assignments/
├─ Assignment1/
│  ├─ 1_1_VR/
│  ├─ 1_2_AR/
│  └─ Assignment1_AR_VR_Birk.pdf
└─ Assignment2/
   ├─ HoganAlley.apk
   ├─ HoganAlley_UnityProject.zip
   └─ IVE_Assignment2_HogansAlley.pdf
```

---

## Assignment 2 – Hogan’s Alley (VR for Smartphone)

### Overview
Assignment 2 is a custom **mobile VR shooting gallery** inspired by the classic *Hogan’s Alley* arcade game.  
The project is implemented in **Unity** using the **Google Cardboard XR Plugin** and deployed as an **Android APK**.

The player stands at a fixed position and interacts with the environment through:
- Head-based aiming (gyroscope)
- Screen tap shooting
- Gaze-based reticle interaction

No artificial locomotion is used to reduce motion sickness.

---

### Deliverables:
- `Assignment2/HogansAlley_Birk.apk` – Android APK (playable demo)
- `Assignment2/IVE_Assignment2_HogansAlley.pdf` – Documentation/report

Unity project sources:
Due to file size constraints on GitHub and Moodle, the Unity project source archive is hosted externally:

🔗 Unity Project ZIP (Google Drive):  
https://drive.google.com/file/d/1prC9lk9dPDhvvNnUI5cayK-3iK6ypjkQ/view?usp=sharing 

---

### How to Play
1. Install the APK on an Android device.
2. Insert the phone into a Google Cardboard-compatible viewer.
3. Aim by moving your head.
4. Shoot by tapping the screen.
5. Hit hostile targets (goons).
6. Avoid shooting civilians — they disappear automatically if left alone.

---

### Technical Notes
- Built with **Unity 6.x**
- **Google Cardboard XR Plugin**
- Minimum Android API: **26**
- Target Android API: **35**
- Uses Unity **Input System** (mobile tap input)
- Scene entry point: `HogansAlley`

---

### Notes on Testing
Full head tracking is only available on physical Android devices.  
When run in the Unity Editor, head rotation is not replicated due to missing gyroscope input.

---

### Author
**Birk Bregendahl**  
December 2025