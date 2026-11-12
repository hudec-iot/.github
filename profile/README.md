<div align="center">

# HUDEC

### Connecting equipment. Enabling possibilities.

Communication Modules · Embedded Control · Equipment Integration

[Explore Projects](https://github.com/orgs/hudec-iot/repositories) · [Technical Focus](#technical-focus) · [Work With Us](#work-with-us)

</div>

---

HUDEC develops and supplies communication modules, with Bluetooth Low Energy (BLE) and Wi-Fi as our initial product focus. We help bring connectivity to existing control equipment, laying the groundwork for equipment data exchange and connected applications.

Starting with practical equipment requirements, we bring control cores, communication modules, and equipment interfaces together in a reusable architecture. Our focus is on interface compatibility, reliable operation, and traceability from prototype validation through production.

## Technical Focus

| Area | Development Focus |
| :--- | :--- |
| **Wireless Communication** | BLE and Wi-Fi module development, equipment interfacing, and communication validation. |
| **Embedded Control** | Sensor data acquisition, equipment state management, and control of GPIO, relays, and actuators. |
| **Equipment Integration** | Evaluation of UART, RS485, I²C, and SPI interfaces to validate control and communication workflows. |
| **Production Readiness** | Module specifications, hardware and firmware version management, and repeatable test procedures. |

## RTCOMP · Modular Equipment Architecture

RTCOMP is our modular product platform and ecosystem currently under development. It separates control, communication, and equipment interfaces into defined roles, providing a shared foundation for different equipment applications.

```text
                          RTCOMP

   Control Core  +  Communication Module  +  Base / Interface
        |                    |                     |
  Equipment Logic      Data Exchange       Sensing & Control
```

- **Core** — Runs equipment control logic and manages peripherals and equipment state.
- **Communication** — Provides wireless connectivity according to application requirements.
- **Base / Interface** — Connects equipment power, signals, and peripheral interfaces.

Current design work covers module naming and configuration management, standardized core interfaces, and prototype validation of separate control and communication functions. Supported features and availability depend on each module's project documentation and validation results.

## From Requirements to Validation

**Requirements & Interface Review → Module Configuration → Prototype Integration → Equipment Testing → Supply Assessment**

We focus on connectivity upgrades for large machinery and medical equipment applications, and explore module applications and research collaboration with academic and research institutions. Each integration defines its functional scope, acceptance criteria, and responsibilities according to the intended use. Validation focuses on interface compatibility, reconnection behavior, power stability, and extended operation.

## Work With Us

We welcome discussions about equipment connectivity upgrades, module applications, and embedded integration. To help us understand your needs, please include:

- **Equipment context** — Your current control architecture and the functions you want to add.
- **Interface requirements** — Communication protocols, power specifications, and existing peripherals.
- **Deployment needs** — Validation goals, expected quantities, and timeline.

For technical questions and suggestions, browse the [relevant project](https://github.com/orgs/hudec-iot/repositories), review its documentation, and follow its contribution guidelines where available. Custom development and equipment integration scope are agreed on a project basis.

---

<div align="center">

<strong>HUDEC</strong><br>
Hsinchu, Taiwan

</div>
