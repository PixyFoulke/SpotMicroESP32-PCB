<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="https://raw.githubusercontent.com/PixyFoulke/SpotMicroESP32-PCB/main/images/logo.png" alt="Logo" width="300" height="300">

  <h3 align="center">SpotMicroESP32-PCB</h3>

  <p align="center">
    Custom PCBs designed for SpotMicroESP32-Leika  
    <br />
    <a href="https://github.com/PixyFoulke/SpotMicroESP32-PCB/tree/main/pcbs"><strong>« Explore PCBs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/pixyfoulke/SpotMicroESP32-PCB/issues/new?labels=bug&template=bug-report.md">Help</a>
    &middot;
    <a href="https://github.com/pixyfoulke/SpotMicroESP32-PCB/issues/new?labels=enhancement&template=feature-request.md">Request Variation</a>
  </p>
</div>

---
> IMPORTANT: ⚠️  
> Each ESP32 Microcontroller variant has different pin row spacing. Please select the PCB that *__will__* fit your board without stress on the pins.

> IMPORTANT: ⚠️  
> The maximum number of pins that your ESP32 can have and still use the breakout board is **40** total. If your board has more than 40, you **have** to use jumper cables to connect to the pins found on the PCB.


  
## **- - - PCB VARIANTS - - -**
<div align="left">
    <img src="https://raw.githubusercontent.com/PixyFoulke/SpotMicroESP32-PCB/main/images/pcbvariants.png" alt="Variants" width="300" height="300">
</div>
<details>
  <summary>Expand PCB Variants</summary>
  
  ### **Header Pin Spacing (Open to see measurement)**
  <details>
    <summary>Expand Row Spacing Variants (Click Image To Inspect)</summary>
    <details>
      <summary>P=17mm</summary>
      <a href="https://github.com/PixyFoulke/SpotMicroESP32-PCB/tree/main/pcbs/17mm">
        <img src="https://raw.githubusercontent.com/PixyFoulke/SpotMicroESP32-PCB/main/images/17mm.png" alt="17mm" width="250">
      </a>
    </details>
    <details>
      <summary>P=18.5mm</summary>
      <a href="https://github.com/PixyFoulke/SpotMicroESP32-PCB/tree/main/pcbs/18_5mm">
        <img src="https://raw.githubusercontent.com/PixyFoulke/SpotMicroESP32-PCB/main/images/18_5mm.png" alt="18.5mm" width="250">
      </a>
    </details>
    <details>
      <summary>P=20mm</summary>
      <a href="https://github.com/PixyFoulke/SpotMicroESP32-PCB/tree/main/pcbs/20mm">
        <img src="https://raw.githubusercontent.com/PixyFoulke/SpotMicroESP32-PCB/main/images/20mm.png" alt="20mm" width="250">
      </a>
    </details>
    <details>
      <summary>P=21mm</summary>
      <a href="https://github.com/PixyFoulke/SpotMicroESP32-PCB/tree/main/pcbs/21mm">
        <img src="https://raw.githubusercontent.com/PixyFoulke/SpotMicroESP32-PCB/main/images/21mm.png" alt="21mm" width="250">
      </a>
    </details>
    <details>
      <summary>P=22mm</summary>
      <a href="https://github.com/PixyFoulke/SpotMicroESP32-PCB/tree/main/pcbs/22mm">
        <img src="https://raw.githubusercontent.com/PixyFoulke/SpotMicroESP32-PCB/main/images/22mm.png" alt="22mm" width="250">
      </a>
    </details>
    <details>
      <summary>P=23mm</summary>
      <a href="https://github.com/PixyFoulke/SpotMicroESP32-PCB/tree/main/pcbs/23mm">
        <img src="https://raw.githubusercontent.com/PixyFoulke/SpotMicroESP32-PCB/main/images/23mm.png" alt="23mm" width="250">
      </a>
    </details>
  </details>
</details>

---

## **- - -**
<div align="left">
    <img src="https://raw.githubusercontent.com/PixyFoulke/SpotMicroESP32-PCB/main/images/hardware.png" alt="Variants" width="300" height="300">
</div>
<details>
  <summary>Click to expand Hardware Overview</summary>

  <a href="https://github.com/PixyFoulke/SpotMicroESP32-PCB/tree/main/images/board.png">
    <img src="https://raw.githubusercontent.com/PixyFoulke/SpotMicroESP32-PCB/main/images/board.png" alt="PCB Design" width="300">
  </a>

  _This PCB layout is specifically designed for SpotMicroESP32-Leika._
</details>

---

## **- - - GETTING STARTED - - -**
<div align="left">
    <img src="https://raw.githubusercontent.com/PixyFoulke/SpotMicroESP32-PCB/main/images/gettingstarted.png" alt="Variants" width="300" height="300">
