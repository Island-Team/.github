<div align="center">

<a href="https://os-island.com">
  <img src="https://raw.githubusercontent.com/Island-Team/.github/master/assets/island-team-logo.png" width="132" alt="Island Team logo">
</a>

# Island Team

### Building embodied intelligence—from perception and memory to safety-gated action.

We develop **IslandOS Aether**, an open platform that connects model-driven cognition to simulated and physical worlds through explicit contracts and controlled execution.

[![Website](https://img.shields.io/badge/Website-os--island.com-126BCE?style=for-the-badge&logo=googlechrome&logoColor=white)](https://os-island.com)
[![Aether](https://img.shields.io/badge/Explore-IslandOS_Aether-071A3D?style=for-the-badge&logo=probot&logoColor=white)](https://github.com/Island-Team/Island-egia)
[![GitHub](https://img.shields.io/badge/Repositories-Island_Team-24292F?style=for-the-badge&logo=github&logoColor=white)](https://github.com/orgs/Island-Team/repositories)

<br><br>

<img src="https://raw.githubusercontent.com/Island-Team/.github/master/assets/island-team-hero.png" width="100%" alt="Island Team embodied-intelligence pipeline: perception and models flow through cognition and a safety gate into physical action">

</div>

---

## IslandOS Aether

Aether separates cognition from physical execution. The **EGI Agent** understands context, builds missions and plans, and requests typed primitives. **EOS** owns device integration and admits every command through a controlled action gate before it reaches hardware.

```mermaid
flowchart LR
    human["Operator"] --> web["Web & Port"]
    web --> egia["EGI Agent<br/>perceive · plan · remember"]
    models["Local models<br/>speech · vision · language"] -.-> egia
    egia -->|"gRPC · typed contracts"| eos["EOS<br/>execute · observe · protect"]
    models -.-> eos
    eos --> world["Robots · devices · simulation"]

    classDef cognition fill:#eaf3ff,stroke:#126bce,color:#071a3d
    classDef execution fill:#071a3d,stroke:#126bce,color:#ffffff
    classDef support fill:#f6f8fa,stroke:#8c959f,color:#24292f
    class egia cognition
    class eos execution
    class human,web,models,world support
```

<table>
  <tr>
    <td width="50%" valign="top">
      <p align="center"><img src="https://raw.githubusercontent.com/Island-Team/.github/master/assets/egia-logo.png" width="72" alt="EGIA logo"></p>
      <h3 align="center"><a href="https://github.com/Island-Team/Island-egia">Island-egia</a></h3>
      <p><strong>EGI Agent · cognition and orchestration</strong></p>
      <p>Turns observations and operator intent into missions and plans, coordinates memory and monitoring, and safety-gates primitive requests before handing them to the embodied runtime.</p>
      <p><code>Python 3.12+</code> · <code>gRPC</code> · <code>WebSocket</code></p>
    </td>
    <td width="50%" valign="top">
      <p align="center"><img src="https://raw.githubusercontent.com/Island-Team/.github/master/assets/eos-logo.png" width="72" alt="EOS logo"></p>
      <h3 align="center"><a href="https://github.com/Island-Team/Island-eos">Island-eos</a></h3>
      <p><strong>Embodied OS · execution and hard safety</strong></p>
      <p>Integrates devices, projects body state, exposes typed primitives, and provides the final controlled path to hardware—with demo and optional ROS 2 backends.</p>
      <p><code>C++17</code> · <code>gRPC</code> · <code>ProtoJSON</code></p>
    </td>
  </tr>
</table>

## The ecosystem

| Project | Role |
| :--- | :--- |
| **[Island-models](https://github.com/Island-Team/Island-models)** | Local serving and lifecycle tooling for speech, vision, language, translation, embedding, pose, and generative models. |
| **[Island-Base](https://github.com/Island-Team/Island-Base)** | Guarded C++ interfaces for the Jueying X30 vendor protocols—pose, navigation, manual motion, and launcher bridging. |
| **[Island-port](https://github.com/Island-Team/Island-port)** | Rust HTTP/WebSocket gateway for identity, messaging, documents, virtual wallets, and the Transnet boundary. |
| **[Island-web](https://github.com/Island-Team/Island-web)** | Bilingual web experience for the public site and Island operator surfaces. |

## Research & simulation

> ### 🌱 [Island OS](https://github.com/Island-Team/Island)
>
> A Rust-native research world where an **anima** inhabits **METALAND** with a body, senses, episodic memory, and an **Action–Critic–Experience** loop. It is our simulation track for exploring persistent, consequence-shaped AI characters—not a claim that today’s systems are conscious.

## What guides us

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>◉ Embodied by design</h3>
      <p>Intelligence is grounded in perception, state, action, and what happens next—not only a text exchange.</p>
    </td>
    <td width="33%" valign="top">
      <h3>◇ Contracts first</h3>
      <p>Typed, versioned boundaries keep cognition, models, runtimes, and hardware independently replaceable.</p>
    </td>
    <td width="33%" valign="top">
      <h3>⛨ Safety at the boundary</h3>
      <p>Planning can stay creative; physical action still passes through explicit validation and controlled execution.</p>
    </td>
  </tr>
</table>

---

<div align="center">

**AI · Agent · Innovation**

[Website](https://os-island.com) · [Repositories](https://github.com/orgs/Island-Team/repositories) · [Contact](mailto:ashexlv278@gmail.com)

<sub>Let embodied agents come to life. Dudulu~</sub>

</div>
