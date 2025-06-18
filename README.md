# Binary Calculator in Proteus

**𝗙𝘂𝗹𝗹𝘆 𝗳𝘂𝗻𝗰𝘁𝗶𝗼𝗻𝗮𝗹 𝗯𝗶𝗻𝗮𝗿𝘆 𝗰𝗮𝗹𝗰𝘂𝗹𝗮𝘁𝗼𝗿 𝗶𝗻 𝗣𝗿𝗼𝘁𝗲𝘂𝘀**  
**𝟰-𝗯𝗶𝘁 𝗮𝗻𝗱 𝟴-𝗯𝗶𝘁 𝗼𝗽𝗲𝗿𝗮𝘁𝗶𝗼𝗻𝘀**

This project simulates a digital binary calculator using **Proteus Design Suite**, designed for academic understanding and demonstration of **combinational logic circuits**.

---

## Features

- **4-bit and 8-bit operation modes**
- **Arithmetic**: Addition, Subtraction, Multiplication
- **Logic operations**: AND, OR, NOT, XOR
- **BCD Output** with Double Dabble Algorithm
- **LED indicators** for overflow and operation status
- **7-Segment Display** interface using 7447 BCD decoders

---

## 🛠 Components Used

| Component               | Purpose                                 |
|------------------------|-----------------------------------------|
| Logic Gates            | AND, OR, NOT, XOR operations            |
| 2:1, 4:1 MUX           | Operation selection                     |
| 4-bit & 8-bit Adders   | Arithmetic logic unit (ALU)             |
| Multipliers            | Binary multiplication                   |
| DIP Switches           | User inputs (A, B, and operator select) |
| 7447 BCD Decoder       | Binary to 7-segment conversion          |
| 7-Segment Display      | Visual output                           |
| LEDs                   | Indicate overflow and mode (optional)   |

---

## How It Works

- The user selects two binary inputs using **DIP switches**
- An **operation selector** chooses the required function
- A custom ALU executes the operation using logic gates and multiplexers
- The **result** is decoded (if needed) and shown on one or more 7-segment displays
- **Overflow** from 8-bit operations is handled via additional LEDs or displays
- For 16-bit multiplication results, the **Double Dabble algorithm** is used to convert binary to BCD before display

---

## Author

* **Taha Ebaad**

> *This project was developed as part of the Digital Logic Design final project.*