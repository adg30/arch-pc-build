# Custom Desktop PC Build – Group 5

**Course**: CSARCH2

**Section**: S20

**Group Members**:

- Benigno, James Khalel
- Corpuz, Thara Mae
- Ganayo, Reinman Geoffrey
- Go, Aaron Daniel
- Tandingan, Hyun Jei

---

## 1. Introduction

This project aims to design an **Extreme-entry level intel-based gaming desktop PC** with a budget target of **₱200,000**. The build focuses on providing high-performance 4K gaming while remaining practical for everyday tasks such as academic work, productivity, and multimedia use.

Our goal was not simply to assemble the most powerful machine possible, but to demonstrate how performance, compatibility, future-proofing, and local availability must be balanced under real-world constraints. By working with only Manila-based vendors, we accounted for pricing, sourcing, and warranty considerations that affect builders in the Philippines.

This approach highlights the importance of strategic component selection in computer architecture: each part was chosen not just for raw power, but also for its ability to ensure system stability, upgrade paths, and long-term usability.

---

## 2. PCPartPicker Build

This build was validated for baseline compatibility using the PCPartPicker System Builder.

**PCPartPicker Permalink:** https://pcpartpicker.com/user/jbeniugn/saved/94dXYJ

### Summary Table

| Component     | Model                                                           | Price (Php) |
| ------------- | --------------------------------------------------------------- | ----------- |
| CPU           | Intel Core i9-14900K                                            | 29,995      |
| CPU Cooler    | Arctic Liquid Freezer III 360 A-RGB                             | 5,795       |
| Motherboard   | MSI MAG Z790 Tomahawk WiFi DDR5                                 | 18,450      |
| RAM           | Corsair Dominator Titanium RGB 64GB (2x32GB) DDR5 6000MT/s CL30 | 18,995      |
| Storage 1     | WD BLACK SN850X 4TB NVMe SSD                                    | 18,750      |
| Storage 2     | TeamGroup T-Force Vulcan Z 2TB SATA SSD                         | 5,950       |
| Graphics Card | GEFORCE RTX 5080 ASUS PRIME OC 16GB                             | 79,995      |
| Power Supply  | Corsair RM1200x SHIFT 1200W 80+ GOLD                            | 12,780      |
| Case          | Fractal Design Meshify 2 ATX Mid-Tower                          | 10,995      |
| Case Fans     | Lian Li Uni Fan SL120 V2 RGB 3-Pack                             | 4,995       |
| **Total**     |                                                                 | **206,700** |

---

## 3. Local Manila Build

This build uses **locally available parts** from Manila-based vendors. All prices are accurate as of the time of research.

