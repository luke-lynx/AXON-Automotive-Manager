# AXON - Automotive Manager

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Status: In Development](https://img.shields.io/badge/Status-In%20Development-orange.svg)](#)

**Automation platform for automotive workshops focused on professional budget generation and technical reports.**

---

## 📋 Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Project Roadmap](#project-roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

---

## 🎯 Overview

**AXON** is an intelligent management system designed to streamline operations in automotive workshops. It automates the creation of professional budgets and technical reports, eliminating manual, time-consuming document preparation and allowing technicians to focus on their core expertise: vehicle diagnostics and repairs.

Built with Python and designed for scalability, AXON transforms workshop management from a bottleneck into a competitive advantage.

### The Problem

Automotive service providers face a critical inefficiency:
- ⏱️ Hours spent manually creating budgets and reports
- 📄 Inconsistent document formatting and professionalism
- 💼 Complex management software that doesn't fit mobile service workflows
- 🚗 Loss of focus on actual vehicle diagnostics and repairs

### The Solution

AXON replaces manual processes with an intelligent, automated system that generates structured, professional PDF documents ready for client delivery via email or messaging applications.

---

## ✨ Key Features

### MVP - Version 0.1

#### 📊 Professional Budget Generation
- **Intelligent Data Collection**: Client information, vehicle specifications (make, model, license plate, engine type)
- **Dynamic Cost Calculation**: Automatic breakdown of labor hours and parts costs
- **Professional Output**: Generates structured PDF documents with professional formatting
- **Client-Ready**: PDFs optimized for email and messaging app delivery

#### 🔧 Core Capabilities
- Real-time budget calculations
- Customizable pricing models
- Client database management
- Multiple budget templates
- Professional PDF export

---

## 🛠️ Technology Stack

### Core
- **Language**: Python 3.8+
- **Primary Use**: Data handling, automation, document generation

### Libraries (Current & Planned)
- **fpdf2**: Professional PDF document generation
- **Flask/Django**: Web interface (planned for v0.2+)
- **SQLAlchemy**: Database ORM (planned)
- **Pydantic**: Data validation

### Development Tools
- Git & GitHub
- Python Virtual Environment
- pytest (planned for testing)

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)
- Virtual environment (recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/luke-lynx/AXON-Automotive-Manager.git
   cd AXON-Automotive-Manager
   ```

2. **Create virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run AXON**
   ```bash
   python main.py
   ```

### Configuration

Create a `.env` file in the project root:
```env
# Database configuration
DATABASE_URL=sqlite:///axon.db

# PDF settings
PDF_FONT_SIZE=11
PDF_MARGIN=10

# API settings (future)
API_PORT=5000
```

---

## 📈 Project Roadmap

### v0.1 (Current)
- ✅ Professional budget generation
- ✅ PDF export functionality
- ✅ Client data collection
- ✅ Cost calculation engine

### v0.2 (Planned)
- [ ] Technical Reports with photo attachments
- [ ] Data validation and error correction module
- [ ] Client database with edit/update capabilities
- [ ] Budget templates and customization
- [ ] Service history tracking

### v0.3 (Planned)
- [ ] Web interface (Flask/Django)
- [ ] Multi-user support with authentication
- [ ] Advanced reporting and analytics
- [ ] Email integration for direct client delivery
- [ ] Cloud synchronization

### v1.0 (Future)
- [ ] Mobile application (iOS/Android)
- [ ] Real-time collaboration features
- [ ] Payment integration
- [ ] Advanced analytics dashboard
- [ ] AI-powered service recommendations

---

## 💡 Architecture

```
AXON/
├── src/
│   ├── core/              # Core business logic
│   ├── models/            # Data models
│   ├── generators/        # PDF and document generation
│   ├── services/          # Business services
│   └── utils/             # Utility functions
├── tests/                 # Test suite
├── docs/                  # Documentation
├── requirements.txt       # Project dependencies
├── .env.example           # Environment variables template
└── main.py               # Application entry point
```

---

## 🔄 Workflow Example

```
Client Request
    ↓
Data Input (Client, Vehicle, Services)
    ↓
Cost Calculation (Labor + Parts)
    ↓
Professional Document Generation (PDF)
    ↓
Client Delivery (Email/WhatsApp)
    ↓
Document Archive & History
```

---

## 🤝 Contributing

Contributions are welcome! Please follow these guidelines:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Standards
- Follow PEP 8 style guidelines
- Write unit tests for new features
- Update documentation accordingly
- Use meaningful commit messages

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Lucas Barbosa Neumann**

- 🔧 Automotive Technician (Specialized in Mechanical & Electrical Systems)
- 💻 Future Computer Engineer
- 🚀 Creator of AXON - Automotive Manager

### Contact & Social
- GitHub: [@luke-lynx](https://github.com/luke-lynx)
- Email: Available upon request

---

## 🎓 Project Purpose

AXON is my first portfolio project, born from real professional necessity. As an automotive technician, I experienced firsthand the inefficiencies in workshop management. Rather than accept these bottlenecks, I decided to build a solution that:

- **Saves time**: Less document creation, more vehicle repairs
- **Increases professionalism**: Clients receive structured, branded documents
- **Scales efficiency**: One professional tool vs. multiple fragmented solutions
- **Demonstrates expertise**: Portfolio project showcasing full software development lifecycle

---

## ⚡ Quick Stats

| Metric | Value |
|--------|-------|
| Language | Python |
| License | MIT |
| Status | In Development |
| Current Version | 0.1 (MVP) |
| Python Support | 3.8+ |

---

## 🙏 Acknowledgments

- Inspired by real-world workflow optimization
- Built with focus on professional automotive services
- Community-driven development approach

---

**"Does a programmer only work at this hour??" — April 23, 2026, 01:24 AM.**

*Making automotive workshop management efficient, professional, and accessible.*
