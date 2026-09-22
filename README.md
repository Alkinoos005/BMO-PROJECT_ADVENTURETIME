🤖 BMO Project: Bringing Ooo's Beloved Companion to Life


<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/a38b9290-b069-4828-b6c9-76ad0c2b64c5" />


"When bad things happen,I know you want to believe they are a joke,but sometimes life is scary and dark.That is why we must find the light."

🌟 The Vision & Motivation

As an Electrical and Computer Engineering (ECE / ΗΜΜΥ) student,engineering is more than just circuit analysis,signal processing and algorithms,it is the ultimate toolkit to bring imagination into the physical World. 

This project was born out of a genuine love for the iconic animated series "Adventure Time".More specifically BMO (Beemo)is an underrated and beloved character. BMO is not just a device in the Land of Ooo,BMO is a loyal friend,a retro gaming console,a camera,a music player and a living personality with a childlike wonder for the world. 

The primary goal of this project is to bridge nostalgic pop culture with real-world embedded engineering.By combining Hardware Architecture,3D Design & Printing,Embedded Systems and Software Engineering, this project manifests a fully functional, real-world companion inspired by MO Co.'s most special creation.

<img width="1408" height="768" alt="COOL_BMO" src="https://github.com/user-attachments/assets/a809f278-dcfa-42d7-8832-5595457bb18e" />


🧠 Who is BMO? (Lore & Inspiration)

Created by *Moseph "Moe" Mastro Giovanni* at MO Co.,BMO was built differently from thousands of other MO bots.While others were designed for specific industrial or household tasks,BMO was engineered with a unique purpose: "To understand love,play and human emotions!

🗝️ Key Characteristics & Features of BMO:

Multi-Functional Architecture: In the series,BMO functions as a Game Boy-style console,VCR player,alarm clock,synthesizer,flashlight and camera.
Distinct Aesthetics: A retro-futuristic chassis inspired by the classic Game Boy Color,Apple Macintosh and Atari 2600 controllers,rendered in a distinctive teal hue.
Living Companion: Beyond being a machine,BMO possesses a vibrant,imaginative personality who emulates faces,emotions and interactive feedback on its CRT screen.

🛠️ Engineering Overview & System Architecture

Transforming a fictional 2D animated character into a functional hardware project requires an interdisciplinary ECE approach:

<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/1a89becc-174b-48e7-be9f-6863b86781ff" /># BMO-PROJECT 

1) ⚙️ Mechanical & Industrial Design (3D CAD & Printing)
* Custom 3D CAD modeling of BMO's chassis, ensuring correct proportions, side text ("BMO"), slot placements, and internal component mounting rails.
* Tolerancing for button actuation, screen bezels, and ventilation for internal electronics.

<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/852a59ae-08fd-4346-ba1e-2e91aede23c5" />

2) ⚡ Hardware & Electronics Subsystem
a) Processing Unit: Single Board Computer (SBC) or high-performance Microcontroller driving the core OS and display UI.
b) Display Interface: LCD screen configured to render BMO’s animated facial expressions,UI elements and retro games.
c) Audio Engineering: Integrated DAC/Amp board and mini speakers for sound effects,iconic voice lines and media playback.
d) Power Management: Battery-powered operation with embedded charging circuits,voltage regulators and status LEDs.


<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/5c4009f4-d6d2-4316-a8f8-7d26d05b84f4" />

3) 💻 Software & Interactive Interface
a) Custom GUI/UI layer for rendering interactive facial expressions and state animations.
b) Retro gaming emulation integration (e.g., RetroPie / EmulationStation or custom lightweight game engines).
c) Input mapping for custom-wired buttons, directional pads, and peripheral controllers.


<img width="1408" height="768" alt="BMO_COOL" src="https://github.com/user-attachments/assets/5a4a590b-39bd-4a65-874b-49131342dc3c" />

📁 Repository Structure

