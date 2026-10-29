<div align="center" style="border: 1px solid #444; padding: 32px 16px;">
  <p align="center" style="margin: 0 0 12px;">
    <img src="https://raw.githubusercontent.com/NightAuth/.github/main/profile/banner.svg" alt="NightAuth" width="360" />
  </p>
  <p align="center">
    <strong>Zero-Trust Software Licensing, HWID Protection & Authentication Infrastructure.</strong><br />
    Cryptographically bound hardware licensing, asymmetric Curve25519 end-to-end encryption, and automated distribution tooling.
  </p>
  <p align="center">
    <a href="https://nightauth.org"><img src="https://img.shields.io/badge/WEBSITE-nightauth.org-2563eb?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
    <a href="https://nightauth.org/docs"><img src="https://img.shields.io/badge/DOCS-Quickstart_&_API-0284c7?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Docs" /></a>
    <a href="https://nightauth.org/blog"><img src="https://img.shields.io/badge/BLOG-Engineering_&_Security-7c3aed?style=for-the-badge&logo=rss&logoColor=white" alt="Blog" /></a>
    <a href="https://nightauth.org/blog/nightauth-vs-keyauth-authgg-comparison"><img src="https://img.shields.io/badge/BENCHMARK-vs_KeyAuth_&_Auth.gg-d97706?style=for-the-badge&logo=speedtest&logoColor=white" alt="Benchmark" /></a>
  </p>
  <p align="center">
    <img src="https://img.shields.io/badge/ENCRYPTION-Curve25519_+_ChaCha20-blue?style=flat-square" alt="Encryption" />
    <img src="https://img.shields.io/badge/HWID-Zero--Trust_Anti--Spoofing-purple?style=flat-square" alt="HWID" />
    <img src="https://img.shields.io/badge/LATENCY-%3C35ms_Global_Edge-emerald?style=flat-square" alt="Latency" />
    <img src="https://img.shields.io/badge/LANGUAGES-10_Official_Locales-orange?style=flat-square" alt="Languages" />
    <img src="https://img.shields.io/badge/LICENSE-Elastic_2.0-red?style=flat-square" alt="License" />
  </p>
</div>

<br />

### 🛡️ Why Developers Choose NightAuth (Architectural Comparison)

| Feature | NightAuth | KeyAuth | Auth.gg |
| :--- | :---: | :---: | :---: |
| **Transport Cryptography** | **Asymmetric Curve25519 (X25519) + ChaCha20-Poly1305** | Static AES-CBC (Vulnerable to MITM & Proxy Interception) | Legacy HTTPS / Plain JSON |
| **Hardware ID Locking (HWID)** | **Multi-Component Cryptographic Hash (Anti-Spoofing)** | Raw WMI Strings (Trivially Spoofed) | Simple Registry / MAC |
| **Edge Network Latency** | **< 35ms Global Anycast Edge Network** | Single-Origin VPS (Frequent Network Outages) | Unmaintained / High Latency |
| **Reseller System & Bots** | **Built-in Multi-Tier Credit Balances + Discord & Telegram Bots** | Manual API / Third-Party Scripts | Incomplete / Deprecated |
| **In-Memory Secure Streaming** | **Zero-Disk Decryption with Direct Memory Execution & Buffer Wiping** | Disk Writes Required | Not Supported |
| **Internationalization** | **10 Languages Supported Out of the Box across Documentation & SDKs** | English Only | English Only |

