
# ✅ Simple To-do Project
### (A To-Do Management Application Written in Motoko on the Internet Computer Protocol)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Motoko](https://img.shields.io/badge/Motoko-FF6B00?style=flat&logo=dfinity&logoColor=white)](#)
[![Internet Computer](https://img.shields.io/badge/Internet%20Computer-000000?style=flat&logo=dfinity&logoColor=white)](#)
[![Made with Learning](https://img.shields.io/badge/Made%20with-Learning-1f425f.svg)](#)

This repository is a simple to-do management application developed using the **Motoko** programming language within the Internet Computer Protocol (ICP) ecosystem. It was created to practice decentralized application (dApp) development.

## 📚 Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation & Usage](#installation--usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

---

## About the Project
As part of my continuous self-improvement journey after graduating from Ankara University Computer Engineering, this project is a decentralized task management application running on the Internet Computer Protocol (ICP). Written in Motoko, it was created to reinforce blockchain-based application development skills.

- **Developer:** Haluk Can SARIÖZ
- **Type:** Decentralized Application (dApp)
- **Platform:** Internet Computer Protocol (ICP)
- **Purpose:** Hands-on learning of Motoko and the ICP ecosystem

---

## Features
- **Add Tasks** – Quickly add new to-do items to the list.
- **Complete Tasks** – Mark completed tasks or cross them off.
- **Delete Tasks** – Remove unwanted or finished tasks from the list.
- **Decentralized Architecture** – Smart contract (canister) architecture running on ICP infrastructure.

---

## Tech Stack

| Layer | Technology |
|:-------|:-----------|
| **Programming Language** | Motoko |
| **Platform** | Internet Computer Protocol (ICP) |
| **Development Environment** | DFX SDK |
| **Version Control** | Git & GitHub |

---

## Installation & Usage

### Prerequisites
Make sure the following tools are installed on your local machine:
- [DFX SDK](https://internetcomputer.org/docs/current/developer-docs/setup/install)
- [Node.js](https://nodejs.org/) (for the ICP development environment)
- Git

### Installation Steps

**1. Clone the repository:**
```bash
git clone https://github.com/halukcansarioz/Simple-To-do-Project.git
```

**2. Navigate to the project directory:**
```bash
cd Simple-To-do-Project
```

**3. Start the ICP local network:**
```bash
dfx start --background
```

**4. Compile and deploy the canister:**
```bash
dfx deploy
```

**5. Access the application:**
After deployment is complete, access the application at the local address displayed in the terminal (usually `http://127.0.0.1:4943`).

---

## Project Structure
```text
Simple-To-do-Project/
├── Main.mo            # Motoko smart contract (main application logic)
├── README.md          # Project documentation
└── .gitattributes     # Git configuration file
```

> ℹ️ **Note:** This project is designed as a smart contract (canister) running on the Internet Computer Protocol (ICP). The user interface can be provided via ICP's Candid interface or a separate frontend canister.

---

## Contributing
Contributions, bug reports, and feature requests are welcome!

1. **Fork** this repository.
2. Create a **Branch** (`git checkout -b feature/NewFeature`).
3. Make your changes and **Commit** (`git commit -m 'Add: New feature'`).
4. **Push** your code (`git push origin feature/NewFeature`).
5. Open a **Pull Request**.

---

<a name="contact"></a>
## Contact
**Haluk Can Sarıöz**

- GitHub: [@halukcansarioz](https://github.com/halukcansarioz)
- Email: [halukcansarioz19@gmail.com](mailto:halukcansarioz19@gmail.com)
- LinkedIn: [Haluk Can Sarıöz](https://www.linkedin.com/in/halukcansarioz)

---

*If you found this dApp project helpful, don't forget to ⭐ it!*

---

## License
This project is licensed under the [MIT License](LICENSE).
