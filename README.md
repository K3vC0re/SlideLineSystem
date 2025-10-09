# 🎢 SlideLine System

A fully Blueprint-based spline sliding system for **Unreal Engine 5**, designed for games, cinematics, and prototypes.  
Easily create dynamic slide paths, rails, or traversal systems using splines — with jump, lean, crouch, obstacle detection, and customizable camera behavior.

---

## 🚀 Features

- **Blueprint-Based Spline Sliding System**  
  100% built in Blueprints — no C++ required.  

- **Dynamic Sliding Mechanics**  
  Slide, jump, lean, crouch, dodge obstacles, and control speed along the spline.  

- **Advanced Curve Handling**  
  Fall off when taking curves too sharply or misaligned.  

- **Modular & Fully Customizable**  
  Every system element is exposed in Blueprints for easy modification and expansion.  

- **Integrated VFX & SFX**  
  Comes preconfigured with Niagara and Audio hooks — ready to customize.  

- **Cinematic Camera System**  
  Includes a custom third-person camera designed for smooth motion along splines.  

- **Flexible Use Cases**  
  Works for human characters, vehicles, trains, slot cars, or cinematic camera paths.

---

## 🕹️ How to Use

Getting started with the SlideLine System is quick and easy — everything runs directly in Blueprints.
This is just a short overview. For detailed setup instructions, please refer to the Wiki.

1. **Add the Component / Interface**  
   - Add the `BP_SlideLine_Component` & Implement the `BPI_SlideLine_Interface` to your character.

2. **Setup Blueprint**  
   - Copy all Red Nodes.
   - Copy all Interfaces Functions
     
3. **Create a Trace Channel**  
   - Create a new Trace`SlideLine`   

4. **Setup Animation Blueprint**  
   - Link the `SlideLine_AnimBP` to your current Active Animation Blueprint
   - Copy 2 Green Nodes

5. **Tune Your Settings**  
   - Open the `DA_SlideLine_Settings` data asset:  
     `/All/Game/SlideLineSystem/Blueprints/SlideLineSystem/Settings/`
   - The project contains precise information about the data file.
  
6. **Play & Test**  
   - Hit Play — your character should now smoothly slide along the spline.  
   - Use Lean or Jump during the slide to test transitions and camera movement.

> 💡 **Tip:** For advanced use, you can connect custom logic (like triggers, effects, or camera events) via the interface events — no need to edit the core system!


> ⚠️ **Safety First:** Always back up your project before integrating new systems!

---



## ⚙️ Customization

- All core parameters can be adjusted in the `DA_SlideLine_Settings` data asset.  
- Enable or disable gameplay features such as Jumping, Crouching, Speed Control, Lean, Fall Off Curve, Camera Behavior, Hit Collision, Automatic Lean Reset, Slide Direction Change, Spline Switching, VFX, and SFX.  
- Adjust the **Spline Transition Force (Factor X)** for smoother or longer jumps between splines.  
- All Blueprints are **fully commented** and easy to extend for custom logic or visuals.

---

## 🧠 Intended Audience

The SlideLine System is made for **everyone working in Unreal Engine**, especially those who love using Blueprints.

- Indie and solo developers  
- Technical artists and designers  
- Teams building modular gameplay or cinematic experiences  

> Optimized for Blueprint-based projects but flexible enough for any Unreal Engine workflow.

---

## 🐞 Troubleshooting

If something doesn’t work as expected:

- **Animations not working:**  
  Ensure your Animation BP links correctly to `SlideLineAnim_BP`.

- **VFX / SFX not playing:**  
  Check that Niagara and audio are enabled, and assets are referenced in `DA_SlideLine_Settings`.

- **Character doesn’t slide:**  
  Make sure the SlideLine Component and Interface are correctly added to your character, and inputs are set up.

If issues persist, don’t worry — I’ll help you out personally.

📧 **Support:** [contact@kevcore.com](mailto:contact@kevcore.com)

---

## 🧱 Credits

- **System & Blueprints:** Kevcore  
- **Animations:** [Ultimate Traversal Anims](https://www.unrealengine.com/marketplace/en-US/product/ultimate-traversal-anims)  
- **VFX:** Based on [Stylized Sword Trails VFX Pack](https://www.unrealengine.com/marketplace/) — modified and adapted for the SlideLine System  
- **SFX:** From [Pixabay.com](https://pixabay.com/sound-effects/) (Free for commercial use)

> All third-party assets remain the property of their original creators and are integrated under respective licenses.

---

## 🔄 Ongoing Development

The SlideLine System is currently in **Version 1.0**.  
I’m actively working on updates with **camera improvements, smoother transitions**, and new features to enhance **usability, performance, and user experience**.

💡 Suggestions and bug reports are always welcome — every piece of feedback helps improve the system for everyone.

---

## 📄 License

This project is licensed under the **Unreal Engine Marketplace EULA**.  
Do not redistribute, resell, or share the included assets outside of projects using the SlideLine System.

---

### ❤️ Created by Kevcore  
*Designed for creators. Built for Blueprint developers.*
