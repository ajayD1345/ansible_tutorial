# ⚙️ Ansible Automation Project Tutorial

This repository contains a collection of **Ansible playbooks**, **roles**, and **configuration files** designed to automate common system administration tasks such as server bootstrapping, user management, and Apache installation/removal.

---

## 📂 Repository Structure

- **files/** — Holds static files and templates used during automation (e.g., configuration files, scripts).  
- **host_vars/** — Contains host-specific variables for targeted automation.  
- **roles/** — Defines reusable Ansible roles for modular and organized playbook execution.  
- **ansible.cfg** — Ansible configuration file defining environment settings.  
- **inventory** — Specifies managed hosts and their groupings.  
- **bootstrap.yml** — Sets up initial configurations, such as creating the “samaritan” user and preparing the environment.  
- **install_apache.yml** — Automates Apache installation and service setup.  
- **remove_apache.yml** — Handles Apache service removal and cleanup.  
- **site.yml** — Main playbook integrating multiple roles for full deployment automation.  
- **site_before.yml** — A pre-setup version of the main site playbook for earlier configurations.  
- **README.md** — Documentation for project understanding and usage.  

---

## 🧠 Purpose

This project demonstrates:
- Infrastructure automation using **Ansible**.  
- Configuration management and environment setup.  
- Modular playbook and role design.  
- Real-world DevOps workflow automation.  

---

## 🚀 Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/ansible-automation.git
   cd ansible-automation
   ```
2. Update the inventory file with your target hosts.
3. Run any playbook:
   ```
   ansible-playbook -i inventory bootstrap.yml
   ansible-playbook -i inventory install_apache.yml
   ansible-playbook -i inventory remove_apache.yml
   ```
# 🧩 Conclusion

This repository showcases practical Ansible automation in action — from initial system setup to full service deployment and teardown. It reflects hands-on experience with infrastructure-as-code, promoting consistency, repeatability, and scalability in DevOps environments.

## 🧑‍💻 Author
 - Hamed Ayojide