**Google Spreadsheet Link:** [Group 5 - PC Build Sheet](https://docs.google.com/spreadsheets/d/1fvw2BcPDp4KBf0TdzCiku6UDXd0qcctDz3ZCUaP_g3I/edit?usp=sharing)

### Local Build Table

| Component     | Model                                             | Vendor & Link                                                                                                                                                                     | Price (Php) | Compatibility Notes                                                                              |
| ------------- | ------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- | ------------------------------------------------------------------------------------------------ |
| CPU           | Intel Core i9-14900K                              | [DataBlitz](https://ecommerce.datablitz.com.ph/products/intel-core-i9-14900k-14th-gen-3-2ghz-24-core-lga-1700-processor-bx8071514900k)                                            | 29,995      | Fits LGA 1700 socket on the Z790 motherboard.                                                    |
| CPU Cooler    | Arctic Liquid Freezer III 360 A-RGB               | [DataBlitz](https://ecommerce.datablitz.com.ph/products/arctic-liquid-freezer-iii-pro-360-multi-compatible-aio-cpu-water-cooler-black-acfre00180a)                                | 5,795       | Compatible with LGA 1700 socket and fits in the Meshify 2 case.                                  |
| Motherboard   | MSI MAG Z790 Tomahawk WiFi DDR5                   | [DataBlitz](https://ecommerce.datablitz.com.ph/products/msi-mag-z790-tomahawk-wifi-ddr5-motherboard)                                                                              | 18,450      | ATX form factor fits the Meshify 2 case; supports LGA 1700 CPU, DDR5 RAM, and PCIe 5.0.          |
| RAM           | Corsair Dominator Titanium RGB 64GB DDR5 6000MT/s | [DataBlitz](https://ecommerce.datablitz.com.ph/products/corsair-dominator-titanium-rgb-64gb-2x32gb-ddr5-dram-6000mt-s-cl30-amd-expo-intel-xmp-memory-kit-grey-cmp64gx5m2b6000z30) | 18,995      | Compatible with MSI Z790 DDR5 slots.                                                             |
| Storage 1     | WD BLACK SN850X 4TB NVMe SSD                      | [DataBlitz](https://ecommerce.datablitz.com.ph/products/wd-black-sn850x-4tb-nvme-pcie-gen4-x4-m-2-2280-7300mb-s-read-speed-internal-gaming-ssd-without-heatsink-wds400t2x0e)      | 18,750      | Fits M.2 2280 slot; motherboard's M.2 shields provide sufficient cooling.                        |
| Storage 2     | TeamGroup T-Force Vulcan Z 2TB SATA SSD           | [DataBlitz](https://ecommerce.datablitz.com.ph/products/teamgroup-t-force-vulcan-z-2tb-2-5-sata-iii-3d-nand-internal-ssd-t253tz002t0c101)                                         | 5,950       | Supported by motherboard's SATA III ports.                                                       |
| Graphics Card | GEFORCE RTX 5080 ASUS PRIME OC 16GB               | [PCWorth](https://www.pcworth.com/product/4be2bbbaa4a1?slug=geforce-rtx-5080-asus-prime-oc-16gb-gddr7-black-triple-fan)                                                           | 79,995      | Fits PCIe 5.0 x16 slot. The 304mm GPU length is well within the Meshify 2's 467mm max clearance. |
| Power Supply  | Corsair RM1200x SHIFT 1200W 80+ GOLD              | [DynaQuest PC](https://dynaquestpc.com/products/corsair-rm1200x-shift-white-1200w-80-gold-fully-modular-psu-cp-9020276-na)                                                        | 12,780      | Standard ATX PSU form factor. 1200W capacity safely powers the i9-14900K and RTX 5080.           |
| Case          | Fractal Design Meshify 2 ATX Mid-Tower            | [DataBlitz](https://ecommerce.datablitz.com.ph/products/fractal-design-meshify-2-computer-case-rgb-black-tg-light-tint-rgb-white-tg-clear-tint-fd-c-mes2a-06-fd-c-mes2a-08)       | 10,995      | Supports ATX motherboard, 360mm radiator, and GPUs up to 467mm.                                  |
| Case Fans     | Lian Li Uni Fan SL120 V2 RGB 3-Pack               | [GameOne](https://gameone.ph/lian-li-uni-fan-sl120-v2-rgb-3x-fan-pack-with-controller-black.html)                                                                                 | 4,995       | Fits standard 120mm fan mounts in the Meshify 2 case.                                            |

---

## 4. Technical & Compatibility Justification

### CPU (Intel Core i9-14900K):

- Intel's flagship 14th Gen consumer CPU was selected for its leading single-core speed, maximizing FPS in modern games. With 24 cores and 32 threads, it also supports heavy multitasking like streaming and content creation. This ensures the system can handle current workloads and won't bottleneck future GPU upgrades.

- The unlocked multiplier allows for future overclocking, while support for DDR5 and PCIe 5.0 ensures compatibility with next-generation hardware. Although power-hungry, its performance is unmatched for this budget, and the rest of the system (cooling and PSU) was chosen to accommodate it.

### Motherboard (MSI MAG Z790 Tomahawk):

- Chosen for its powerful VRM design and feature set, this Z790 board provides stable power delivery for the i9-14900K. It supports DDR5 memory, PCIe 5.0 GPUs and SSDs, and WiFi 6E.
- We deliberately avoided higher-end motherboards because this board already offers everything needed for stability, expansion, and performance, allowing more of the budget to be spent on the GPU and PSU. This strikes the right balance between cost and capability.

### CPU Cooler (Arctic Liquid Freezer III 360):

- The i9-14900K generates significant heat, requiring high-end cooling. This 360mm AIO liquid cooler prevents thermal throttling and maintains boost clock speeds under load, ensuring sustained performance and system longevity.
- We selected the 360mm version over a larger 420mm for cost-effectiveness and compatibility with the Meshify 2 case, while still providing high thermal headroom.

### RAM (Corsair Dominator Titanium 64GB DDR5):

- With 6000MT/s speed and CL30 latency, this kit balances high frequency and low latency for optimal Intel performance. The 64GB capacity far exceeds current gaming needs but provides headroom for larger titles, professional workloads, and long-term use, making it a future-proof choice.
- The Dominator Titanium line is also known for reliability and stable XMP tuning, ensuring consistent performance (and also why we chose it over the others).

### GPU (GEFORCE RTX 5080 ASUS PRIME OC):

- The build's centerpiece, the RTX 5080, provides no-compromise 4K gaming with NVIDIA's latest Blackwell architecture and 16GB of fast GDDR7 VRAM. We chose the 5080 over the 5090, since while the latter is faster, it costs nearly double for only marginal gains in extreme gaming contexts. This aligns with the project's "extreme entry-level" scope and keeps the build within budget.
- The ASUS PRIME OC edition provides a high-end triple-fan cooling design that maintains lower noise and temperatures, ensuring stability during long gaming sessions.

### Storage 1 (WD BLACK SN850X 4TB):

- A high-speed Gen4 NVMe SSD delivering up to 7300MB/s read speeds. Its 4TB capacity ensures space for large game libraries, applications, and media without compromising performance.
- We opted against PCIe 5.0 drives, as the real-world gains are minimal for significantly higher cost, making the SN850X the most cost-effective high-end choice.

### Storage 2 (TeamGroup Vulcan Z 2TB):

- Provides cost-effective secondary storage, ideal for less speed-sensitive data such as bulk games and media. Faster than HDDs, while preserving M.2 slots for potential future NVMe upgrades.

### Power Supply (Corsair RM1200x SHIFT 1200W):

- This Gold-rated ATX 3.0 PSU ensures efficient, stable power delivery. Although PCPartPicker estimated an 800W requirement, we chose a 1200W Gold-rated ATX 3.0 unit to provide headroom for power spikes, ensure GPU/CPU stability, and allow for future upgrades.
- Compared to the cheaper RM1000e, the RM1200x offers quieter operation, longer warranty, and higher capacity -- a safer long-term investment. The SHIFT side-mounted connector design also improves cable management inside the Meshify 2.

### Case (Fractal Design Meshify 2):

Chosen for its exceptional airflow, spacious interior, and modern design. With 467mm GPU clearance and support for a 360mm radiator, it accommodates both the RTX 5080 and AIO cooler easily. This prevents airflow bottlenecks and ensures long-term flexibility for upgrades.

### Case Fans (Lian Li Uni):

While not strictly required for thermals (what we have is probably overkill), we chose the Lian Li Uni fans for their airflow optimization and clean daisy-chain cabling, which improves build quality and aesthetics.

---

## 5. Budget Analysis

- **Budget Limit**: ₱200,000.00
- **Final Total**: ₱206,700.00
- **Result**: Over Budget, but Compliant ✅
- **Notes**: Our build went slightly over budget by ₱6,700 (3.3%). This was an intentional decision to prioritize system stability and longevity. Instead of cutting costs by downgrading the power supply or case, we chose to invest in a 1200W PSU and spacious Meshify 2 case, which provide long-term value, safety, and upgrade flexibility. In our case, the overage is within the project's 5% margin, making the decision both practical and justifiable.

---

## 6. Conclusion & Learnings

This project gave us a realistic view of what it takes to design and source an Extreme Entry-Level Gaming PC within a fixed budget and using only locally available components in Manila.

We learned several key lessons:

**1. Balancing Performance and Budget:** Even though we had the "dream-like" budget for our PC, we still had to juggle costs as including the RTX 5090 would add an extra ~80k to the price, which in our case wasn't worth it as described in the justifications.

**2. Vendor Availability Shapes Builds:** Component choices in the Philippines are often dictated by what local retailers have in stock, Even if a component exists internationally, local availability, warranty, and service support are critical for a successful build.

**3. Future-Proofing vs Immediate Needs:** By selecting high-capacity DDR5 RAM, a 1200W PSU, and a spacious Meshify 2 case, we ensured the system won't just perform well today but will also support future upgrades in the next 3–5 years.

In summary, this project showed us that PC building is much more complex than just picking the shiniest most powerful parts. Builders need to weigh cost, compatibility, availability, and future-proofing to deliver a stable machine.

---

## 7. Video Pitch

[video link](https://www.youtube.com/watch?v=yHbjKz6Ath0)


note the budget in the video is wrong as the price of the cpu increased after the video was made; 

our total price changed from 205,555 -> 206,700 (still within overage limit), which we believe didnt necessitate a redo of the video

---

## 8. References

- **Technical Reference Links:**
- **PCPartPicker Build Link:** [https://pcpartpicker.com/user/jbeniugn/saved/94dXYJ](https://pcpartpicker.com/user/jbeniugn/saved/94dXYJ)
- **Google Spreadsheet Link:** [https://docs.google.com/spreadsheets/d/1fvw2BcPDp4KBf0TdzCiku6UDXd0qcctDz3ZCUaP_g3I/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1fvw2BcPDp4KBf0TdzCiku6UDXd0qcctDz3ZCUaP_g3I/edit?usp=sharing)

- **Vendor Links:**

https://ecommerce.datablitz.com.ph/products/intel-core-i9-14900k-14th-gen-3-2ghz-24-core-lga-1700-processor-bx8071514900k

https://ecommerce.datablitz.com.ph/products/arctic-liquid-freezer-iii-pro-360-a-rgb-multi-compatible-aio-cpu-water-cooler-black-white

https://ecommerce.datablitz.com.ph/products/msi-mag-z790-tomahawk-wifi-ddr5-motherboard

https://ecommerce.datablitz.com.ph/products/corsair-dominator-titanium-rgb-64gb-2x32gb-ddr5-dram-6000mt-s-cl30-amd-expo-intel-xmp-memory-kit-grey-cmp64gx5m2b6000z30

https://ecommerce.datablitz.com.ph/products/wd-black-sn850x-4tb-nvme-pcie-gen4-x4-m-2-2280-7300mb-s-read-speed-internal-gaming-ssd-without-heatsink-wds400t2x0e

https://ecommerce.datablitz.com.ph/products/teamgroup-t-force-vulcan-z-2tb-2-5-sata-iii-3d-nand-internal-ssd-t253tz002t0c101

https://www.pcworth.com/product/4be2bbbaa4a1?slug=geforce-rtx-5080-asus-prime-oc-16gb-gddr7-black-triple-fan

https://ecommerce.datablitz.com.ph/collections/corsair-rme-series/products/corsair-rme-series-rm1000e-1000w-atx-3-0-80-gold-fully-modular-low-noise-power-supply-black

https://ecommerce.datablitz.com.ph/collections/all/products/fractal-design-meshify-2-computer-case-rgb-black-tg-light-tint-rgb-white-tg-clear-tint-fd-c-mes2a-06-fd-c-mes2a-08

https://gameone.ph/lian-li-uni-fan-sl120-v2-rgb-3x-fan-pack-with-controller-black.html
