
🧮 Advanced Calculator – Java Swing GUI
📌 Overview
This project is a Multi-Mode Advanced Calculator built using Java Swing. It features a clean, interactive GUI interface with multiple operational modes suited for everyday use, scientific calculations, and programming-related computations. It also includes a history tracker and settings customization.

The goal is to provide a user-friendly, extendable, and functional calculator with the feel of a physical scientific calculator and the flexibility of a digital tool.

🎯 Features
🔀 Multi-Mode System
![Calculator 6_23_2025 10_12_25 PM](https://github.com/user-attachments/assets/4c648fe2-a30a-47c7-97de-9f51c580eee0)

The calculator provides several distinct operational modes accessible from a side menu:

Main Mode: Basic arithmetic operations.

Functional Mode: Includes advanced functions like trigonometric, logarithmic, and exponential functions.

Programmer Mode: Binary, hexadecimal conversions and bitwise operations.

History: Shows previous calculations performed during the session.

🔣 Scientific & Functional Operations
![Calculator 6_26_2025 8_24_58 PM](https://github.com/user-attachments/assets/757ff81c-f9a4-4e67-913e-20a69eb3e46d)

The Functional Mode adds advanced operations:

sin, cos, tan, cot

√ (square root), ∛ (cube root), n√x (nth root)

x^y, e^x, 10^x

log (base 10), ln (natural logarithm)

π, e, ! (factorial)

1/x, |x| (absolute value), x², ½, %

🧠 Memory & History Support

Memory Buttons:

M+: Add current value to memory.

M-: Subtract current value from memory.

MR: Recall memory.

MC: Clear memory.

History:
![Calculator 6_26_2025 8_23_54 PM](https://github.com/user-attachments/assets/578a81ab-9f9d-4210-9561-ee290c029f47)

Track all calculations.

Accessible from the side menu (History 📜).

Can be extended to support saving to file.

🛠️ Settings Panel
![Calculator 6_26_2025 8_24_50 PM](https://github.com/user-attachments/assets/67167702-8386-45ed-8889-9f9e633a67a0)

The settings menu (⚙️) allows the user to:

Toggle dark/light mode (future expansion).

Change angle unit (degrees/radians).

Set themes or font sizes.

Enable/disable sound or click feedback (optional).

🖼️ GUI Breakdown
The GUI consists of:

Side Menu Panel:

Navigation between modes.

Settings access.

Display Panel:

Dual-line text field: input & output.

Button Grid:

Organized by color and category:

Orange: Actions like DEL, AC, arithmetic.

Blue: Functional/scientific operations.

Grey: Numeric pad (0–9).

Dark: Mode/logic-related toggles.

🛠️ Technologies Used
Java (JDK 17+)

Java Swing

NetBeans GUI Builder (Matisse) – for WYSIWYG interface design.

Custom Java Math Parser or integrated use of javax.script.ScriptEngine for expression evaluation.

📁 Project Structure
plaintext
Copy
Edit
src/
│
├── calculator.java
🧪 Example Calculations
Input	Output
sin(30)	0.5
5 + 6 × (2 ^ 3)	53
log(100)	2
`	-12
5! + 2^4	144
π × r² (r = 3)	28.27

🧩 Possible Extensions
Graphing Mode: Plotting equations (y = f(x)).

Programming Mode Enhancements: Hex ↔ Binary ↔ Decimal, AND/OR/XOR/NOT.

Unit Conversion Mode: Temperature, Length, Weight, etc.

Keyboard Shortcuts: For faster input.

Mobile Version: Convert GUI to be responsive using JavaFX or port to Android.

🔧 Installation & Running
Requirements:
Java 17 or higher.

NetBeans IDE (recommended for editing GUI).

Swing library (included in JDK).

Running:
bash
Copy
Edit

🤝 Contributing
Contributions are welcome! You can:

Report bugs.

Suggest new features.

Submit pull requests to enhance functionality or UI.

🧑‍💻 Author
Developer: ESA
Language: Java
Design Tool: NetBeans Swing Builder

📜 License
This project is licensed under the MIT License – feel free to use, modify, and distribute.
