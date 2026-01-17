<img src="../ZARKHAM-X-Banner.png" alt="ZARKHAM dVPN" />

<div align="center">
  <h1>ZARKHAM</h1>
  <p><strong>PRIVATE BANDWIDTH SHARING</strong></p>
  
  <p>
    <a href="https://zarkham.xyz"><img src="https://img.shields.io/badge/Website-ZARKHAM-yellow?style=for-the-badge" alt="Website" /></a>
    <a href="https://github.com/zarkhamVPN/binaries/releases"><img src="https://img.shields.io/badge/GitHub-Releases-black?style=for-the-badge" alt="Releases" /></a>
    <a href="https://x.com/zarkhamVPN"><img src="https://img.shields.io/badge/Twitter-@zarkhamVPN-blue?style=for-the-badge" alt="Twitter" /></a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Go-1.23%2B-blue?style=flat-square" alt="Go" />
    <img src="https://img.shields.io/badge/Rust-Anchor-orange?style=flat-square" alt="Rust" />
    <img src="https://img.shields.io/badge/Svelte-5.0-ff3e00?style=flat-square" alt="Svelte" />
    <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square" alt="License: MIT" /></a>
  </p>

</div>

---

### THE PROTOCOL

Zarkham is a sovereign, decentralized VPN built on **Solana**. It replaces centralized ISPs with a trustless, private peer-to-peer market for bandwidth.

| Role | Function | Mission |
| :--- | :--- | :--- |
| **SEEKER** | Zero-Knowledge Client | Initiates ZK handshakes & ephemeral session keys. Total privacy. |
| **WARDEN** | Residential Relay | Provides high-reputation exit IPs. Validates cryptographic proofs. |
| **RYNE** | Consensus Engine | Proof-of-Bandwidth mechanism. Batches TCs for efficient settlement. |
| **SOLANA** | Private Settlement | Shielded micropayments. Instant sub-cent per-megabyte billing. |


---

### INSTALLATION

**Linux (Recommended)**
```bash
curl -sL https://raw.githubusercontent.com/zarkhamVPN/binaries/main/install.sh | bash 
```

**Manual Binary**
Grab the latest release for your architecture from the [Releases Page](https://github.com/zarkhamVPN/binaries/releases).

---

### RUN A NODE

**Become a Warden (Provide Bandwidth, Earn SOL)**
```bash
sudo ./zarkham gui --profile warden
```

**Connect as Seeker (Browse Privately, Pay-as-you-Go)**
```bash
sudo ./zarkham gui --profile seeker
```

---

<div align="center">
  <sub>Built by <a href="https://x.com/davidnzubee">Skipp</a>. Powered by <strong>Solana</strong>.</sub>
</div>
