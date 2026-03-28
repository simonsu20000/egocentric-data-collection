# obaydata/egocentric-data-collection

[![Website](https://img.shields.io/badge/Website-obaydata.com-blue)](https://obaydata.com)
[![Demo Dataset](https://img.shields.io/badge/🤗%20Demo-HuggingFace-yellow)](https://huggingface.co/datasets/obaydata/egocentric-dexterous-manipulation-demo)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

**Scalable egocentric human manipulation data for embodied AI.**

OBayData operates a production-grade platform for first-person dexterous manipulation data collection. We capture multi-view video, hand poses, camera parameters, and rich language annotations across 1,000+ real-world scenarios — at up to 100,000 hours per month.

---

## Overview

Training embodied AI systems for real-world manipulation requires data that is:
- **Egocentric** — first-person perspective matching robot deployment viewpoints
- **Dexterous** — capturing fine-grained hand-object interactions
- **Diverse** — spanning thousands of real environments and tasks
- **Annotated** — with structured labels that downstream models can consume

OBayData provides all of the above as a managed data collection service.

## Hardware Setup

| Component | Specification |
|---|---|
| Head Camera | Head-mounted, 1080p, egocentric viewpoint |
| Wrist Cameras | Dual (left + right), 1080p, close-up hand views |
| Tactile Gloves (optional) | Manus METAGLOVES PRO — finger force & contact sensing |
| Synchronization | Hardware-synced multi-stream capture |

All streams are temporally aligned and calibrated.

## Data Products

| Product | Description | Format |
|---|---|---|
| Egocentric Video | 1080p first-person video from head + wrist cameras | MP4 / frames |
| Gesture & Action Labels | Per-frame action recognition and gesture classification | JSONL |
| Hand Pose Reconstruction | 3D hand mesh / joint positions per frame | JSONL / NPZ |
| Camera Extrinsics | Per-frame camera pose estimation | JSONL |
| Atomic Language Annotations | Fine-grained natural language descriptions of each sub-action | JSONL |
| Tactile Data (optional) | Per-finger force and contact signals from Manus gloves | JSONL |

## Scenario Coverage

We operate in **1,000+ real-world scenarios** across diverse environments:

| Category | Example Scenarios |
|---|---|
| Hospitality | Hotel room cleaning, bed making, minibar restocking |
| Manufacturing | Assembly line operations, quality inspection, tool handling |
| Retail | Shelf stocking, checkout operations, inventory counting |
| Logistics | Package sorting, palletizing, warehouse picking |
| Food Service | Kitchen prep, plating, serving, dishwashing |
| Office | Document handling, equipment operation, desk organization |
| Domestic | Cooking, cleaning, laundry, appliance operation |
| Healthcare | Instrument handling, sample preparation, supply management |

Custom scenarios and task definitions available on request.

## Benchmark Support

Our collection protocols are aligned with leading embodied AI benchmarks:

- **RoboTwin 2.0** — dual-arm manipulation tasks
- **PI Olympics** — physical intelligence challenge tasks
- Custom benchmark task reproduction on request

## Capacity & Pricing

| Tier | Volume | Price Range |
|---|---|---|
| Standard | Up to 10K hrs/month | $20–100/hr |
| Scale | 10K–50K hrs/month | $10–100/hr |
| Enterprise | 50K–100K hrs/month | $5.50–100/hr |

*Pricing depends on annotation complexity, scenario requirements, and hardware configuration. Deliveries begin May 2026.*

## Demo Dataset

Evaluate our data quality with the published demo:

🔗 **[obaydata/egocentric-dexterous-manipulation-demo](https://huggingface.co/datasets/obaydata/egocentric-dexterous-manipulation-demo)**

The demo includes sample egocentric videos, hand pose annotations, and language labels from a subset of our scenarios.


## Contact

- **Website:** [obaydata.com](https://obaydata.com)
- **Email:** simon.su@obaydata.com
- **Company:** New Oriental Bay Limited (香港新东湾有限公司)

For data collection inquiries, custom scenario requests, or partnership discussions — reach out via our website or email.