```gcode
BMO-PROJECT-ADVENTURETIME/
├── 📂 CAD/             # 3D models (.STL, .STEP) for chassis, buttons, and mounts
├── 📂 Hardware/        # Schematic diagrams, PCB layouts, and component BOM
├── 📂 Software/        # Firmware, UI scripts, facial animations, and display logic
├── 📂 Assets/          # Audio files, sprite sheets, and media resources
├── LICENSE             # Open-source MIT License
└── README.md           # Project overview and docume

```

Tools & Assumptions
Tools
3D printer (capable of PLA/PETG)
Soldering iron with fine tip
Wire cutters and strippers
M3 hex key
Heat-set insertion tool (or soldering iron attachment)
Tweezers
Digital Multimeter
Precision screwdriver set
Assumptions
-
3D slicer software installed and calibrated
-
Host computer has Linux flashing utilities available
-
Basic soldering and electronics troubleshooting experience
-
5V USB-C power source available for testing

1.
Fabricate
3/3
1.1
3D print all chassis components and mounts
3D printer (capable of PLA/PETG)
M3 hex key
Precision screwdriver set
BMO Front Shell
3D Print
BMO Rear Shell
3D Print
LCD Screen Mounting Frame
3D Print
Speaker Housing
3D Print
Main Logic Board Mount
3D Print
High Fidelity Audio Mount
3D Print
Tactile Button Covers
3D Print

Hide details
3D print all chassis components and mounts for the BMO bot.

Print BMO Front Shell and Rear Shell using teal PLA with 20% infill and 0.2mm layer height.
Print LCD Screen Mounting Frame in PLA at 40% infill to ensure rigid screen alignment.
Print Main Logic Board Mount and High Fidelity Audio Mount using PETG with 30% infill and 4 perimeters for heat resistance.
Print Speaker Housing using PLA at 100% infill to minimize unwanted acoustic resonance.
Print 8 Tactile Button Covers in PLA at 0.1mm layer height for a smooth finish.
Clean all parts by removing support material and deburring edges for a clean, retro-futuristic fit.

Regenerate
1.2
Post-process prints and remove support material
3D printer (capable of PLA/PETG)
BMO Front Shell
3D Print
BMO Rear Shell
3D Print
LCD Screen Mounting Frame
3D Print
Speaker Housing
3D Print
Main Logic Board Mount
3D Print
High Fidelity Audio Mount
3D Print
Tactile Button Covers
3D Print

Hide details
Clean and prepare all 3D printed components for assembly.

Remove support structures from BMO Front Shell and BMO Rear Shell using flush cutters.
Deburr contact surfaces on the LCD Screen Mounting Frame and Speaker Housing with a hobby knife.
Clean residue from the Main Logic Board Mount and High Fidelity Audio Mount to ensure flat mounting surfaces.
Clear support material from the button holes on the BMO Front Shell for smooth Tactile Button Covers movement.
Test-fit M3 heat-set inserts into all designated mounting holes using a soldering iron at 200°C.

Regenerate
1.3
Install M3 heat-set inserts into mounts
3D printer (capable of PLA/PETG)
M3 hex key
Precision screwdriver set
Brass Heat Set Inserts
Brass Heat Set Inserts
Brass Heat-Set Inserts
LCD Screen Mounting Frame
3D Print
Main Logic Board Mount
3D Print
Speaker Housing
3D Print
BMO Rear Shell
3D Print

Hide details
Install M3 brass heat-set inserts into mounting points on structural components.

Clean out any support material remnants from the hexagonal holes in the LCD Screen Mounting Frame, Main Logic Board Mount, Speaker Housing, and BMO Rear Shell.
Place the M3x5mm Brass Heat-Set Inserts into the designated mounting holes using a soldering iron set to 200°C.
Apply gentle, even pressure until the top of each insert is flush with the printed surface.
Wait 15 seconds for the plastic to solidify around the insert before testing the fit with an M3 machine screw.
Ensure the inserts sit perfectly vertical to prevent misalignment during final chassis assembly.

Regenerate
2.
Wire
5/5
2.1
Solder speaker leads to DAC output terminals
Soldering iron with fine tip
Wire cutters and strippers
Heat-set insertion tool (or soldering iron attachment)
Adafruit 3W 4 Ohm Mono Speaker
Adafruit 3W 4 Ohm Mono Speaker
Voice Speaker
HiFiBerry DAC+ Zero
HiFiBerry DAC+ Zero
High Fidelity Audio

