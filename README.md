# DisplayTemps Rainmeter skin

GPU and CPU temps in Rainmeter using MSI Afterburner’s data.

## Contents
- `DisplayTemps_1.0.rmskin` packaged Rainmeter skin.

## Requirements
- Windows 10 or 11.
- **MSI Afterburner** (v4.6.x or newer).
  - During setup, **install RivaTuner Statistics Server (RTSS)** when prompted.
- **Rainmeter** (v4.5.x or newer).

## Install MSI Afterburner + RTSS
1. Run the MSI Afterburner installer.
2. When the RTSS component screen appears, leave it **checked** and continue.
3. Launch Afterburner once. Go to **Settings → Monitoring**.
4. Ensure hardware monitoring is enabled and the sensors you care about are **checked**.
5. Enable **Start with Windows** if you want data available after reboot.
6. Keep **Afterburner running**. Rainmeter reads its shared memory.

## Install Rainmeter
1. Run the Rainmeter installer.
2. Choose **Standard installation**.
3. Finish and allow Rainmeter to start (you will see its tray icon).

## Add the `.rmskin` to Rainmeter (accurate process)
1. Double-click `DisplayTemps_1.0.rmskin`.
2. The **Rainmeter Skin Installer** window opens and shows the package name, author, version, and contents.
3. Leave **Load included skins** checked. If present, you can also check **Apply included layout**.
4. Click **Install**. The files are copied to `Documents\Rainmeter\Skins\DisplayTemps` and the skin loads.
