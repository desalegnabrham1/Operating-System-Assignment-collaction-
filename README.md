# Operating-System-Assignment-collaction-
# Operating System Assignment Collection

This repository contains my Operating System assignment submissions. The main deliverable included here is a step‑by‑step report (PDF) describing how to install Red Hat Enterprise Linux (RHEL) Server on a virtual machine.

Author: Abrham Desalegn  
GitHub: @desalegnabrham1  
Student ID: 1600609

---

## Contents

- `Installation_of_RHEL_Server_on_VM_Abrham_Desalegn_ID_1600609.pdf`  
  A complete installation guide and documentation for installing RHEL Server on a virtual machine. The PDF contains screenshots, configuration steps, and notes.

(If you clone or browse the repo, you will find the PDF at the root of the repository.)

---

## Purpose

This repository is intended to document and share the installation process I followed for deploying RHEL Server inside a VM for the Operating System course assignment. The PDF is written as a reproducible guide that other students or users can follow.

---

## How to view

- On GitHub: click the PDF file to preview it in the browser.
- Locally:
  1. Clone the repository:
     ```
     git clone https://github.com/desalegnabrham1/Operating-System-Assignment-collaction-.git
     ```
  2. Open the PDF with your preferred PDF viewer:
     - Linux: Evince, Okular, or `xdg-open`
     - macOS: Preview
     - Windows: Adobe Reader or built-in viewer

---

## Summary of the PDF (quick)

The included PDF covers:
- Preparing a virtual machine (VM) environment (VirtualBox / VMware recommendations)
- Configuring VM resources (CPU, RAM, disk)
- Attaching the RHEL ISO and booting the installer
- Partitioning, network, and package selection
- Post-installation steps: enabling network, installing updates, basic user creation, and enabling services
- Screenshots illustrating key installer screens and commands used
- Troubleshooting tips and final verification steps

---

## Reproduce the setup (brief)

1. Create a new VM with recommended resources (e.g., 2+ CPUs, 4+ GB RAM, 20+ GB disk).
2. Attach the RHEL Server ISO and boot the VM.
3. Follow the installer steps highlighted in the PDF (language, keyboard, installation destination, network).
4. After installation, log in and perform the basic checks and commands listed in the guide (update packages, configure network, enable sshd if remote access required).

---

## Notes & Recommendations

- Use a licensed/correct RHEL ISO or a CentOS/AlmaLinux equivalent if you do not have RHEL subscription access.
- If using cloud VMs, adjust steps accordingly (cloud-init, images, cloud provider network/security groups).
- The PDF is the authoritative walkthrough — follow screenshots and commands there for the most detail.

---

## License

If you want to reuse this work, please contact the author. (No license file included — add one if you want to permit reuse, e.g., MIT.)

---

## Contact

For questions or clarifications:
- GitHub: https://github.com/desalegnabrham1
- Author: Abrham Desalegn (Student ID 1600609)

Thank you.