</div>
<details>
  <summary>Click to expand Getting Started</summary>
  
  > IMPORTANT: ⚠️  
  > **SOLDERING IRON REQUIRED!**  
  > You will need to **manually solder** some components onto the PCB.

  ### **Setup Instructions**
  1. **📥 Download Gerber Files:**  
  - Available in the [PCBs directory](https://github.com/pixyfoulke/SpotMicroESP32-PCB/tree/master/pcbs).
    
  2. **🔩 Create BOM**  
     - Once you have selected the PCB variant, there is a folder called "/parts/". Edit the ".csv" file to fit the format of your selected manufacturer.

  3. **🛒 Order PCB:**  
     - Upload Gerber files to a PCB manufacturer (e.g., [JLCPCB](https://jlcpcb.com/)).  

  4. **🔧 Assemble PCB:**  
     - Solder components as per the schematic.  

  5. **🖇️ Connect Components:**  
     - Refer to the **[SpotMicroESP32-Leika](https://github.com/runeharlyk/SpotMicroESP32-Leika)** documentation.  

  6. **🔌 Upload Firmware:**  
     - Flash the **ESP32 microcontroller** with the SpotMicroESP32-Leika firmware.  
</details>

---

## **- - - MIT LICENSE - - -**
<div align="left">
    <img src="https://raw.githubusercontent.com/PixyFoulke/SpotMicroESP32-PCB/main/images/mitlicense.png" alt="Variants" width="300" height="300">
</div>
<details>
  <summary>Click to view License</summary>

  This project is licensed under the **MIT License**. See [LICENSE](https://github.com/pixyfoulke/SpotMicroESP32-PCB/blob/master/license) for details.  
</details>

---

## **- - - ACKNOWLEDGEMENTS - - -**
<div align="left">
    <img src="https://raw.githubusercontent.com/PixyFoulke/SpotMicroESP32-PCB/main/images/acknowledgements.png" alt="Variants" width="300" height="300">
</div>
<details>
  <summary>Expand Acknowledgments</summary>

  **Special thanks to:**

  - **Rune Harlyk** – Creator of **SpotMicroESP32-Leika**  

  - **SpotMicroAI Community** – [Join the Discord](https://discord.gg/WwefSZczQA)  
</details>

---

## **- - - HELP SERVICES - - -**
<div align="left">
    <img src="https://raw.githubusercontent.com/PixyFoulke/SpotMicroESP32-PCB/main/images/helpservices.png" alt="Variants" width="300" height="300">
</div>
<details>
  <summary>Expand</summary>

  👋 Contact Us!

  - **PixyFoulke** – PCB design & assembly inquiries; Discord Username: "_pixy."

  - **Rune Harlyk** – [GitHub Discussions](https://github.com/runeharlyk/SpotMicroESP32-Leika/discussions)  

  - **SpotMicroAI Community** – [Join Discord](https://discord.gg/WwefSZczQA)
    <details>
    <summary>FAQ</summary>
      
      Q: Who are you?
      
      A: Hi! I'm Jaxlyn or "PixyFoulke", I'm a 17 year old highschool aerospace engineering intern from Columbus, Ohio. I've been studying all aspects of engineering since before I could speak. I use 


    Q: How much does the PCB cost?

    A: Depends on the cost of the parts, but for me (JLCPCB), $60. If the cost is too high and you're younger than 19, check out [OnBoard](https://github.com/hackclub/OnBoard)


    Q: Why?

    A: I made this PCB after a failed hackathon attempt. Due to the small space, and the high density of wires used, there was a very high likelyhood of wires shorting, and smoke (this happened a LOT).


    Q: Will any ESP32 work?
    
    A: Yes. As long as the board has SDA and SCL pin(s), it will work. If your board has 18 pins, or 22 pins (up to 40 total pins), it will work. But you will have empty unused pins (which is completely fine).
    
    Q: How do I edit the PCB files?
    
    A: Download and Install KiCAD, open your specific PCB project (found in /pcbs/{selected_spacing}/). Here's basic learning resources for beginners: [Here](https://learn.sparkfun.com/tutorials/beginners-guide-to-kicad)
    
    Q: Can you do it for me?
    
    A: Two answers yes (see below) and no. If you need help with the PCB, DM PixyFoulke (see above). If you need help with Leika, open a GitHub Discussion [here](https://github.com/runeharlyk/SpotMicroESP32-Leika/discussions). After making edits/fixes, feel free to open a PR to have it added to this repository!  

    > **Important ⚠️**  
    > If you want me (PixyFoulke) to assemble the PCB and ship it to you, you will have to pay an **$80 deposit upfront**. Once it's in transit, you **must** pay the remaining balance.  
    > If you fail to pay within 48 hours (some exceptions may apply, but must be communicated via email), the **$80 deposit is non-refundable** for damages and losses.  

    A #2: Yes, if you live in North America, I (PixyFoulke) can order, assemble, and deliver the completed and tested PCB for you. However, you will need to cover all costs, including PCB manufacturing, parts, assembly, and shipping.  

    **Full Cost Breakdown:**  
    - **PCB cost:** ~$70  
    - **Labor cost (Soldering components):** ~$20  
    - **Part cost:**  
      - [PCA9685](https://a.co/d/jlCFAqK)  
      - [MPU6050](https://a.co/d/4rnn9Vi)  
    - **(Optional) Personalized 3D-Printed Mounting Plate** ($5) *(Files in `/pcbs/` folder)*  
    - **Shipping Cost:** TBD (You must pay this ahead of time)  

    **Subtotal:** $120 + Shipping + (Optional: Personalized Mounting Plate)  




    Q: How do I connect the pins?
    
    A: Use short jumper wires (Female-To-Male dupont) to connect the exposed male header pins to the exposed 
    
    </details>
</details>

--- 
🎯 **Want to contribute?** Fork the repo, submit PRs, and help improve the project!