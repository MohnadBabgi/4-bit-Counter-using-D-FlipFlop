# 4-Bit Counter Using D-Flip Flops

A digital circuit project demonstrating a 4-bit binary counter using D-flip flops. This counter cycles through binary states from `0000` to `1111` and resets, with synchronized clock and reset controls.

---

---

## 🚀 Project Overview  
This project implements a **4-bit synchronous counter** using D-flip flops. The counter advances through binary states (`0000` to `1111`) with each clock pulse, resetting to `0000` after reaching the maximum value. Key features include:  
- **Synchronized clock input** via a button.  
- **Reset functionality** to initialize the counter.  
- **Visual output** using LEDs for each bit.  

---

## 🔧 Circuit Components  
- **4 D-Flip Flops**: Core components for storing and transferring bits.  
- **4 LEDs**: Visual indicators for binary outputs (LED3 = MSB, LED0 = LSB).  
- **Clock Button**: Generates pulses to advance the counter.  
- **Reset Button**: Resets all flip-flops to `0000`.  

---

## ⚙️ How It Works  
### Step-by-Step Operation  
1. **Initialization**  
   - On power-up or reset, all flip-flops are set to `0000`.  

2. **Clock Pulse**  
   - Pressing the clock button sends a pulse to all flip-flops simultaneously.  

3. **State Transition**  
   - Each flip-flop updates its output based on the previous stage’s output (Q → D of next flip-flop).  

4. **Binary Counting**  
   - The counter increments by `1` with each pulse, cycling from `0000` to `1111`.  

5. **LED Display**  
   - LEDs light up to represent the current binary value (e.g., `1010` = LED3 ON, LED2 OFF, LED1 ON, LED0 OFF).  

6. **Reset**  
   - Pressing the reset button forces all outputs back to `0000`.  

---

  
