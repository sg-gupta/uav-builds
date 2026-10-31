# UAV / Drone Builds

Four drone and fixed-wing projects built with Team Robolution, spanning our first from-scratch quadcopter through to a BSF-funded surveillance one.

## 500mm Quadcopter (S500)

Our team's first drone build — starting completely from scratch with some guidance from seniors. Built with teammates **Prateek** and **Arun**.

- S500 frame, D3536-8 1000KV motors, 10" props
- Pixhawk 2.4.8 flight controller, configured via Mission Planner
- 4S 8000mAh LiPo
- Autonomous waypoint missions with RTL/failsafe

## 5" FPV Drone

Our first attempt at FPV-style builds, still flown through Mission Planner rather than a dedicated FPV firmware stack. Built with teammate **prateek**.

- QAV250 frame, MT2204 2300KV motors, 5055 tri-blade props
- MicoAir743 V2 FC+ESC stack
- 4S Li-ion battery with integrated PDB

## Fixed-Wing UAVs

A series of fixed-wing builds for the **IIT Bombay aeromodeling competition**. All receiver-controlled (no flight controller) except the last:

- **Two 1m-wingspan builds** — team effort; I was mainly in a support role here rather than leading
- **A smaller 50cm-wingspan puller plane**, built with teammate **Vaishali** — carbon-fibre + 3D-printed internal support structure of the wings, the wings outers serface made with teflon sheets, EPO/thermocol body, 2200KV motor - 6 inch props , FS-i6 receiver, servo push-rod control surfaces
- **A later FC-controlled variant**, led by teammates **Prateek** and **Ritesh** while I was more focused on a different project

## 10" FPV Surveillance Drone

Funded entirely by BSF as a student-collab build, and built with teammates **Vaishali** and **Arun**, running INAV firmware. Designed from the ground up for efficiency, endurance, and modular versatility, with the focus on aerodynamic stability, vibration damping, and energy efficiency throughout.

- Up to 30 minutes of flight with no payload, ~20 minutes carrying a 1kg payload

**Build:**

- GEPRC MARK4 V2 10" frame
- GEPRC TAKER F4 65A FC/ESC stack
- ALEX X3155 900KV BLDC motors
- Gemfan 1050-3 glass-fibre nylon propellers 
- 22.2V (6S) 9000mAh Li-ion battery, XT60 connector
- RadioMaster Boxer (M2) radio controller with ELRS
- GEPRC ELRS 2.4G diversity receiver
- HGLRC M100 PRO GPS
- GEPRC MATEN 5.8G 3W VTX
- RunCam Phoenix 2 Pro FPV camera
- Eachine FPV goggles (dual antenna) + 5.8GHz LHCP RP-SMA antenna + triple-feed patch antenna + RHCP SMA/RP-SMA antennas
- TBS Smoke Stopper (safety device for first power-up)
- Microware mini AV-to-HDMI video converter + Eachine 7" ground station screen
- Nylon braided wire sleeving + zip ties for cable management

## My role across these

Mostly wiring and electronics on the earlier builds, moving into firmware and testing work by the later ones.

## Repo structure

```
uav-builds/
├── README.md
├── 500mm-quad/
│   └── build.jpg
├── 5inch-fpv/
│   └── build.jpg
├── fixed-wing/
│   ├── 1m-wingspan.jpg
│   └── 50cm-wingspan.jpg
└── 10inch-surveillance/
    ├── build.jpg
    └── bom.md
```
