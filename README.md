# LEGOSwarm
LEGOSwarm is a research platform investigating autonomous robotic assembly, powered by a system called [Weave](Weave.md) that employs a [Foreman](Foreman.md) and [Workers](Worker.md) to assemble complete LEGO kits purely from visual input of the LEGO isntruction booklet. Developed by Loom Robotics.


# Youtube Channel
https://www.youtube.com/channel/UCpjbNt2DCMKCNqQ9IGROmjg 


## Excecutive Summary
A modular distributed robotics research platform for decentralized physical assembly, swarm coordination, and fault-tolerant construction workflows.


## Core Prinicples
**Decentralized execution** — Robots act independently.

**Minimal communication** — Low bandwidth, event-driven, sparse messages.

**Stigmergic coordination** — Shared digital twin and memory.

**Fault tolerance** — Loss of individual robots does not terminate construction.


### How
A team of autonomous mobile robots collaboratively assembles LEGO structures within a controlled arena. A supervisory planning layer, the [Foreman](foreman.md), parses a digital construction model into an [Assembly Graph](Assemblygraph.md), comprised of physical jobs that need to be completed onsite. The graph releases job nodes to the swarm intermittently and with minimal bandwidth usage. Execution, navigation, placement, and verification are fully decentralized and performed onboard by the [Workers](Worker.md).


### Why
Unlike centralized industrial automation, LegoSwarm emphasizes decentralized execution, local autonomy, minimal communication, stigmergic coordination, and robustness to partial system failure.
V1 deliberately constrains the problem — LEGO parts, a flat arena, fiducial localization, and mechanically simple robots — to maximize research throughput, reproducibility, and iteration speed on the coordination software, which is the true object of study.
The long-term objective is not LEGO automation, but scalable coordination architectures applicable to modular robotic construction, autonomous infrastructure assembly, hazardous-environment fabrication, planetary construction, and distributed robotic manufacturing.
