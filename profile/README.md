# Museum Monitoring (MuMo)

🏛️ **Open-source museum environmental monitoring solution**

Bringing affordable, open-source alternatives to museum monitoring modules through collaborative innovation.

---

## 🎯 Project Overview

Museum Monitoring (MuMo) is a comprehensive open-source solution designed to help museums monitor and preserve their collections through advanced environmental sensing and data management. This project represents a collaboration between:

- **University of Antwerp**
- **IDLab - Ghent University - IMEC** 
- **Fashion Museum Antwerp (MoMu)**

## 🏗️ Architecture Overview

MuMo consists of three interconnected components that work together to provide a complete monitoring ecosystem:

### 1. 📡 Open-Source Hardware
Custom PCB boards supporting multiple sensors that transmit measurements via LoRaWAN through The Things Network.

### 2. 📊 Follow-up Dashboard
A PHP-based administration and monitoring platform that handles:
- LoRaWAN data ingestion from The Things Network
- User and group management with flexible permissions
- Real-time sensor data visualization
- Data pipeline orchestration for semantic transformation

### 3. 🔍 Query Dashboard
A Svelte-based client-side application enabling:
- Solid authentication for secure access
- Dynamic semantic data querying across multiple datastreams
- Complex query building and visualization
- Data export capabilities (CSV format)

## 🚀 Getting Started

### For Museums

**Option 1: MuMo as a Service** 🌐
- Low-cost subscription model
- Hardware rental included
- Minimal setup required
- Professional support

**Option 2: Self-Hosted** 🔧
- Full control over your instance
- Customizable to your needs
- Requires initial investment and technical setup
- Complete data sovereignty

### For Developers

Explore our repositories to contribute or deploy your own instance:

```bash
# Clone platform repository
git clone --recursive git@github.com:MuseumMonitoring/mumo-platform.git
```

## 📚 Repository Guide

| Component | Technology | Repository | Description |
|-----------|------------|------------|-------------|
| **Hardware PCB** | PCB Design, C++ | [`hardware`](https://github.com/Strooom/MuMo-V2-Node-PCB) | Node boards |
| **Firmware** | C++ | [`firmware`](https://github.com/Strooom/MuMo-v2-Node-SW) | Node firmware |
| **Dashboard** | PHP, MySQL | [`dashboard`](https://github.com/MuseumMonitoring/dashboard) | Admin interface and data ingestion |
| **Data Pipeline** | Javascript, RDF | [`data-pipeline`](https://github.com/MuseumMonitoring/pipeline) | Semantic data transformation |
| **Graphs Client** | Svelte, Solid | [`graphs-dashboard`](https://github.com/MuseumMonitoring/graphs) | Semantic data querying interface |
| **Deployment** | Docker, nginx | [`mumo-platform`](https://github.com/MuseumMonitoring/mumo-platform) | Deployment repository with docker-compose files and nginx configs |

## 🔗 Semantic Web Integration

MuMo leverages modern semantic web technologies to create interoperable museum monitoring data:

- **Linked Data EventStreams** for real-time data publishing
- **Solid pods** for decentralized data storage
- **RDF/OSLO** for standardized data representation
- **Permission-based access control** synchronized across systems

This approach enables museums to:
- Maintain data interoperability between instances
- Participate in a growing museum monitoring dataspace
- Combine data from multiple institutions for research
- Future-proof their monitoring infrastructure

## 🛠️ Technology Stack

### Backend
- **PHP** - Dashboard and API server
- **MySQL** - Primary data storage  
- **RDF-Connect** - Data pipeline and semantic transformation

### Frontend
- **Svelte** - Query dashboard interface

### Hardware & Infrastructure
- **LoRaWAN** - Long-range sensor communication
- **The Things Network** - LoRaWAN network provider
- **Custom PCB** - Specialized sensor boards


## 🤝 Contributing

We welcome contributions from the community! Whether you're:

- **Hardware engineers** - Help improve sensor designs
- **Backend developers** - Enhance the dashboard and pipeline
- **Frontend developers** - Improve the query interface  
- **Museum professionals** - Provide domain expertise
- **Researchers** - Use and extend our semantic data models

Check out our [Contributing Guide](CONTRIBUTING.md) to get started.

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

- **Issues & Bug Reports**: [GitHub Issues](https://github.com/MuseumMonitoring/issues)
- **General Questions**: [GitHub Discussions](https://github.com/MuseumMonitoring/discussions)
- **Security Issues**: [Security Policy](SECURITY.md)

## 🙏 Acknowledgments

- IDLab - IMEC - Ghent University - Semantic web expertise  
- Fashion Museum Antwerp (MoMu) - Domain expertise and testing
- University of Antwerp - Research and development
- The Things Network - LoRaWAN infrastructure

---

**🌟 Star our repositories to support open-source museum monitoring!**

