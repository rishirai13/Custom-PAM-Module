# Custom PAM Module  
*Enhancing System Security with Elegance and Precision*  

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)  
[![Language](https://img.shields.io/badge/Language-C-00599C.svg)]()  
[![Status](https://img.shields.io/badge/Status-Completed-green.svg)]()  

---

## Overview  
Welcome to the **Custom PAM Module** project – a sophisticated solution designed to bolster system security through a custom-built Pluggable Authentication Module (PAM). Developed during my tenure as an intern at **THALES DIS Technology Pvt. Ltd.** in the Banking and Payment Service Department (June 2023 – July 2023), this project showcases a seamless blend of robust authentication design, automation, and cross-functional collaboration.  

Built from the ground up using **C**, this module enhances authentication workflows while ensuring scalability and reliability. Whether you're a security enthusiast or a developer exploring PAM integrations, this repository offers a glimpse into a production-ready security solution crafted with precision.

---

## Features  
- **Custom Authentication Logic**: A tailor-made PAM module to enforce advanced security policies.  
- **Automation Excellence**: Streamlined validation process for rapid deployment and consistent performance.  
- **Production-Ready**: Successfully integrated into real-world environments through cross-team collaboration.  
- **Lightweight & Efficient**: Optimized for performance without compromising security.  

---

## Project Highlights  
- **Designed & Implemented**: Engineered a bespoke PAM module using C to meet stringent security requirements.  
- **Automated Validation**: Developed an automated validation pipeline to ensure reliability and reduce deployment overhead.  
- **Team Synergy**: Worked closely with cross-functional teams at THALES to deploy the solution into production systems.  

---

## Getting Started  

### Prerequisites  
- **Compiler**: GCC or any C-compatible compiler  
- **Operating System**: Linux (PAM is Linux-specific)  
- **Dependencies**: `libpam-dev` for PAM development  

### Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/rishirai13/Custom-PAM-Module.git  
   cd Custom-PAM-Module  
   ```  
2. Compile the module:  
   ```bash  
   gcc -fPIC -c pam_custom.c -o pam_custom.o  
   gcc -shared -o pam_custom.so pam_custom.o -lpam  
   ```  
3. Deploy the module:  
   ```bash  
   sudo cp pam_custom.so /lib/security/  
   ```  
4. Configure PAM: Add the module to your PAM configuration file (e.g., `/etc/pam.d/` or `/etc/pam.conf`).  

### Usage  
- Integrate the module into your authentication stack by referencing `pam_custom.so` in your PAM configuration.  
- Test the module with a sample application or service requiring authentication.  

---

## Technical Details  
- **Language**: C  
- **Framework**: Linux PAM (Pluggable Authentication Modules)  
- **Focus**: Security, Automation, Integration  

This module adheres to PAM standards, ensuring compatibility with Linux-based authentication systems. The automated validation process leverages scripting and test cases to guarantee robustness before deployment.

---

## Contributions  
This project was completed as part of an internship and is currently in a stable state. While contributions are not actively sought, feel free to fork the repository and adapt it for your own use. Suggestions or issues can be raised via GitHub Issues.

---

## License  
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as per the terms.

---

## Acknowledgments  
- **THALES DIS Technology Pvt. Ltd.**: For providing the opportunity to work on cutting-edge security solutions.  
- **Mentors & Team**: For their guidance and collaboration during the internship.  

---

*Crafted with precision by [Rishi Rai](https://github.com/rishirai13) – June 2023*  
*Last Updated: March 24, 2025*  
