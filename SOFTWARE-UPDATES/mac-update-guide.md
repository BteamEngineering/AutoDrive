# Mac Firmware Update Guide

This guide explains how to update your AutoDrive controller using a Mac.

## What You Need

- Mac computer
- AutoDrive controller connected via Micro-USB
- Firmware (.hex file)
- upload_firmware.sh script
- Internet connection (first-time setup only)

---

## Step 1 – Prepare Files

Option A (Recommended):
- Place the firmware file in the same folder as the script
- The tool will automatically detect it

Option B:
- Store the firmware anywhere
- You will be prompted to enter the file location

---

## Step 2 – Enable Script (One-Time Setup)

Option A:
- Right-click the script
- Select "Get Info"
- Set "Open with" → Terminal.app

Option B:
- Open Terminal
- Type: chmod +x
- Drag script into terminal
- Press Enter

---

## Step 3 – Run the Tool

- Connect controller via USB
- Double-click the script
- Allow execution if prompted

The tool will automatically:
- Install Arduino CLI (first run only)
- Detect controller
- Locate firmware
- Upload firmware

---

## What to Expect

First Run:
- Installs dependencies (2–3 minutes)

Normal Use:
- Upload takes ~30–60 seconds
- Confirmation shown when complete

---

## Important

- Do NOT unplug during upload
- Do NOT rename firmware file
- Tool remains open until completion

---

## Troubleshooting

No Controller Found:
- Check USB connection
- Ensure cable supports data

Upload Fails:
- Reconnect USB
- Retry upload

Script Won’t Open:
- Verify permissions
- Check macOS security settings

---

## Support

If issues persist:
- Take a screenshot
- Contact support with details
