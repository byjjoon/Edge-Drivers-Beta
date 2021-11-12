## Edge Driver zigbee Contact

Is a original smartthings beta driver added Lidl Contact Sensor Fingerprint and profile contact-battery

## Devices 29-0ct-2021:
zigbeeManufacturer:
  - id: "ORVIBO/e70f96b3773a4c9283c6862dbafb"
    # Shorten because of 36 ch limit. Need to use complete model name
    deviceLabel: Orvibo Open/Closed Sensor
    manufacturer: ORVIBO
    model: e70f96b3773a4c9283c6862dbafb6a99
    deviceProfileName: contact-profile
  - id: "eWeLink/DS01"
    deviceLabel: eWeLink Open/Closed Sensor
    manufacturer: eWeLink
    model: DS01
    deviceProfileName: contact-profile
  - id: "Aurora/WindowSensor51AU"
    deviceLabel: Aurora Open/Closed Sensor
    manufacturer: Aurora
    model: WindowSensor51AU
    deviceProfileName: contact-profile
  - id: "Aurora/DoorSensor50AU"
    deviceLabel: Aurora Open/Closed Sensor
    manufacturer: Aurora
    model: DoorSensor50AU
    deviceProfileName: contact-profile
  - id: "HEIMAN/DoorSensor-N"
    deviceLabel: HEIMAN Open/Closed Sensor
    manufacturer: HEIMAN
    model: DoorSensor-N
    deviceProfileName: contact-profile
  - id: "NYCE/3010"
    deviceLabel: NYCE Open/Closed Sensor
    manufacturer: NYCE
    model: 3010
    deviceProfileName: contact-battery-profile
  - id: "NYCE/3011"
    deviceLabel: NYCE Open/Closed Sensor
    manufacturer: NYCE
    model: 3011
    deviceProfileName: contact-battery-profile
  - id: "NYCE/3014"
    deviceLabel: NYCE Open/Closed Sensor
    manufacturer: NYCE
    model: 3014
    deviceProfileName: contact-battery-profile
  - id: "sengled/E1D-G73"
    deviceLabel: Sengled Open/Closed Sensor
    manufacturer: sengled
    model: E1D-G73
    deviceProfileName: contact-battery-profile
  - id: "Visonic/MCT-340 SMA"
    deviceLabel: Tyco Open/Closed Sensor
    manufacturer: Visonic
    model: MCT-340 SMA
    deviceProfileName: contact-profile
  - id: "LIDL Open/Close Sensor"
    deviceLabel: LIDL Open/Close Sensor
    manufacturer: _TZ1800_ejwkn2h2
    model: TY0203
    deviceProfileName: contact-battery-profile
  - id: "NEDIS Open/Close Sensor"
    deviceLabel: Nedis Open/Close Sensor
    manufacturer: TUYATEC-crr8qb0p
    model: RH3001
    deviceProfileName: contact-battery-profile
  - id: "HiveHom/DWS003 Open/Close Sensor"
    deviceLabel: HiveHom DWS003 Open/Close Sensor
    manufacturer: HiveHome.com
    model: DWS003
    deviceProfileName: contact-battery-profile
  - id: "TUYATEC/r9hgssol Open/Close Sensor"
    deviceLabel: TUYATEC r9hgssol Open/Close Sensor
    manufacturer: TUYATEC-r9hgssol
    model: RH3001
    deviceProfileName: contact-battery-profile
zigbeeGeneric:
  - id: "contact-generic"
    deviceLabel: "Zigbee Contact Sensor"
    zigbeeProfiles:
      - 0x0104
    deviceIdentifiers:
      - 0x0402
    clusters:
      server:
        - 0x0000
        - 0x0001
        - 0x0003
        - 0x0009
        - 0x0500
      client:
        - 0x0000
    deviceProfileName: contact-general