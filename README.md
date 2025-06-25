# Zenth Secure Messaging Protocol (ZSMP)

Zenth Secure Messaging Protocol (ZSMP) is a privacy-focused, sovereign, and extensible messaging protocol developed by Sky Genesis Enterprise as part of the Zenth Cloud ecosystem. Built upon the Matrix protocol, ZSMP enables secure, decentralized communication while integrating tightly with Zenth's internal services and infrastructure.

## ✨ Features

- End-to-end encrypted messaging by default
- Authentication via Zenth SSO Server
- Event-driven protocol with support for text, media, and system messages
- Optional federation with fine-grained control
- Native integration with Zenth services (API, Monitoring, Admin, etc.)
- Fully open-source under AGPLv3

## 🏗 Architecture

ZSMP is based on the Matrix protocol stack but introduces its own:
- Identity and access model (Zenth SSO)
- Event format and routing system
- Server implementation (`zsmp-server`) and client (`zsmp-client`)
- Extensions tailored for cloud-native infrastructure messaging

## 📚 Repositories

- [`zsmp-spec`](https://github.com/zenthcloud/zsmp-spec) – Protocol specification
- [`zsmp-server`](https://github.com/zenthcloud/zsmp-server) – Server implementation
- [`zsmp-client`](https://github.com/zenthcloud/zsmp-client) – Reference client
- [`zsmp-bridge`](https://github.com/zenthcloud/zsmp-bridge) – Bridges to other protocols (Matrix/XMPP)
- [`zsmp-docs`](https://github.com/zenthcloud/zsmp-docs) – Developer documentation

## 🛡️ License

Zenth Secure Messaging Protocol is licensed under the **GNU Affero General Public License v3 (AGPLv3)**. See the `LICENSE` file for details.

---

Contributions, bug reports, and feature requests are welcome at [github.com/zenthcloud](https://github.com/zenthcloud).