> 📖 **In-Depth Benchmark Analysis:** Read our full architectural comparison on the engineering blog: [NightAuth vs KeyAuth vs Auth.gg: Technical Security, Cryptography & Architecture Comparison](https://nightauth.org/blog/nightauth-vs-keyauth-authgg-comparison).

<br />

<table width="100%" cellpadding="8" cellspacing="12" style="border: 1px solid #444; padding: 16px;">
  <tr>
    <!-- Columna 1: Client SDKs -->
    <td valign="top" width="50%">
      <h3>
        <img src="https://api.iconify.design/lucide/code-xml.svg?color=%2360a5fa" width="18" height="18" alt="" vertical-align="middle" />
        &nbsp;Official Client SDKs (9 Languages)
      </h3>
      <table width="100%" style="border: 1px solid #30363d; border-collapse: collapse;">
        <thead>
          <tr>
            <th align="left" style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;">Language</th>
            <th align="left" style="padding: 6px 8px; border-bottom: 1px solid #30363d;">Repository</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;"><img src="https://cdn.simpleicons.org/c/A8B9CC/white" width="16" height="16" vertical-align="middle" />&nbsp; C</td>
            <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://github.com/NightAuth/NightAuth-C-SDK"><strong>NightAuth-C-SDK</strong></a> (Header-Only C11)</td>
          </tr>
          <tr>
            <td style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" width="16" height="16" vertical-align="middle" />&nbsp; C++</td>
            <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://github.com/NightAuth/NightAuth-CPP-SDK"><strong>NightAuth-CPP-SDK</strong></a> (Header-Only C++17)</td>
          </tr>
          <tr>
            <td style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" width="16" height="16" vertical-align="middle" />&nbsp; C#</td>
            <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://github.com/NightAuth/NightAuth-CSharp-SDK"><strong>NightAuth-CSharp-SDK</strong></a> (.NET 8/9/10 & WPF)</td>
          </tr>
          <tr>
            <td style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" width="16" height="16" vertical-align="middle" />&nbsp; Go</td>
            <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://github.com/NightAuth/NightAuth-Go-SDK"><strong>NightAuth-Go-SDK</strong></a> (Go 1.21+)</td>
          </tr>
          <tr>
            <td style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="16" height="16" vertical-align="middle" />&nbsp; Java</td>
            <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://github.com/NightAuth/NightAuth-Java-SDK"><strong>NightAuth-Java-SDK</strong></a> (Java 17/21 & JavaFX)</td>
          </tr>
          <tr>
            <td style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="16" height="16" vertical-align="middle" />&nbsp; Node.js</td>
            <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://github.com/NightAuth/NightAuth-Node.js-SDK"><strong>NightAuth-Node.js-SDK</strong></a> (Node.js 18+)</td>
          </tr>
          <tr>
            <td style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="16" height="16" vertical-align="middle" />&nbsp; Python</td>
            <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://github.com/NightAuth/NightAuth-Python-SDK"><strong>NightAuth-Python-SDK</strong></a> (Python 3.10+ & PyQt6)</td>
          </tr>
          <tr>
            <td style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;"><img src="https://cdn.simpleicons.org/rust/dea584/white" width="16" height="16" vertical-align="middle" />&nbsp; Rust</td>
            <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://github.com/NightAuth/NightAuth-Rust-SDK"><strong>NightAuth-Rust-SDK</strong></a> (Rust 1.75+ & Win32 GDI)</td>
          </tr>
          <tr>
            <td style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="16" height="16" vertical-align="middle" />&nbsp; TypeScript</td>
            <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://github.com/NightAuth/NightAuth-TypeScript-SDK"><strong>NightAuth-TypeScript-SDK</strong></a> (Modern ESM/CJS)</td>
          </tr>
        </tbody>
      </table>
    </td>
    <!-- Columna 2: Bots -->
    <td valign="top" width="25%">
      <h3>
        <img src="https://api.iconify.design/lucide/bot.svg?color=%23a855f7" width="18" height="18" alt="" vertical-align="middle" />
        &nbsp;Automated Bots
      </h3>
      <table width="100%" style="border: 1px solid #30363d; border-collapse: collapse;">
        <thead>
          <tr>
            <th align="left" style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;">Platform</th>
            <th align="left" style="padding: 6px 8px; border-bottom: 1px solid #30363d;">Source</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;"><img src="https://cdn.simpleicons.org/discord/5865F2" width="16" height="16" vertical-align="middle" />&nbsp; Discord</td>
            <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://github.com/NightAuth/NightAuth-Discord-Bot"><strong>Discord Bot</strong></a></td>
          </tr>
          <tr>
            <td style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;"><img src="https://cdn.simpleicons.org/telegram/26A5E4" width="16" height="16" vertical-align="middle" />&nbsp; Telegram</td>
            <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://github.com/NightAuth/NightAuth-Telegram-Bot"><strong>Telegram Bot</strong></a></td>
          </tr>
        </tbody>
      </table>
    </td>
    <!-- Columna 3: Customer Portal -->
    <td valign="top" width="25%">
      <h3>
        <img src="https://api.iconify.design/lucide/user-round.svg?color=%2338bdf8" width="18" height="18" alt="" vertical-align="middle" />
        &nbsp;Customer Portals
      </h3>
      <table width="100%" style="border: 1px solid #30363d; border-collapse: collapse;">
        <thead>
          <tr>
            <th align="left" style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;">Framework</th>
            <th align="left" style="padding: 6px 8px; border-bottom: 1px solid #30363d;">Example</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;"><img src="https://cdn.simpleicons.org/astro/BC52EE" width="16" height="16" vertical-align="middle" />&nbsp; Astro</td>
            <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://github.com/NightAuth/NightAuth-Astro-Portal"><strong>Astro Portal</strong></a></td>
          </tr>
          <tr>
            <td style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;"><img src="https://cdn.simpleicons.org/htmx/3366CC" width="16" height="16" vertical-align="middle" />&nbsp; HTMX</td>
            <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://github.com/NightAuth/NightAuth-HTMX-Portal"><strong>HTMX Portal</strong></a></td>
          </tr>
          <tr>
            <td style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;"><img src="https://cdn.simpleicons.org/php/777BB4" width="16" height="16" vertical-align="middle" />&nbsp; PHP</td>
            <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://github.com/NightAuth/NightAuth-PHP-Portal"><strong>PHP Portal</strong></a></td>
          </tr>
          <tr>
            <td style="border-right: 1px solid #30363d; padding: 6px 8px; border-bottom: 1px solid #30363d;"><img src="https://cdn.simpleicons.org/vite/646CFF" width="16" height="16" vertical-align="middle" />&nbsp; Vite</td>
            <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://github.com/NightAuth/NightAuth-Vite-Portal"><strong>Vite Portal</strong></a></td>
          </tr>
        </tbody>
      </table>
    </td>
  </tr>
</table>

### 🔗 Quick Links & Developer Ecosystem

<table width="100%" style="border: 1px solid #444; border-collapse: collapse;">
  <thead>
    <tr>
      <th align="left" style="padding: 6px 8px; border-bottom: 1px solid #30363d;">Resource</th>
      <th align="left" style="padding: 6px 8px; border-bottom: 1px solid #30363d;">Description</th>
      <th align="left" style="padding: 6px 8px; border-bottom: 1px solid #30363d;">URL</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><strong>Official Website</strong></td>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;">Platform overview, pricing plans, and dashboard access</td>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://nightauth.org">nightauth.org</a></td>
    </tr>
    <tr>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><strong>Documentation & Quickstart</strong></td>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;">Developer tutorials, SDK installation guides, and API explorer</td>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://nightauth.org/docs">nightauth.org/docs</a></td>
    </tr>
    <tr>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><strong>Engineering & Security Blog</strong></td>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;">Deep dives on cryptography, anti-tamper, HWID, and comparisons</td>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://nightauth.org/blog">nightauth.org/blog</a></td>
    </tr>
    <tr>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><strong>Discord Community</strong></td>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;">Official developer community and support server</td>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://nightauth.org/discord">nightauth.org/discord</a></td>
    </tr>
    <tr>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><strong>Telegram Community</strong></td>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;">Official announcement channel and community group</td>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://nightauth.org/telegram">nightauth.org/telegram</a></td>
    </tr>
    <tr>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><strong>YouTube Channel</strong></td>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;">Video tutorials, implementation guides, and demos</td>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://nightauth.org/youtube">nightauth.org/youtube</a></td>
    </tr>
    <tr>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><strong>TikTok Channel</strong></td>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;">Product updates, feature previews, and short tutorials</td>
      <td style="padding: 6px 8px; border-bottom: 1px solid #30363d;"><a href="https://nightauth.org/tiktok">nightauth.org/tiktok</a></td>
    </tr>
  </tbody>
</table>