Hide details
Solder the mono speaker leads to the HiFiBerry DAC+ Zero output terminals.

Strip 5mm of insulation from the speaker wires to expose the copper leads.
Tin the exposed speaker leads and the DAC output pads with a small amount of solder.
Solder the positive speaker lead to the DAC_AUDIO_OUT_POS terminal.
Solder the negative speaker lead to the DAC_AUDIO_OUT_NEG terminal.
Slide small pieces of heat-shrink tubing over the joints and apply heat to seal the connections.
Use a multimeter in continuity mode to verify no shorts exist between the two terminals.

Regenerate
2.2
Prepare and connect GPIO jumper cables for I2S bus
Soldering iron with fine tip
Wire cutters and strippers
Heat-set insertion tool (or soldering iron attachment)
Raspberry Pi 4 Model B
Raspberry Pi 4 Model B
Main Logic Board
HiFiBerry DAC+ Zero
HiFiBerry DAC+ Zero
High Fidelity Audio

Hide details
Connect the I2S bus between the Raspberry Pi and High Fidelity Audio board.

Identify the I2S pin set on the Raspberry Pi 40-pin header: GPIO 18 (BCK), GPIO 19 (LRCK), GPIO 21 (DIN), and GND.
Cut four lengths of 28AWG silicone jumper wire, stripping 3mm from each end.
Crimp or solder the wires to match the I2S pin mapping on the High Fidelity Audio board (BCK, LRCK, DIN, and GND).
Slide heat-shrink tubing over each connection and apply heat to insulate the solder joints.
Verify continuity for each wire pair using a multimeter to ensure no shorts exist between adjacent GPIO pins.

Regenerate
2.3
Connect power management rails to main SBC and DAC
Soldering iron with fine tip
Wire cutters and strippers
Heat-set insertion tool (or soldering iron attachment)
Waveshare Power Management HAT
Waveshare Power Management HAT
Battery Management
Raspberry Pi 4 Model B
Raspberry Pi 4 Model B
Main Logic Board
HiFiBerry DAC+ Zero
HiFiBerry DAC+ Zero
High Fidelity Audio

Hide details
Connect power rails from Battery Management HAT to Main Logic Board and DAC.

Measure and cut two 18AWG red and black wires to connect the Battery Management HAT 5V output pins to the Main Logic Board GPIO power pins.
Strip 3mm of insulation from wire ends and tin with lead-free solder.
Solder red wire to the 5V pin and black wire to the GND pin on both the Battery Management HAT and the Main Logic Board GPIO header.
Repeat the process to route an additional 5V and GND connection from the Battery Management HAT power output rails to the High Fidelity Audio DAC board power input pins.
Apply 10mm heat shrink tubing over each solder joint to prevent short circuits.
Use a multimeter to verify 5V continuity between all boards before plugging in the battery.

Regenerate
2.4
Route USB/HDMI cables for display and control interface
Soldering iron with fine tip
Wire cutters and strippers
Heat-set insertion tool (or soldering iron attachment)
Raspberry Pi 4 Model B
Raspberry Pi 4 Model B
Main Logic Board
Waveshare 5inch HDMI LCD (H)
Waveshare 5inch HDMI LCD (H)
Facial UI Display
Zero Delay USB Encoder
Zero Delay USB Encoder
Gaming Input Controller

Hide details
Route HDMI and USB interface cables to connect display and controller to logic board.

Connect the HDMI cable from the Facial UI Display HDMI input port to the Raspberry Pi 4 HDMI output port.
Plug the micro-USB data cable into the Facial UI Display touch interface and a USB 2.0 port on the Raspberry Pi 4.
Attach the USB data cable from the Gaming Input Controller to the second USB 2.0 port on the Raspberry Pi 4.
Use small zip ties to secure cabling to the internal chassis ribs to provide strain relief and maintain airflow.
Verify continuity for the Gaming Input Controller USB data lines using a multimeter to ensure reliable HID input.

