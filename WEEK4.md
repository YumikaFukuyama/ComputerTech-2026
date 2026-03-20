# Unit 1 Blueprint of Bits (數位藍圖：進位與編碼) 🏗️, W02-W03
### Lab 20: Digital Sampling (數位採樣：現實轉數位)

<img width="432" height="131" alt="image" src="https://github.com/user-attachments/assets/7dc5b752-b8f7-4c0d-84fe-e58490226206" />

### 1. What is a Bit?  
A bit (binary digit) is the smallest unit of data in a computer. It can be either 0 or 1

If you have n bits, you can represent:
- 2^n different values

Examples:

- 1 bit → 2 values
- 8 bits → 256 values
- 32 bits → about 4.3 billion values

### 2. Thermometer Example (Analog vs Digital)

**Mercury Thermometer (Analog)**  
- Uses continuous physical change (mercury expansion)
- Infinite possible values (in theory)
- You read the scale manually

**Digital Thermometer**  
- Uses a sensor + ADC (Analog-to-Digital Converter)
- Converts temperature into digital values

Typical case:  
- Range: 32.0°C to 42.0°C
- Precision: 0.1°C

Number of steps:
- (42.0 - 32.0) / 0.1 = 100 steps

Bits needed:
- 2^7 = 128 → enough

**Display: about 7–8 bits**
**Internal measurement: often 12–16 bits for higher accuracy**

### 3. IPV6  
IPv6 uses 128 bits.  

**Total addresses:**  
- 2^128 ≈ 3.4 × 10^38  
This is extremely large.

**Reasons IPv6 exists:**  
- IPv4 ran out of addresses
- More devices (phones, IoT, etc.)

**Advantages:**
- Huge address space
- Better routing and efficiency
- Built-in support for modern networking

**Example IPv6 address:**
- 2001:0db8:85a3:0000:0000:8a2e:0370:7334
- Shortened form: 2001:db8:85a3::8a2e:370:7334

### 4. Comparing Bit Scales
Bits	Number of Values	Meaning
30 bits	~1 billion	small ID space
32 bits	~4.3 billion	IPv4
128 bits	huge (10^38)	IPv6

**(1) Check System Bit (32-bit or 64-bit)**
<img width="1000" height="654" alt="image" src="https://github.com/user-attachments/assets/610c105f-43aa-49d9-b5fc-32609d146ba2" />

**(2) Check Your IP Address**
<img width="681" height="409" alt="image" src="https://github.com/user-attachments/assets/580d7821-2438-45a4-bf24-476c4fe8ce69" />

## CMOS - CMOS = Complementary Metal-Oxide-Semiconductor(相補型金属酸化膜半導体)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/219b20d0-a11a-4315-8861-a023c10b1811" />


1️⃣ Basic Structure

A CMOS circuit uses two types of transistors:  

‐ Type	Name	Behavior  
- P-type MOSFET	PMOS	Conducts when voltage is low, blocks when high
- N-type MOSFET	NMOS	Conducts when voltage is high, blocks when low

“Complementary” means PMOS and NMOS are paired so that one conducts while the other blocks.

2️⃣ Representing 0 and 1 (bit perspective)

Input = 1 (high voltage):  
→ NMOS conducts → current flows to ground

PMOS blocks → no current from Vdd  
→ Output = 0 (low voltage)

Input = 0 (low voltage):  
→ NMOS blocks → no current to ground

PMOS conducts → current flows from Vdd  
→ Output = 1 (high voltage)

So, logic 0 and 1 are represented by voltage levels, controlled by complementary transistor pairs.

3️⃣ Why CMOS uses low power  

- Only one transistor conducts at a time
- When storing a bit (0 or 1), almost no current flows
- Makes CMOS very energy-efficient and produces little heat

4️⃣ Applications  

- CPUs, memory, and logic ICs
- CMOS image sensors in cameras are a practical application of the same technology

---

Key points:

1.Two types of switches (transistors)
- PMOS → “on” when voltage is low
- NMOS → “on” when voltage is high

2. They work together so that only one conducts at a time.
- Represents 0 and 1
- High voltage → 1
- Low voltage → 0

This is how computers read and store information.

3. Very energy-efficient
- Almost no power is used when storing a 0 or 1
- That’s why CPUs and memory chips use CMOS technology.

4. Where you see it
- CPU and memory chips in computers
- Camera sensors in phones and digital cameras
- Small memory in PCs that stores BIOS settings (kept alive by a little battery)

CMOS is a type of chip technology that lets computers and devices handle bits (0 and 1) efficiently with very little power.












