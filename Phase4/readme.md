# Phase 4

In this segment I will focus on embedded electronics project keeping mechatronics as base.

Days can vary by ±2 

If any additional material, code is required it will be updated in this directory only.

I built a mechatronics project which was pending from a lot of time!

## SliderX
![SliderX](https://user-images.githubusercontent.com/40523329/142217890-5adcf6f6-8a22-4789-9440-02a3cd86a1b8.png)

---

<details>
  <summary>Hardware</summary>
  Main components of hardware includes:

  - Aluminum Extrusion [20x40]
  - Belt Tensioner
  - V Slot Gantry
  - 3D printed Enclosures
  - Camera Holder 2.5" [Small Ball Head]
  - Tripod Mounting [7.9375mm - 16 Thread]

  3D Print includes:
  - Main Enclosure
  - End Cap
  - V Gantry
  - Tripod Mount
  - Eccentric spacer
  - Aluminum spacer
  
|      Name      | Weight [gm] | Time [In Hr] |
|:--------------:|:-----------:|:------------:|
| Main Enclosure |     100     |     11.9     |
|  End Enclosure |      29     |      3.8     |
|  Bottom Cover  |      14     |      1.3     |
|    Top Cover   |      14     |       1      |
|   Logo Cover   |      8      |       1      |
|                |    165 gm   |    19.3 Hr   |

  ##
</details>

<details>
<summary>Electronics</summary>


 Main component of electronics development includes PCB development and due to limited knowledge there are currently 3 versions!
 
  v1.0.0 [Problems]
  ![v1.0.0](https://user-images.githubusercontent.com/40523329/147377180-92331d32-7ed9-4937-982a-24a57e2fc3eb.jpg)

  - Small Size
  - no mounting holes
  - small ESP32 placement
  - no resistors for GPIO out
  - no indicator LEDs
  - missing silk screen notations

  v1.1.0 [Problems]
  ![v1.1.0](https://user-images.githubusercontent.com/40523329/147377199-5b99902d-9b1f-4126-aa9a-a5f2b0eba900.jpg)

  - fixed issues from v1.0.0
  - buttons 3.3v input missing
  - add 4 indicator LEDs
  - new size : 75x50mm
##
</details>

<details>
<summary>Product Development</summary>

It includes a number of factors to make a product and most important this project is based on DIY approach [There are still some hardware design problems pending].

Main components includes : UI / UX / Firmware development

1. UI / UX
In SliderX easy to use interface is preffered with advanced features for PRO users:
![UI](https://user-images.githubusercontent.com/40523329/147377271-b9d73269-af43-4791-bed5-abb91bd94d5b.png)

Webserver implementation including:
 - Websockets implementation
 - API callback

</details>

Many problems arrised while making this project, it might be better to work on them before starting a mechatronics project:
 - PCBs recieved from china took too much long time [Vendor : ALLPCB]
 - V-slot wheels should be purchased along with v-slot gantry combo [More economical and strong compared to 3D printed]
 - PCB design not reviewed correctly [Check your circuits first on breadboard and get it reviewed from your mentor]

---

[Go back home](https://github.com/AnshumanFauzdar/100DaysOfHardware)