Regenerate
2.5
Verify continuity of all power and data lines
Soldering iron with fine tip
Wire cutters and strippers
Heat-set insertion tool (or soldering iron attachment)
Digital Multimeter
Waveshare Power Management HAT
Waveshare Power Management HAT
Battery Management
Raspberry Pi 4 Model B
Raspberry Pi 4 Model B
Main Logic Board
HiFiBerry DAC+ Zero
HiFiBerry DAC+ Zero
High Fidelity Audio
Waveshare 5inch HDMI LCD (H)
Waveshare 5inch HDMI LCD (H)
Facial UI Display
Zero Delay USB Encoder
Zero Delay USB Encoder
Gaming Input Controller
Adafruit 3W 4 Ohm Mono Speaker
Adafruit 3W 4 Ohm Mono Speaker
Voice Speaker

Hide details
Verify electrical continuity across all power rails and data communication buses.

Set digital multimeter to continuity mode and probe the 5V and GND pins between Battery Management and Main Logic Board.
Verify the I2S signal path between Main Logic Board GPIO header and High Fidelity Audio input pins.
Check USB data lines (D+ and D-) continuity from Main Logic Board to Gaming Input Controller and Facial UI Display connectors.
Confirm stable connection between the High Fidelity Audio analog output pins and the Voice Speaker terminals.
Inspect all soldered header connections for electrical shorts using the multimeter probe before applying system power.

Regenerate
3.
Bring-up
4/4
3.1
Flash OS and boot SBC to verify power management
Digital Multimeter
Raspberry Pi 4 Model B
Raspberry Pi 4 Model B
Main Logic Board
Waveshare Power Management HAT
Waveshare Power Management HAT
Battery Management

Hide details
Flash OS to Raspberry Pi and verify power management functionality.

Flash the latest Raspberry Pi OS image onto a microSD card using a secondary PC.
Insert the microSD card into the Raspberry Pi 4 Model B.
Connect the Battery Management HAT to the 40-pin GPIO header and power it via the battery input.
Measure 5V across the Raspberry Pi power pins using a multimeter to ensure stable voltage delivery.
Observe LED status on the Raspberry Pi to confirm successful boot into the Linux environment.

Regenerate
3.2
Initialize display drivers and verify screen output
Digital Multimeter
Raspberry Pi 4 Model B
Raspberry Pi 4 Model B
Main Logic Board
Waveshare 5inch HDMI LCD (H)
Waveshare 5inch HDMI LCD (H)
Facial UI Display

Hide details
Configure Linux display drivers and verify HDMI output for the facial UI.

Connect the Facial UI Display to the Main Logic Board via HDMI and USB.
Boot the system and verify the Facial UI Display is detected by the OS using the command 'xrandr'.
Edit the boot configuration file to force HDMI output and set the resolution to match the 5-inch display.
Install the Waveshare display drivers to enable touch interface support via the USB connection.
Run the facial animation test script to confirm proper display rendering and responsiveness.

Regenerate
3.3
Configure I2S audio kernel modules and test audio output
Digital Multimeter
Raspberry Pi 4 Model B
Raspberry Pi 4 Model B
Main Logic Board
HiFiBerry DAC+ Zero
HiFiBerry DAC+ Zero
High Fidelity Audio
Adafruit 3W 4 Ohm Mono Speaker
Adafruit 3W 4 Ohm Mono Speaker
Voice Speaker

Hide details
Configure I2S kernel drivers and verify audio output on the High Fidelity Audio HAT.

Connect the High Fidelity Audio HAT onto the Raspberry Pi 4 Model B 40-pin GPIO header.
Edit the boot config file to enable the I2S overlay using 'dtoverlay=hifiberry-dac'.
Install the ALSA utilities and select the High Fidelity Audio DAC as the default playback device.
Execute an speaker-test command to verify clear audio output from the 3W 4 Ohm Mono Speaker.
Adjust ALSA mixer volume levels to prevent digital clipping in the mono output stage.

Regenerate
3.4
Calibrate control interface inputs and map button events
Digital Multimeter
Raspberry Pi 4 Model B
Raspberry Pi 4 Model B
Main Logic Board
Zero Delay USB Encoder
Zero Delay USB Encoder
Gaming Input Controller

