<div align="center">

![Alessandro Mainardi - Banner](./assets/banner.svg)

<br>

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-alexmaina.dev-00e5ff?style=for-the-badge&logoColor=black)](https://alexmaina.dev/)
[![Bio Hub](https://img.shields.io/badge/🔗_Bio_Hub-bio.alexmaina.dev-7c3aed?style=for-the-badge&logoColor=white)](https://bio.alexmaina.dev/)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.23781231-007ec6?style=for-the-badge&logo=doi&logoColor=white)](https://doi.org/10.5281/zenodo.23781231)
[![Wikidata](https://img.shields.io/badge/Wikidata-Q141886579-339966?style=for-the-badge&logo=wikidata&logoColor=white)](https://www.wikidata.org/wiki/Q141886579)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0003--7003--7247-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0003-7003-7247)
[![Guide Tecniche](https://img.shields.io/badge/📚_Guide_Tecniche-alexmaina.dev%2Fguide-10b981?style=for-the-badge&logoColor=white)](https://alexmaina.dev/guide/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Alessandro_Mainardi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alessandro-mainardi-ab812823b/)
[![X/Twitter](https://img.shields.io/badge/Twitter-@Alex__Maina__-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/Alex_Maina_)
[![Email](https://img.shields.io/badge/Email-maina@alexmaina.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:maina@alexmaina.dev)

</div>

---

### 👨‍💻 Engineering Snapshot

```json
{
  "name": "Alessandro Mainardi",
  "role": "Software Developer & Computer Engineering Student",
  "institution": "Alma Mater Studiorum - Università di Bologna (UniBo)",
  "degree_course": "Ingegneria Informatica (Computer Science & Engineering)",
  "orcid": "https://orcid.org/0009-0003-7003-7247",
  "location": "Bologna, Italy 🇮🇹",
  "core_competencies": {
    "cloud_enterprise": ["Microsoft 365", "Microsoft Entra ID", "Microsoft Azure", "Intune MDM"],
    "systems_infrastructure": ["Windows Server 2025", "Hyper-V", "Storage Spaces ReFS", "Docker"],
    "zero_trust_networking": ["Tailscale WireGuard Mesh", "Cloudflare Outbound Tunnels"],
    "software_engineering": ["Swift 5.10", "TypeScript", "Next.js 15", "React 19", "Python"],
    "health_informatics": ["HL7 CDA R2", "Apple HealthKit", "LOINC", "Zero-Cloud Mobile Edge"]
  },
  "engineering_ethos": "Building resilient, sovereign, and zero-compromise systems"
}
```

---

### ⭐ Showcase Progetti & Architetture

<table>
  <tr>
    <td colspan="2" valign="top">
      <h3 align="center">⚕️ RosettaEdge — Mobile Edge Zero-Cloud &amp; FSE 2.0</h3>
      <p align="center">
        <a href="https://alexmaina.dev/Health-App/"><b>[Landing &amp; Docs ↗]</b></a> • 
        <a href="https://alexmaina.dev/Health-App/rosettaedge-monografia-tecnica.pdf"><b>[Monografia Tecnica A4 (PDF) ↗]</b></a> • 
        <a href="https://doi.org/10.5281/zenodo.23781231"><b>[DOI Zenodo ↗]</b></a> • 
        <a href="https://github.com/AlexMaina05/Health-App"><b>[Repository GitHub]</b></a>
      </p>
      <p>Architettura software nativa iOS/watchOS per l'interoperabilità semantica deterministica tra Fascicolo Sanitario Elettronico (HL7 CDA R2) e Apple HealthKit con tecnologia Zero-Cloud e crittografia hardware Secure Enclave conforme GDPR Art. 9:</p>
      <ul>
        <li><b>Monografia Scientifica Peer-Reviewed (44 Pagine ISO A4):</b> Documentazione teorica ed empirica completa (<a href="https://doi.org/10.5281/zenodo.23781231">DOI: 10.5281/zenodo.23781231</a>).</li>
        <li><b>Motore di Transcodifica Deterministico:</b> Mappatura ontologica bidirezionale LOINC ↔ HealthKit con garanzie matematiche di non-alterazione semantica e latenze on-device &lt; 100ms.</li>
        <li><b>Privacy-by-Design &amp; Identity Firewall:</b> Elaborazione esclusivamente on-device, nessun dato trasmesso a server terzi o cloud.</li>
      </ul>
      <p><b>Stack:</b> <code>Swift 5.10</code> <code>Apple HealthKit</code> <code>Core Data</code> <code>CryptoKit</code> <code>HL7 CDA R2</code> <code>LOINC Standard</code> <code>Zero-Cloud</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🚀 GitOps Auto-Deployer</h3>
      <p align="center">
        <a href="https://doi.org/10.5281/zenodo.23781231"><b>[DOI Zenodo ↗]</b></a> • 
        <a href="https://github.com/AlexMaina05/gitops_deployer"><b>[Repository GitHub]</b></a>
      </p>
      <p>Microservizio asincrono sviluppato in Python con FastAPI per la continuous delivery di stack containerizzati con sicurezza crittografica HMAC-SHA256 e notifiche Telegram/n8n:</p>
      <ul>
        <li><b>118 Test Unitari & Adversarial:</b> Suite completa con prevenzione timing attack e command injection.</li>
        <li><b>DOI Cern/Zenodo:</b> Software archiviato e citabile scientificamente (DOI 10.5281/zenodo.23781231).</li>
      </ul>
      <p><b>Stack:</b> <code>Python 3.12</code> <code>FastAPI</code> <code>Docker Compose</code> <code>HMAC-SHA256</code> <code>Telegram API</code> <code>uv</code></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🏛️ HP Fortress Homelab</h3>
      <p align="center">
        <a href="https://alexmaina.dev/hp-fortress-homelab/"><b>[Portale Live ↗]</b></a> • 
        <a href="https://github.com/AlexMaina05/hp-fortress-homelab"><b>[Repository GitHub]</b></a>
      </p>
      <p>Infrastruttura server enterprise ibrida on-premise operativa 24/7 su Windows Server 2025, Hyper-V, ReFS e rete Zero-Trust Cloudflare/Tailscale.</p>
      <p><b>Stack:</b> <code>Windows Server 2025</code> <code>Hyper-V</code> <code>Docker</code> <code>Tailscale</code> <code>Cloudflare</code> <code>ReFS</code> <code>Veeam</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🛡️ PII Redactor Lite</h3>
      <p align="center">
        <a href="https://github.com/AlexMaina05/pii-redactor-lite"><b>[Repository GitHub ↗]</b></a>
      </p>
      <p>Applicazione per la sanitizzazione intelligente e reversibile di dati personali identificabili (PII) prima della condivisione con LLM:</p>
      <ul>
        <li>Riconoscimento ed estrazione entità contestuale tramite Google Gemini Flash-Lite.</li>
        <li>Sostituzione con token crittografici reversibili per permettere la de-anonimizzazione autorizzata a valle.</li>
      </ul>
      <p><b>Stack:</b> <code>TypeScript</code> <code>Gemini Flash-Lite</code> <code>Privacy by Design</code></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">📐 3D Parametric CAD Web</h3>
      <p align="center">
        <a href="https://github.com/AlexMaina05/3d-model"><b>[Repository GitHub ↗]</b></a>
      </p>
      <p>Modellatore CAD parametrico client-side eseguibile interamente nel browser per la prototipazione rapida e la stampa 3D FDM/SLA:</p>
      <ul>
        <li>Kernel geometrico OpenCascade compilato in WebAssembly (WASM).</li>
        <li>Generazione ed esportazione parametrica di mesh e solidi nei formati standard STL e STEP.</li>
      </ul>
      <p><b>Stack:</b> <code>TypeScript</code> <code>Replicad</code> <code>OpenCascade WASM</code> <code>3D Graphics</code></p>
    </td>
  </tr>
</table>

---

### 🛠️ Stack Tecnologico & Strumenti

<div align="center">

#### 💻 Linguaggi di Programmazione
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

#### ☁️ Cloud, Sistemi & Reti
![Microsoft 365](https://img.shields.io/badge/Microsoft_365-D83B01?style=for-the-badge&logo=microsoft&logoColor=white)
![Microsoft Entra ID](https://img.shields.io/badge/Entra_ID-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Microsoft Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows_Server_2025-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Hyper-V](https://img.shields.io/badge/Hyper--V-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_Debian/Ubuntu-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Zero--Trust-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale_WireGuard-24292E?style=for-the-badge&logo=tailscale&logoColor=white)

#### ⚡ Framework & Strumenti Web
![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

</div>

---

### 📚 Archivio Didattico & Guide Tecniche Open Source

Documento regolarmente le mie sperimentazioni, architetture e percorsi di studio nell'hub open source [alexmaina.dev/guide/](https://alexmaina.dev/guide/):

| Categoria | Argomento Guida | Risorsa & Documentazione |
| :--- | :--- | :--- |
| ☁️ **Cloud M365** | Percorsi Certificazioni Microsoft 365, Copilot & Azure | [ms365/](https://alexmaina.dev/ms365/) |
| 🐳 **Docker & SSL** | Risolvere Loop "Too Many Redirects" su WordPress Docker | [wordpress-docker-redirect-loop/](https://alexmaina.dev/wordpress-docker-redirect-loop/) |
| 🛡️ **Entra ID** | Risoluzione Errore AADSTS50011 (Redirect URI Mismatch) | [entra-id-redirect-uri-aadsts50011/](https://alexmaina.dev/entra-id-redirect-uri-aadsts50011/) |
| 💾 **Storage QNAP** | QNAP Container Station: Conflitti Porte 80/443 & Reverse Proxy | [qnap-docker-reverse-proxy/](https://alexmaina.dev/qnap-docker-reverse-proxy/) |
| ⚡ **M365 Automazione** | Rinnovo Automatico Tenant M365 E5 Developer (90 Giorni) | [m365-developer-rinnovo-automatico/](https://alexmaina.dev/m365-developer-rinnovo-automatico/) |
| 🔒 **Zero-Trust** | Tailscale Subnet Router & Pi-hole Anti-CGNAT | [tailscale-pihole-homelab-cgnat/](https://alexmaina.dev/tailscale-pihole-homelab-cgnat/) |
| 🐍 **Modern Python** | Modern Python con uv, Lockfile Deterministico & CI/CD Ultra-Rapida | [python-uv-github-actions/](https://alexmaina.dev/python-uv-github-actions/) |
| 🔧 **M365 Sandbox** | Configurazione Developer Zero-Risk & Sync-Magic | [configurazione-developer-zerorisk/](https://alexmaina.dev/configurazione-developer-zerorisk/) |
| 🛡️ **Cybersecurity** | Guida alla Sicurezza Informatica Base & Privacy | [sicurezza/](https://alexmaina.dev/sicurezza/) |
| 🌐 **Hosting NAS** | Web App WordPress e Database su NAS QNAP | [wordpress-su-nas/](https://alexmaina.dev/wordpress-su-nas/) |
| 🐍 **Linguaggi** | Guida Completa a Python per Principianti | [guida_python/](https://alexmaina.dev/guida_python/) |
| ⚡ **Frontend** | Sviluppo Web Statico con GitHub Pages & Custom Domain | [guida_sito/](https://alexmaina.dev/guida_sito/) |
| 🧮 **Web App** | Calcolatrice Reattiva con HTML, CSS e JavaScript | [guida_calculator/](https://alexmaina.dev/guida_calculator/) |
| 🏓 **Gamedev** | Gioco Pong con HTML5 Canvas e Loop a 60 FPS | [guida_pong/](https://alexmaina.dev/guida_pong/) |
| ✒️ **Documentazione** | Guida Completa al Linguaggio Markdown per Developer | [guida_markdown/](https://alexmaina.dev/guida_markdown/) |

---

### 📊 Attività & Metriche GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AlexMaina05&show_icons=true&theme=tokyonight&hide_border=true&bg_color=070a14&title_color=00e5ff&icon_color=00e5ff&text_color=f8fafc" alt="Statistiche GitHub di Alessandro Mainardi" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AlexMaina05&layout=compact&theme=tokyonight&hide_border=true&bg_color=070a14&title_color=a855f7&text_color=f8fafc" alt="Linguaggi più usati" height="165" />
</div>

---

<div align="center">

💡 *"La conoscenza è potere, ma la condivisione della conoscenza è libertà."*

🌐 **[alexmaina.dev](https://alexmaina.dev/)** • 🔗 **[bio.alexmaina.dev](https://bio.alexmaina.dev/)** • 📧 **[maina@alexmaina.dev](mailto:maina@alexmaina.dev)**

</div>
