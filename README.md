<div align="center">

# William Eklund

**Systems & Game Developer | C# / .NET**  
*Game engines, low-level networking, backend systems, and performance.*

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-cedsson.github.io-c8452c?style=flat-square&logo=google-chrome&logoColor=white)](https://cedsson.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-William_Eklund-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/williamekl/)
[![itch.io](https://img.shields.io/badge/itch.io-Cedsson-FA5C5C?style=flat-square&logo=itchdotio&logoColor=white)](https://cedsson.itch.io)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:williameklund2@gmail.com)

<br/><br/>

> *💡 **Note:** After developing the Krut 3D engine and my core systems in local repositories, I've recently started migrating my active development, benchmarks, and open-source libraries onto GitHub.*

</div>

---

### ⚙️ Krut Engine
> *A modern 3D game engine built solo in C# / .NET 10.*

* **Graphics:** Custom Forward+ (clustered) renderer with **Direct3D 12** and **Vulkan** backends, offline-compiled HLSL (DXIL & SPIR-V), PBR, cascaded shadow maps, and custom GI lightmapper.
* **Architecture:** Clean subsystem isolation tested via xUnit, deterministic simulation running headless, and **Native AOT** compilation.
* **Level Workflow:** Quake/Source-style BSP/CSG workflow using TrenchBroom, portal culling, and triangle BVH collision.
* **Scale:** Architected and maintained solo across **~240k+ LOC** of tested C# (spanning the engine core, multiplayer racer, and distributed backend).

---

### 🕹️ Games Built on Krut

<table>
  <tr>
    <td width="50%" valign="top">
      <h4 align="center">🏎️ Krut.Racing</h4>
      <a href="https://cedsson.github.io/#racing">
        <img src="assets/Racing-poster.jpg" alt="Krut.Racing" width="100%" style="border-radius: 6px;" />
      </a>
      <p>
        Online multiplayer racing game with an authoritative dedicated server, client prediction, car physics, and an <b>ASP.NET Core & PostgreSQL</b> backend with Steam authentication.
      </p>
      <div align="center">
        <img src="https://img.shields.io/badge/Multiplayer-Dedicated_Server-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/ASP.NET_Core-Backend-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-Database-316192?style=flat-square&logo=postgresql&logoColor=white" />
      </div>
    </td>
    <td width="50%" valign="top">
      <h4 align="center">🚇 Commute</h4>
      <a href="https://cedsson.itch.io/commute">
        <img src="assets/commute.jpg" alt="Commute Vertical Slice" width="100%" style="border-radius: 6px;" />
      </a>
      <p>
        A 10-minute <b>vertical slice and engine tech demo</b> built to integrate and test all subsystems in a playable FPS: Forward+ rendering, capsule-vs-triangle collision, FMOD spatial audio occlusion, and AI navmeshes.
      </p>
      <div align="center">
        <img src="https://img.shields.io/badge/Vertical_Slice-10_min-blueviolet?style=flat-square" />
        <img src="https://img.shields.io/badge/Engine-Tech_Demo-orange?style=flat-square" />
        <img src="https://img.shields.io/badge/itch.io-Playable_Demo-FA5C5C?style=flat-square&logo=itchdotio&logoColor=white" />
      </div>
    </td>
  </tr>
</table>

---

### ⚡ Open Source

* **[Krut.Netcode](https://github.com/Cedsson/Krut.Netcode)** `MIT` — High-performance, authoritative multiplayer netcode library for .NET.
  * **Zero allocations:** Steady-state messaging produces 0 B GC pressure with object pooling.
  * **Prediction & Reconciliation:** Instant local inputs with tick rewinds and smooth correction blending.
  * **Link Degradation Simulator:** Built-in simulation of latency spikes, burst packet loss, and jitter.

---

### 🛠️ Tech & Systems

* **Languages & Core:** `C#` &middot; `.NET 10` &middot; `Native AOT` &middot; `HLSL` &middot; `C/C++`
* **Graphics & Simulation:** `Direct3D 12` &middot; `Vulkan` &middot; `Forward+ Rendering` &middot; `Jitter2 Physics` &middot; `FMOD`
* **Backend & Infrastructure:** `ASP.NET Core` &middot; `PostgreSQL` &middot; `Docker` &middot; `Steamworks Auth`
