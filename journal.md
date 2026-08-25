  B2 FC  — Project Journal

Project: Flight Controller PCB
Software Used: EasyEDA Pro
Total Time Taken: 13 Hours
Designed By: Omer Ruknuddin
<img width="2160" height="1412" alt="3D_PCB1_2026-08-25" src="https://github.com/user-attachments/assets/7e92b69e-0f63-49a7-9861-c2aaee1fbc69" />

1. Creation of the Schematic — 3 Hours 35 Minutes

Firstly, I began work on the creation of the schematic for the flight controller. For this, my first task was to create the project itself and add the main elements which I will use in this schematic.

For example, I imported STM microcontroller and then I added USB-C controller, LEDs, 5V 2A BEC, flash memory, I2C connectors, and all the buses. After adding all the elements, I began to place them and make connections between the elements.

It is necessary to note that at the beginning, I spent more time doing this step because I needed to make sure about the correctness of the structure of the flight controller at this stage.
<img width="1124" height="498" alt="Screenshot 2026-08-16 230838" src="https://github.com/user-attachments/assets/172670d8-ce1b-47fb-912f-6a0077814424" />

2. Pinouts and Connections — 1 Hour

After completing the initial schematic, I moved on to the different pinouts and solder pads needed for the board.

I created and labelled the connections for things such as ESC power, camera, VTX, and the boot switch. I also added the required decoupling connections and the 3.3V regulator section. I made sure the different pads and pinouts were clearly named so that they would be easier to work with later during the PCB layout.
<img width="1020" height="288" alt="Screenshot 2026-08-17 231019" src="https://github.com/user-attachments/assets/31aa084d-3dc5-46d1-a4b7-43143f334771" />

3. Finalizing the Schematic — 2 Hours 40 Minutes

After the basic connections were completed, I went on to complete the rest of the schematic.

I placed the gyro sensor and connected it with all the necessary components. At the same time, I placed the DJI connector, camera connector, ESC connectors, buzzer, diode, and other components of the circuit.

The schematic began to resemble a proper flight controller and not just a bunch of separate components. I checked all the connections between the components and ensured that they were correctly connected before proceeding with the PCB.

Having finished the schematic, I created the board outline.
<img width="1233" height="739" alt="Screenshot 2026-08-22 132757" src="https://github.com/user-attachments/assets/6358d6d2-b05a-4cc3-9e89-4be2dd5d1b1a" />
<img width="1287" height="655" alt="Screenshot 2026-08-22 132640" src="https://github.com/user-attachments/assets/186ac26b-dc16-4af7-85fa-7457fffda0f8" />
<img width="961" height="562" alt="Screenshot 2026-08-20 194934" src="https://github.com/user-attachments/assets/89da5611-b0b8-4233-96d8-1e28f6f3af88" />

4. Component Placement and Design Rules — 1 Hour 48 Minutes

With the schematic completed, I converted the design into the PCB layout and started placing the components.

I spent time deciding where each component should go based on its purpose, connections, and the available space on the board. I tried to keep the important components properly positioned while also leaving enough space for routing.

I also configured the PCB design rules and layer settings. Since the board had a lot of connections and components, I had to carefully set up the layers and clearances before starting the routing.

<img width="1905" height="842" alt="Screenshot 2026-08-24 004001" src="https://github.com/user-attachments/assets/bd488f8d-1b5b-4dcb-b632-ca5ed92c3de8" />
<img width="1233" height="722" alt="Screenshot 2026-08-24 004109" src="https://github.com/user-attachments/assets/4abd3d87-777c-4b43-9ac0-f9930544b402" />

5. PCB Routing and Error Correction — 4 Hours

Routing the PCB was the last and longest step.

In the beginning, I started routing between the components, moving gradually from one section of the board to another. I faced some errors in design rules and clearances while routing, so I needed to change some design rules and routes to fix these errors.

I checked the connections, cleared the DRC errors, changed the tracks if necessary and continued the routing process. Some of the errors needed the changes in clearances and other parameters of the PCB to complete the routing correctly.

Once the routing was done, I passed the final touch-up on the board. I checked the connections, polished the routing, corrected the errors and finished the PCB layout.
<img width="1520" height="726" alt="Screenshot 2026-08-25 181156" src="https://github.com/user-attachments/assets/b84dc998-1797-4088-a75e-4b3f5747f1bd" />
<img width="770" height="472" alt="Screenshot 2026-08-24 224548" src="https://github.com/user-attachments/assets/f385f6ce-6997-4c21-b1cc-67fd993397f2" />
<img width="1510" height="712" alt="Screenshot 2026-08-24 224751" src="https://github.com/user-attachments/assets/f04596dc-c495-4a8c-a1ed-7aecdb418773" />

Final Result
<img width="2160" height="1392" alt="PCB_PCB1_2026-08-25" src="https://github.com/user-attachments/assets/9204c014-b2aa-440d-8f2f-401a61c0a6b8" />
<img width="2160" height="1412" alt="3D_PCB1_2026-08-25" src="https://github.com/user-attachments/assets/ef386519-eb23-471a-910b-46a8729dead2" />
<img width="2160" height="1434" alt="3D_PCB1_2026-08-25 (1)" src="https://github.com/user-attachments/assets/c2fd3474-7790-47a6-8533-15cdee8041e3" />

Finally, after 13 hours of work, I have finished designing the flight controller PCB. The project helped me go through the entire process starting with the creation of the schematic and selection of the components and finishing with the PCB routing and DRC correction.

My main tasks were the creation of the schematic, the addition and connection of the STM microcontroller and other components, the preparation of different connectors and pinouts, the board outline creation, components placement, the setup of the layers and design rules of the PCB, routing and error correction.

Generally, this project helped me understand the PCB creation process much better and pay proper attention to the routing and DRC part of the process.
