<p align="center">
  <img src="YOUR_LOGO_URL_HERE" width="400">
</p>Velox OS

Fast. Fluid. Yours.


---

📌 What is Velox OS?

Velox OS is an open-source aftermarket Android operating system focused on speed, fluidity, and a smooth user experience. Powered by the latest LineageOS base with unique tweaks and optimizations.


---

⚙️ Base Firmware

LineageOS


---

🚀 Getting Started

Initialize your local repository

repo init -u https://github.com/Velox-Os/platform_manifest -b main --git-lfs

Sync the source

repo sync -c --no-clone-bundle --optimized-fetch --prune --force-sync -j$(nproc --all)


---

📱 Building Velox OS

Prepare your environment

. build/envsetup.sh

Lunch your device

lunch velox_<device>-userdebug

Start the build

mka bacon
``

