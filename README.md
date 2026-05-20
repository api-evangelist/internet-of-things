# Internet of Things (internet-of-things)
An index and topic collection covering consumer and commercial Internet of Things (IoT) platforms, smart home ecosystems, connected device APIs, and the messaging and edge protocols that bind them together. This collection focuses on cloud IoT services such as AWS IoT Core, smart home and connected device platforms like Google Nest, Tuya, IFTTT, and Reolink, MQTT brokers like HiveMQ and Mosquitto, edge runtimes like KubeEdge and LF Edge, and the standards and SDKs that connect millions of devices to APIs every day. Distinct from the Industrial topic, which focuses on OT and manufacturing systems.

**URL:** [https://apievangelist.com](https://apievangelist.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - IoT, Smart Home, Connected Devices, MQTT, LoRaWAN, Edge

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Device Schema](https://raw.githubusercontent.com/api-evangelist/internet-of-things/refs/heads/main/json-schema/internet-of-things-device-schema.json)
- [JSONSchema - Telemetry Event Schema](https://raw.githubusercontent.com/api-evangelist/internet-of-things/refs/heads/main/json-schema/internet-of-things-telemetry-event-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/internet-of-things/refs/heads/main/json-ld/internet-of-things-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/internet-of-things/refs/heads/main/vocabulary/internet-of-things-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Device Identity and Provisioning | IoT platforms issue per-device credentials, X.509 certificates, and identities so connected devices can authenticate to cloud services and to each other across the network. |
| MQTT and Pub/Sub Messaging | Lightweight publish/subscribe messaging via MQTT, CoAP, and similar protocols is the dominant pattern for moving telemetry from constrained devices to cloud backends. |
| Device Shadows and State Synchronization | Cloud IoT services maintain a virtual representation (shadow or twin) of each device that mirrors and synchronizes desired and reported state across intermittent connectivity. |
| Rules Engines and Telemetry Routing | IoT platforms include rules engines that filter, transform, and route incoming telemetry to databases, analytics services, notification channels, and downstream APIs. |
| Over-the-Air (OTA) Firmware Updates | Connected device platforms offer managed OTA firmware update delivery, rollout orchestration, and rollback for fleets ranging from a few units to millions. |
| Edge Computing and Local Runtimes | Runtimes like AWS Greengrass, KubeEdge, and LF Edge push compute, ML inference, and message brokering to gateways and devices for low-latency local control. |
| Smart Home Integration and Automation | Smart home platforms expose device APIs and event triggers that enable cross-vendor automation, voice control, and consumer-facing routines like "good morning" or geofenced actions. |
| Long-Range Low-Power Connectivity | LoRaWAN, cellular IoT, and similar long-range low-power networks connect battery-powered sensors and trackers that operate for years on a single charge. |

## Use Cases

| Name | Description |
|------|-------------|
| Smart Home Automation | Consumers connect lights, locks, cameras, thermostats, and voice assistants through platforms like Google Nest, Tuya, and IFTTT to create cross-device routines and remote control. |
| Connected Camera and Security | Platforms like Reolink and Neolink expose APIs for live video, motion events, and recording management so security cameras can be integrated into broader workflows. |
| Fleet and Asset Tracking | Commercial IoT platforms like Samsara stream vehicle telemetry, location, and driver behavior to cloud dashboards and APIs for logistics and fleet management. |
| Industrial-Grade Device Management at Scale | AWS IoT Device Management and similar services let operators register, organize, monitor, and update millions of connected devices through a single API surface. |
| Real-Time Telemetry Pipelines | MQTT brokers like HiveMQ and Mosquitto, combined with stream processors, ingest billions of telemetry events per day from devices into analytics and storage systems. |
| Edge AI and Local Inference | Edge runtimes like AWS Greengrass and KubeEdge run ML models close to devices for fast local decisions in industrial cameras, vehicles, and smart appliances. |
| Connected Mobility and EVs | Vehicle platforms and OEM APIs expose location, charging, and diagnostic data for electric vehicles and connected cars, enabling routing, charging, and maintenance integrations. |
| Event-Driven Consumer Automation | IFTTT and similar platforms let consumers wire IoT devices to web APIs through if-this-then-that recipes that span dozens of vendors and services. |

## Integrations

| Name | Description |
|------|-------------|
| AWS IoT Core | Managed cloud service that brokers MQTT, HTTPS, and WebSocket connections from devices and routes messages to AWS services through a rules engine. |
| HiveMQ | Enterprise-grade MQTT broker platform used for connecting millions of IoT devices with extensions for Kafka, security, and observability. |
| Google Nest | API platform for thermostats, cameras, and doorbells in the Google smart home ecosystem, exposing device state, events, and control. |
| Tuya | Global IoT platform powering tens of thousands of branded smart home devices through unified cloud APIs and SDKs. |
| IFTTT | Consumer automation platform that connects IoT devices, web apps, and services through user-authored conditional recipes. |
| Cisco Meraki | Cloud-managed networking and IoT platform with APIs for cameras, environmental sensors, and Wi-Fi-connected device telemetry. |
| Samsara | Connected operations platform for vehicles, equipment, and sites with APIs for telemetry, video, and driver safety data. |
| KubeEdge | Open-source CNCF project extending Kubernetes orchestration to edge nodes and IoT devices for managed edge workloads. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Device Schema](json-schema/internet-of-things-device-schema.json)
- [Telemetry Event Schema](json-schema/internet-of-things-telemetry-event-schema.json)

### JSON Structure

- [Device Structure](json-structure/internet-of-things-device-structure.json)
- [Telemetry Event Structure](json-structure/internet-of-things-telemetry-event-structure.json)

### JSON-LD

- [Internet of Things Context](json-ld/internet-of-things-context.jsonld)

## Vocabulary

- [Internet of Things Vocabulary](vocabulary/internet-of-things-vocabulary.yaml) - Unified taxonomy mapping resources, actions, workflows, and personas across cloud IoT, smart home, MQTT messaging, and edge runtimes

## Network

This index references the following Internet of Things repositories:

- [Amazon IoT Core](https://github.com/api-evangelist/amazon-iot-core)
- [Amazon IoT Device Management](https://github.com/api-evangelist/amazon-iot-device-management)
- [Amazon IoT Device Defender](https://github.com/api-evangelist/amazon-iot-device-defender)
- [Amazon IoT Events](https://github.com/api-evangelist/amazon-iot-events)
- [Amazon IoT Greengrass](https://github.com/api-evangelist/amazon-iot-greengrass)
- [Amazon IoT FleetWise](https://github.com/api-evangelist/amazon-iot-fleetwise)
- [Amazon IoT TwinMaker](https://github.com/api-evangelist/amazon-iot-twinmaker)
- [Amazon FreeRTOS](https://github.com/api-evangelist/amazon-freertos)
- [Google Nest](https://github.com/api-evangelist/google-nest)
- [Tuya](https://github.com/api-evangelist/tuya)
- [IFTTT](https://github.com/api-evangelist/ifttt)
- [HiveMQ](https://github.com/api-evangelist/hivemq)
- [MQTT](https://github.com/api-evangelist/mqtt)
- [PubNub](https://github.com/api-evangelist/pubnub)
- [NATS](https://github.com/api-evangelist/nats)
- [Cisco Meraki](https://github.com/api-evangelist/cisco-meraki)
- [Samsara](https://github.com/api-evangelist/samsara)
- [Samsung](https://github.com/api-evangelist/samsung)
- [Philips](https://github.com/api-evangelist/philips)
- [KubeEdge](https://github.com/api-evangelist/kubeedge)
- [LF Edge](https://github.com/api-evangelist/lf-edge)
- [OpenYurt](https://github.com/api-evangelist/openyurt)
- [Aklivity](https://github.com/api-evangelist/aklivity)
- [mParticle](https://github.com/api-evangelist/mparticle)
- [Telnyx](https://github.com/api-evangelist/telnyx)
- [Reolink](https://github.com/api-evangelist/reolink)
- [Neolink](https://github.com/api-evangelist/neolink)
- [Parklio](https://github.com/api-evangelist/parklio)
- [BLE](https://github.com/api-evangelist/ble)
- [Zephyr Project](https://github.com/api-evangelist/zephyr)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
