# Machinist MR9A PRO MAX Modded BIOS (X9MPM001)

**Developer:** Avkila  
**Status:** Tested / Working  

---

### 🛠 Changelog
* **Overclocking:** Injected OC driver. Multiplier/Voltage control unlocked.
* **Memory Tuning:** Injected memory driver. Access to timings/frequency unlocked.
* **Power Limits:** Current limits removed (Manual configuration required in BIOS).
* **Resizable BAR:** Injected RebarDxe driver.
* **BCLK Fix:** Spread Spectrum killed via Intel FIT. Fixed 100MHz BCLK.
* **Turbo Boost:** No Turbo Boost unlock injected.

### ⚡ Power & Overclocking Guidance
* **Power Limit Safety:** Most E5 26xx v3/v4 and 16xx v4 CPUs have a hard cap at 140W and are completely fine with this BIOS.
* **High Wattage CPUs:** Chips like the E5 1650v3, 1660v3, 1680v3, i7 6700k, 6800k, and 6950X are fine to use if you leave the power limits enabled.
* **Stable Overclocking:** Because Chinese boards often have very aggressive built-in power limits, I recommend disabling the power limit in the BIOS for a stable overclock, but then setting a manual power limit in Intel XTU.

> [!CAUTION]
> **CSM MUST BE OFF:** You must disable CSM (Compatibility Support Module) in the BIOS. The RebarDxe driver will cause a boot failure/hang if CSM is enabled. Ensure your OS is on a **GPT** partition.

---

### 💾 File Verification
**Avkila's Modded ROM**
* **SHA-256:** `4eab0567829ae5e51bdf4db79d6ce45d385d196b4a3abc1905d52518dcf0a31c`
* **MD5:** `b838d141132744325b1de92837629799`

**Stock Image (For Reference)**
* **SHA-256:** `8c447651059696993065e8ae25a5546c761af970372b9b3075a542da8e555972`
* **MD5:** `07c75001fec08006214739ab8add76e2`

---

### 🤝 Credits
* **Stock ROM:** [koshak1013](https://github.com/Koshak1013/HuananzhiX99_BIOS_mods)
* **Modded by:** Avkila

**Disclaimer:** This firmware is provided as-is. I will not take any responsibility for bricking your motherboard, but I will happily help you recover it if you ask me nicely. Always have a CH341A programmer and a backup of your original ROM ready.