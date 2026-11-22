# BiomeBundleReloaded-Preset
BiomeBundleReloaded-Preset for plugin OTGZeusAdventureRL minecraft 1.21
# 🌍 BiomeBundleReloaded (BBR) — Reborn for Minecraft 1.21+

This repository hosts the official **BiomeBundleReloaded (BBR)** world preset for **OTGZeusAdventureRL** — a complete, ground-breaking revival of Open Terrain Generator (OTG) and BBR, rewritten and optimized from 1.16.5 all the way to modern **Minecraft 1.21+**.

---

### 🌲 About Biome Bundle Reloaded (BBR)
Experience a breathtaking universe filled with variety, depth, and custom landscapes — completely server-side (no client mods required):
* **400+ Custom Biomes:** Massive custom mountain ranges, deep fantasy forests, unique desert oases, and more.
* **Custom Structures:** Hundreds of unique ruins, custom trees, dungeons, and landmarks generated naturally across the world.
* **Modern 1.21+ Ecosystem Blending:** Rewritten ecosystem logic ensuring modern mechanics (such as Trial Chambers and the Deep Dark) generate seamlessly alongside classic BBR biomes.

---

### ⏳ A 6-Year Journey of Passion & Dedication
This project is my life's work. Since **January 2020**, I have poured endless hours and immense effort into rebuilding this engine from the ground up. Over the past 6 years, I have rewritten extensive parts of the world generation, redesigned major systems from scratch, and overcome massive technical hurdles to bring BBR and OTG into the modern era of Minecraft. 

I continue to actively develop, optimize, and expand this project every single day so the Minecraft community can enjoy the ultimate exploration experience for years to come.

---

### 🚀 Installation Guide
1. **Download the Main Plugin (Required):** You must get the main **`OTGZeusAdventureRL.jar`** plugin from our official **[Modrinth Project Page](https://modrinth.com)**. Place the JAR file into your server's `plugins/` folder, start the server once to generate the configuration folders, and stop it.
2. **Download the BBR Preset:** Go to the **[Releases](../../releases)** tab on the right side of this GitHub page and download `BiomeBundleReloaded.zip`.
3. **Extract the Preset:** Move `BiomeBundleReloaded.zip` into `plugins/OTGZeusAdventureRL/Presets/` and extract it there (you can safely delete the `.zip` file afterward).
4. **Configure `bukkit.yml`:** Open `bukkit.yml` in your server's root folder and add the following lines at the bottom:
   ```yaml
   worlds:
     world:
       generator: OTGZeusAdventureRL:BiomeBundleReloaded
   ```
5. **Generate World:** Delete your default `world` folder and start the server to generate your new BBR world! *(Purpur is recommended for optimal performance).*

---

### 🏅 Credits & Deepest Gratitude
This dream would never have been possible without the brilliant minds behind the original frameworks. Deepest respect and thanks to:
* **nekdu64_** — Creator of **Biome Bundle Reloaded (BBR)**
* **PG85, Team OTG, and MCPitman** — Creators of **Open Terrain Generator (OTG)**

Thank you for building the foundations that inspired this 6-year journey.
