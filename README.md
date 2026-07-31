# Gezo Harvest - Android Pixel Farming RPG

📱 **Gezo Harvest (Harvest Moon: Back to Nature Inspired 2D HD Pixel RPG)**

### 📦 Download Releases:
- 🌾 **Gezo Harvest v4 (Fixed PCK Loader & Embedded assets/assets.pck):** [GezoHarvest_v4.apk](./GezoHarvest_v4.apk) (`26.7 MB`)
- 🌾 **Gezo Harvest v3:** [GezoHarvest_v3.apk](./GezoHarvest_v3.apk) (`26.7 MB`)

✅ **Audit & Fixes in v4:**
- **Root Cause Fixed:** Embedded project PCK at `assets/assets.pck` inside the APK (Resolves *"Couldn't load project data. Is the .pck file missing?"*)
- **Scene Loader:** Main scene `scenes/MainFarm.tscn` loaded as default
- **OpenGL Compatibility:** Renderer switched to `GL Compatibility` (OpenGL ES 3.0)
- **zipalign & apksigner:** Verified 4-byte zipalign & Signature Scheme v1, v2, v3
- **Architecture:** `arm64-v8a` native Android library (`26.7 MB`)
