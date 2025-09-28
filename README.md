# Custom Desktop PC Build – Group 1

**Course**: CSARCH2
**Section**: S20
**Group Members**:
- Crisostomo, Josh Neal
- Lim, Patrick Anthony
- Ross, Isabella Althea
- De Castro, Jediaelle Denise
- Sim, Matthew Fraser
---
## 1. Introduction
Briefly describe your project build (1–2 paragraphs).
Mention: target use case (e.g., general-purpose desktop, gaming, programming, data
science, etc.) and budget constraint.
---
## 2. Draft Build (PCPartPicker)
This build uses **PCPartPicker System Builder** for compatibility check.
PCPartPicker Permalink: https://pcpartpicker.com/list/cNd2PJ
### Summary Table
| Component | Model | Price (USD/Php) | Notes |
|-----------------|-------|-----------------|-------|
| CPU | Intel Core i3-12100 3.3GHz Quad-Core Processor | $139.99 / ₱8,128.83 | Compatible with the Motherboard's CPU Socket (LGA1700) |
| CPU Cooler | ARCTIC Alpine 17 CO | $12.99 / ₱754.29 | Compatible with the Motherboard's CPU Cooler Mount (LGA1700) |
| Motherboard | MSI PRO H610M-G DDR4 Micro TX LGA 1700 Motherboard | $89.29 / ₱5184.82 | Fits the Lian Li A3-mATX MicroATX Mini Tower Case (Motherboard Mount) |
| RAM | TEAMGROUP T-Create Expert 16GB (2x8GB) DDR4-3200 CL 16 Memory | $45.99 / ₱2670.51 | Occupies both RAM1 and RAM2 (288-pin DIMM) slots. However, RAM Clearance with the CPU Cooler is not checked. |
| Storage 1 | TEAMGROUP MS30 256GB M.2-2280 SATA SSD | $21.99 / ₱1276.90 | Occupies the M.2_1 (M) slot. However, using this SATA-based M.2 device disables one SATA 6 Gb/s port. |
| Storage 2 | ... | ... | ... |
| Graphics Card | ... | ... | ... |
| Power Supply | MSI MAG A550BN 550W 80+ Bronze  Certified ATX Power Supply | $54.99 / ₱3193.12 | Fits the Lian Li A3-mATX MicroATX Mini Tower Case (PSU_MNT). Compatible with the Motherboard for both ATX24 (24-Pin) and EPS (8-Pin) power connections. |
| Case | Lian Li A3-mATX MicroATX Mini Tower Case | $69.99 / ₱4064.12 | Requires adapters for full front panel USB functionality: USB 2.0 to USB 3.2 Gen 1 header adapter and USB 3.2 Gen 1 to USB 3.2 Gen 2 header adapter. |
| Case Fans | Thermalright TL-P12W-S 52.86 CFM 120 mm Fan | $5.39 / ₱312.98 | Fan compatibility checking is currently not supported. |
| **Total** | | **439.92 USD / 25585.57 Php** | |
---
## 3. Local Manila Build
This build uses **locally available parts** from Manila vendors.
Google spreadsheet link: [PC_Build_Template_With_Budget](https://docs.google.com/spreadsheets/d/15jZedLD7o_Gfmr0jKC2sMzixGadV74LwGvGNQ5sZwUE/edit?gid=533572080#gid=533572080)

### Local Build Table

| Component       | Model | Vendor & Link       | Price (Php) | Compatibility Notes                        |
|-----------------|-------|--------------------|-------------|-------------------------------------------|
| CPU             | INTEL CORE I3 12100 (LGA1700)   | [PC WORTH](https://www.pcworth.com/product/28231a3d76be?slug=intel-core-i3-12100-lga1700-with-intel-laminar-rm1-cooler-boxed) | 6,495         | Compatible with H610M motherboard       |
| CPU Cooler      | INTEL LAMINAR RM1 COOLER (comes with CPU)   | [PC WORTH](https://www.pcworth.com/product/28231a3d76be?slug=intel-core-i3-12100-lga1700-with-intel-laminar-rm1-cooler-boxed)    | 0         | Fits case clearance                        |
| Motherboard     | Gigabyte H610M K DDR4 LGA1700 Motherboard   | [DynaQuest PC](https://dynaquestpc.com/products/gigabyte-h610m-k-ddr4-lga1700-motherboard) | 4,150         | Dual Channel DDR4                          |
| RAM             | Lexar Thor 8GB Single DDR4 3200MHz Desktop Memory LD4BU008G-R3200GSXG x2   | [DynaQuest PC](https://dynaquestpc.com/products/lexar-thor-8gb-8gbx1-ddr4-3200mhz-desktop-memory-ld4bu008g-r3200csxg?_pos=2&_psq=lexar+thor&_ss=e&_v=1.0) | 2,640         | DDR4 3200MHz 2x8GB                      |
| Storage 1 (SSD) | Adata Legend 710 512GB PCIe Gen3 x4 M.2 NVME 2280 Internal SSD ALEG-710-512GCS   | [DynaQuest PC](https://dynaquestpc.com/products/adata-legend-710-512gb-pcie-gen3-x4-m-2-nvme-2280-internal-ssd-aleg-710-512cgs) | 1,820         | NVMe M.2 Supported                   |
| Storage 2 (HDD) | ...   | ...    | ...         | ...                        |
| GPU             | ...   | ...   | ...         | ...        |
| PSU             | MSI MAG A550BN Bronze 550W 80+ Power Supply   | [DynaQuest PC](https://dynaquestpc.com/products/msi-mag-a550bn-bronze-550w-80-power-supply?_pos=1&_psq=MSI+MAG+a550BN&_ss=e&_v=1.0)    | 2,595         | 550W, 80+ Bronze                           |
| Case            | Tecware NEO M2 Steel Black Mesh mATX Case with 3X120mm Fans   | [DynaQuest PC](https://dynaquestpc.com/products/tecware-neo-m2-steel-black-mesh-matx-case-with-3x120mm-fans)    | 1,670         | Micro ATX                              |
| Case Fans       |  3X120mm Fans (comes with Case)   | [DynaQuest PC](https://dynaquestpc.com/products/tecware-neo-m2-steel-black-mesh-matx-case-with-3x120mm-fans)    | 0         | 120mm x3                              |
| **Total**       |       |                    | **19,370 Php** | Within budget                              |

## 4. Compatibility Justification
For each part, explain compatibility and choices.
Example:
- **CPU + Motherboard**: Intel i5-13400F (LGA1700) works with ASUS B760M board
(LGA1700 socket, BIOS compatible).
- **RAM**: DDR5 RAM supported by motherboard slots (up to 128GB).
- **GPU**: NVIDIA RTX 3060 fits case, PSU wattage sufficient.
---
## 5. Budget Analysis
- **Budget Limit**: ₱XX,000
- **Final Total**: ₱XX,000
- Within budget / Over budget✅ ❌
- Notes on trade-offs (e.g., cheaper RAM, higher PSU wattage, no aftermarket
cooler, etc.).
---
## 6. Conclusion & Learnings
Reflections on:
- Price differences (international vs. Manila vendors)
- Challenges in finding stock or cheaper equivalents
- What the group learned about PC components and system design
---
## 7. Video pitch
- Your video link here
## 8. References
- Vendor link 1: https://www.pcworth.com/
- Vendor link 2: https://dynaquestpc.com/
- PCPartPicker build link: https://pcpartpicker.com/list/cNd2PJ
- Any technical documentation consulted
