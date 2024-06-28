---
label: "Tower View"
icon: "file"
order: 100
---

**What is a tower view?**

Tower view is a system designed to allow controllers to view real-time network activity via his or her preferred flight simulator software. It provides controllers with a 3D view of a 2D radar scope.

**What do I need?**

You must choose your preferred ATC client, your preferred Flight Simulator, and the corresponding connection clients (Audio For Vatsim, vPilot, xPilot, Swift, etc.)

**How does it work?**

Ultimately the simplest explanation is that one system (typically the ATC client) establishes a connection to VATSIM and establishes a proxy server. The connection client will make a connection to the proxy server and inject the network traffic into the flight simulator. That said, various platforms exist with different connection methods.

**Getting started**

This tutorial assumes you have installed the EuroScope ATC client, Audio For Vatsim, and either vPilot or xPilot depending on your preferred Flight Simulator.

**Connecting**

**Step 1** - Open your flight simulator and position yourself at your local airport. (If necessary, we recommend using a default GA aircraft and positioning it at a remote gate or ramp when tower positions are not an option)

**Step 2** - Open EuroScope, Go to Quick Set, and Select Enable advanced proxy communication.

**Step 3** - In EuroSope click to open the connection dialog, Choose Start Proxy Server, and Click Connect.

**Step 4** - Open Audio For Vatsim and connect normally. (you are now controlling the selected position)

**Step 5** - Open either vPilot or xPilot and in the command line type .towerview (this will trigger a connection to the proxy server and show your cid_tv as a callsign)

Enjoy!