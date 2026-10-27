# Hi, I'm William Eklund 👋

I'm a **systems and game developer** based in Sweden, focusing on **C# / .NET**, performance-critical architecture, networking, and graphics. 

I build **Krut**, an independent 3D game engine, alongside related games, distributed backends, and open-source networking tools.

🌐 **Portfolio:** [cedsson.github.io](https://cedsson.github.io) &nbsp;|&nbsp; 💼 **LinkedIn:** [/in/williamekl](https://www.linkedin.com/in/williamekl/) &nbsp;|&nbsp; 🎮 **itch.io:** [cedsson.itch.io](https://cedsson.itch.io) &nbsp;|&nbsp; ✉️ **Contact:** williameklund2@gmail.com

---

### 🚀 What I'm Working On

- **[Krut Engine](https://cedsson.github.io/#engine)** — A custom 3D game engine (~58k LOC in C#/.NET 10) built solo.
  - Forward+ (clustered) renderer supporting **Direct3D 12** and **Vulkan**.
  - TrenchBroom BSP/CSG level workflow with modern PBR, real-time lighting, and custom GI lightmapper.
  - Fully tested with xUnit suites, running headless deterministic simulations, and built with **Native AOT**.

- **[Krut.Netcode](https://github.com/Cedsson/Krut.Netcode)** *(Open Source, MIT)* — Authoritative-server netcode library for .NET.
  - Client prediction & reconciliation, fixed tick clock synchronization, and snapshot interpolation.
  - Zero-allocation steady-state messaging with object pooling.
  - Integrated network link degradation simulator (latency, jitter, burst packet loss).

- **[Krut.Racing](https://cedsson.github.io/#racing)** — Online multiplayer racing game powered by Krut & Krut.Netcode.
  - Dedicated authoritative game servers.
  - Backend built with **ASP.NET Core**, **PostgreSQL**, append-only ledger for payouts, and Steam authentication.

- **[Commute](https://cedsson.itch.io/commute)** — Retro-styled single-player FPS tech demo built on Krut to stress-test collision, audio occlusion, and AI navigation.

---

### 🛠️ Core Tech & Skills

```text
Languages & Runtime : C# / .NET 10, Native AOT, HLSL, C/C++
Graphics & Shaders  : Direct3D 12, Vulkan, Clustered Forward+ Rendering, PBR, SPIR-V / DXIL
Networking & Engine : Client Prediction, Fixed-Tick Netcode, Jitter2 Physics, TrenchBroom / BSP
Backend & Data      : ASP.NET Core, PostgreSQL, EF Core, Docker, REST APIs
