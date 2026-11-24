# Out of Space — Epic MegaJam 2021


https://github.com/user-attachments/assets/6be9c1fc-8bbe-41b2-9976-1483fd43243d


A 3D puzzle game made in **7 days** for the **2021 Epic MegaJam** (theme: *"Running Out of Space"*), built in **Unreal Engine 5 Early Access** by a two-person team, **Limited Corporation**.

You play **KOR**, a robot inside a computer. Each level has a disk with a fixed capacity: scan objects of different sizes, clone them, and place them on the grid to fill the disk to exactly its capacity. Match it and the energy barrier drops, letting you grab the drive and finish the level.

[**▶ Download on itch.io**](https://lshigaki.itch.io/outofspace) (Windows)

---

## 🎮 Controls

- **WASD** → Move
- **Space** → Jump
- **Hold LMB** → Scan object
- **Q / E** → Choose which scanned object to clone
- **B** → Toggle builder mode, **LMB** to place

---

## ⚙️ Gameplay Systems (my work)

All gameplay was implemented in **Blueprints** during the jam week:

- **Scan & clone:** scan objects in the level and clone them through an item selector
- **Grid builder:** grid-based placement with a build preview mode
- **Viruses:** red and blue viruses that grow or shrink objects, changing how pieces fit
- **Level mechanics:** "Disk" level logic (capacity check, energy barrier, drive pickup), glass surfaces, CPU sockets
- **Disk display:** in-world display tracking used space against the level's capacity
- **Level flow:** retry on failure and a complete tutorial level

---

## 👥 Team

| | Role |
|---|---|
| **Leandro Shigaki** | Gameplay programming: all mechanics and systems listed above, tutorial, level flow |
| **Mazzo** | Art, robot model and animations, level design, menus and UI, audio integration |

Assets were made in Blender and Unreal (robot, data center and box textures in Substance Painter). Music from WeLoveIndies and Dynamedion.

---

## 🛠️ Tech

- Unreal Engine 5 Early Access
- Blueprints only
- 5 levels + tutorial, made in 7 days (26 Aug – 2 Sep 2021)

## 📌 Notes

This is a game jam project: the code and content were written quickly to ship within the deadline and are kept as they were at submission.

