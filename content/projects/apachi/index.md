---
title: Apachi & the Chonki Series
date: 2020-01-01
tags:
  - Combat Robotics
  - Mechanical Design
  - RoboJackets
links:
  - type: site
    url: https://wiki.robojackets.org/Apachi
image:
  caption: 'Apachi'
  focal_point: ""
  preview_only: false
---

Combat robots designed and built through Georgia Tech's RoboJackets team. Apachi was an 18 lb hobbyweight with an overhead bar weapon and shuffler drive. Its spiritual successors — Chonki through Chonkiv — grew into a 45 lb featherweight shuffling shell spinner lineage that took 1st place at NHRL in April 2024.

<!--more-->

## Apachi

Apachi was an 18 lb hobbyweight combat robot designed and built in 2019–2020. It featured a shuffler drive — six HDPE feet per side actuated by an eccentric mechanism — chosen to gain experience with the drive type and take advantage of the 50% weight bonus shufflers receive in competition. I was the design lead on the drive side. The weapon was an overhead bent bar spinning at approximately 800 RPM, giving 360-degree strike capability.

| | |
|---|---|
| **Weight class** | Hobbyweight (18 lb) |
| **Weapon** | Overhead bent bar, ~800 RPM |
| **Drive** | Shuffler, 6 HDPE feet per side |
| **Drive motors** | Turnigy 540L V-Spec Inrunner 810kv |
| **Weapon motor** | Scorpion SII-4025-520KV |
| **Battery** | Two 2200 mAh 4S LiPo |
| **ESCs** | HobbyKing RC car ESCs (drive), YEP 100A (weapon) |

{{< youtube URhNGAVd9NQ >}}

Apachi competed at Motorama 2020, going 0–2 in bracket competition before winning the 12 lb rumble by survival. Post-competition analysis identified two critical failure modes: the main drive shaft was undersized, and the weapon bar fractured repeatedly under impact from being over-hardened and insufficiently reinforced at the mounting point.

After competing with Apachi, we decided to run tests with the drive train to see if it would be able to run a larger bot. This was done by simply putting a 30lb robot on top of the 18 lb robot. Apachi was still able to drive well, so we decided to compete with a very similar drive train in the 30 lb class in future years.

## Chonki Series

The Chonki lineage grew directly out of lessons learned on Apachi. All four generations are 45 lb featherweight shuffling shell spinners — combining the shuffler weight bonus (1.5× against wheeled competitors) with a full-coverage spinning steel shell that simultaneously serves as weapon and armor. Design reviews were conducted across the series to carry forward improvements between iterations.

### Chonki

Chonki was developed in 2020–2021 as the first attempt at the shell spinner concept. The name came before the design. The shell was milled from a solid 200 lb steel block — consuming roughly 90% of the material as waste — chosen over a nested-ring construction to eliminate connection failure points. The weapon drive used a single driven wheel at the top of the shell with supporting rollers, inspired by competitor Hyperpolarized. A tapered roller bearing interface carried the shell load to the chassis. The drive was largely carried over from my original Apachi design

The chassis used ¼" aluminum top and side plates, ⅛" bottom plate, and HDPE front and back panels. Drive used dual Turnigy SK3 brushless motors with Flipsky controllers. Chonki never competed due to COVID-related event cancellations.

### Chonkii

Chonkii competed in 2021–2022 with a 3–4 combined record across two events.

The shell retained the solid single-piece construction and wheel-driven weapon system from Chonki, but at 1200 RPM the tip speed proved too low for reliable damage. Other identified weaknesses included poor pushing traction, no self-righting mechanism, an undersized electronics stack, and a shell positioned too high — leaving the underside exposed to wedges and undercutters. One loss at Motorama was caused by an over-tightened screw grounding out the electronics.

### Chonkiii

Chonkiii iterated on Chonkii's shortcomings with a significantly upgraded shell — ¼" heat-treated 4140 steel replacing the unhardened A36 — and a 50-degree outward slant designed to deflect horizontal impactors. At 2000 RPM the tip speed reached ~120 MPH. A self-righting mechanism was added extending from the center shaft, and the HDPE side plates were retained for electronics protection.

The shell proved exceptionally durable — surviving direct hits from Megatron — but underpowered drive motors caused inconsistent shuffler performance under load.

### Chonkiv

Chonkiv was designed and built in 2023–2024 and addressed the drive power deficit that had plagued earlier iterations. Competing at NHRL April 2024, Chonkiv went 5–1 to take **1st place** — the culmination of the design lineage. Its only loss was a timeout against MegatRON; wins came by knockout, technical knockout, judges' decision, and forfeit.

| | |
|---|---|
| **Weight class** | Featherweight (45 lb) |
| **Weapon** | Shell spinner |
| **Record** | 5–1, **1st place NHRL April 2024** |

{{< youtube RcbaYH99iOs >}}

Full design documentation is on the [RoboJackets wiki](https://wiki.robojackets.org/Chonkiv).
