RevToolz Lite - Car Packer (Free Version)
=========================================

📦 What This Tool Does:
This is a lightweight tool that lets you quickly pack multiple FiveM vehicles into a single resource folder — ready to drag and drop into your server.

✅ It organizes everything into:
- /stream — with a subfolder for each vehicle's files
- /data — with subfolders for each vehicle's meta files
- Includes a working __resource.lua file for easy FiveM loading

---

🛠️ How To Use:
1. Launch `revtoolz_lite.exe`
2. Click **Browse** and select the folder that contains all your individual vehicle folders
   - Each vehicle folder should have a `stream` folder and meta files like `vehicles.meta`, `handling.meta`, etc.
3. Click **PACK VEHICLES**
4. Enter a name for the final output folder
5. The packed resource will appear in the same directory as the tool

---

📁 Output Example:
YourOutputFolder/
│
├── __resource.lua
├── stream/
│   ├── vehicle1/
│   ├── vehicle2/
│   └── ...
└── data/
    ├── vehicle1/
    ├── vehicle2/
    └── ...

---

⚠️ Notes:
- Vehicles missing either a stream folder or meta files will be skipped automatically.
- If two vehicles have the same folder name, duplicates will be skipped.
- You can re-run the tool as many times as you want with different folders.

---

Made with ❤️ by Esko @ RevToolz
https://discord.gg/pq9xk3MPN5