Hide details
Configure the Gaming Input Controller and map button events within the Linux OS.

Connect the Gaming Input Controller to the Raspberry Pi 4 USB port.
Verify the controller is detected by running 'lsusb' in the Linux terminal.
Install the 'evtest' utility to monitor input event streams from the device.
Run 'evtest' to identify the event path and confirm input registration for every button.
Create a custom udev rule to assign a persistent name to the controller device.
Map the captured input events to BMO's facial animation software using a Python script.

Regenerate
4.
Assemble
4/5
4.1
Mount display to front shell with frame
M3 hex key
Precision screwdriver set
Waveshare 5inch HDMI LCD (H)
Waveshare 5inch HDMI LCD (H)
Facial UI Display
LCD Screen Mounting Frame
3D Print
BMO Front Shell
3D Print

Hide details
Secure the LCD display to the front shell using the 3D-printed mounting frame.

Install six M3x5mm brass heat-set inserts into the mounting points of the BMO Front Shell using a soldering iron.
Align the LCD Screen Mounting Frame with the internal screw bosses on the front shell.
Place the Facial UI Display onto the mounting frame, ensuring the HDMI port is oriented correctly.
Fasten the frame and display assembly to the front shell using M3x16mm machine screws.

Regenerate
4.2
Install control interface and attach tactile button caps
M3 hex key
Precision screwdriver set
Zero Delay USB Encoder
Zero Delay USB Encoder
Gaming Input Controller
Tactile Button Covers
3D Print
BMO Front Shell
3D Print

Hide details
Mount the control interface board and attach tactile button caps to the front chassis.

Press the tactile button caps into the circular apertures on the front face of the BMO Front Shell until they snap into place.
Align the Gaming Input Controller PCB directly behind the button caps, ensuring the tactile switches on the PCB seat into the button caps.
Secure the Gaming Input Controller to the front chassis using M3 machine screws through the designated mounting bosses.
Verify the button travel distance to ensure the caps do not bind against the BMO Front Shell bezel.

Regenerate
4.3
Secure logic board and DAC to rear shell using standoffs
M3 hex key
Precision screwdriver set
Raspberry Pi 4 Model B
Raspberry Pi 4 Model B
Main Logic Board
Main Logic Board Mount
3D Print
HiFiBerry DAC+ Zero
HiFiBerry DAC+ Zero
High Fidelity Audio
High Fidelity Audio Mount
3D Print
SBC Mounting Standoffs
SBC Mounting Standoffs
Misc
BMO Rear Shell
3D Print

More details
4.4
Mount speaker driver into acoustic housing
M3 hex key
Precision screwdriver set
Adafruit 3W 4 Ohm Mono Speaker
Adafruit 3W 4 Ohm Mono Speaker
Voice Speaker
Speaker Housing
3D Print
BMO Rear Shell
3D Print

Hide details
Secure the voice speaker into the 3D-printed acoustic housing.

Place the speaker driver into the Speaker Housing cavity with the diaphragm facing outward.
Align the speaker mounting holes with the molded standoffs inside the Speaker Housing.
Insert M3x5mm brass heat-set inserts into the Speaker Housing mounting holes using a soldering iron.
Fasten the speaker to the housing using M3 machine screws until firm to ensure an airtight acoustic seal.

Regenerate
4.5
Fasten front and rear shell assembly with M3 screws
M3 hex key
Precision screwdriver set
BMO Front Shell
3D Print
BMO Rear Shell
3D Print
Case Assembly Screws
Case Assembly Screws
Misc

Hide details
Secure the BMO front and rear shells using M3 screws.

Align the BMO front shell and BMO rear shell ensuring internal components clear all mounting points.
Verify that the battery management board and internal wiring are not being pinched between the shells.
Insert six M3x16mm assembly screws through the rear shell into the front shell's integrated mounting posts.
Tighten each screw in a cross-pattern until snug, ensuring the shell seam is flush and even.

<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/c7b0f3c0-b747-4639-8d43-c71e1d6ef879" />
 
 🚀🛰️And there's BMO in space!!!

