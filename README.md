# jalrakshak-prototype-
# JalRakshak AI 
### IoT + AI Waterless Cooling System for Data Centers

> "Protecting Water. Powering Tomorrow."

JalRakshak AI is an innovative, 100% waterless cooling system designed for data centers in India. By combining Phase Change Materials (PCM) with IoT edge intelligence, it eliminates water consumption entirely while cutting cooling costs by 40%. 

Built for the **SEVA Innovation Challenge 2026** under the *Sustainable Technology & Green Innovation* track.

## Live Prototype
Click the link below to view the interactive web-based simulation:
--> **[]**

---

# How to Operate the Prototype

Follow these exact steps to explore the two simulations:

**Step 1: Open the Hub**
* Click on the **[Live Prototype Link]** provided above.
* You will land on the main JalRakshak AI menu page. From here, you can choose your demo.

**Step 2: Explore the Thermal Simulation (The Concept Pitch)**
* From the menu page, **click on "Thermal Simulation"**.
* **Page 1 (Hardware):** View the breakdown of the ₹15,000 cost. Click the blue button at the bottom that says **"Launch Thermal Simulation"**.
* **Page 2 (Traditional Cooling):** Observe how traditional water cooling wastes resources. Click the blue button **"Upgrade to JalRakshak"**.
* **Page 3 (The JalRakshak Solution):** Use the **Adjust Simulation Temperature slider** on the right. Drag the slider from 30°C up to 80°C. Watch how the paraffin wax melts (turns blue) and how the fans automatically kick in at 42°C to cool the rack.

**Step 3: Explore the Live IoT Dashboard**
* Go back to the main menu page.
* **Click on "IoT Live Dashboard"**.
* Watch the live telemetry data update in real-time across the 3 server racks. Notice the "Total water saved" counter ticking up.
* **Test the AI:** Click the button that says **"Simulate heat spike (+15°C)"**. Watch how the system predicts the heat, the PCM liquid percentage jumps, and the smart fans spin up instantly to save the servers.
* Click **"reset normal load"** to return the racks to normal operating temperatures.

---

## How It Works (The Two-Layer System)
1. **Passive Thermal Storage (PCM):** We use Paraffin Wax (RT-42) placed next to server heat sinks. When servers heat up, the wax melts at 42°C, absorbing massive amounts of heat (200 kJ/kg) without using a single drop of water or electricity.
2. **Active IoT Intelligence:** An ESP32 microcontroller and DHT22 sensors read temperatures every 5 seconds. AI algorithms predict thermal spikes 30 minutes in advance and automatically scale the cooling fans (0%, 50%, or 100%) to optimize energy use.

## Hardware & Software Stack
* **Hardware:** ESP32, DHT22 Sensors, 12V DC Fans, Paraffin PCM, Aluminum Heat Sinks.
* **Software:** HTML5, CSS3, Vanilla JavaScript (for the Web Simulation), MQTT, Firebase (concept architecture).
* **Cost:** ~₹15,000 per rack with a 13-month payback period.

## Repository Contents
* `index.html` - The landing page/hub linking to both prototypes.
* `simulation.html` - A 3-stage interactive presentation showing hardware, traditional cooling problems, and the JalRakshak PCM dashboard.
* `dashboard.html` - A live IoT data center simulation showing real-time telemetry, PCM melt rates, and predictive fan control.
