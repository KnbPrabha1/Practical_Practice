<img width="953" alt="image" src="https://github.com/user-attachments/assets/2237244d-34f1-42f8-bb43-8bca7a8b78a1" />


# 🧪 Cybersecurity Lab Setup Using Oracle VirtualBox

To practice cybersecurity techniques like penetration testing and threat modeling, it’s important to create a controlled, safe environment. I set up a basic lab using virtualization technology, which allows running multiple operating systems on one physical computer.

---

## 🖥️ Tools Used

- **Oracle VirtualBox:** Free, open-source virtualization software that lets you create and run virtual machines (VMs).
- **Windows VM:** Acts as the **victim** machine.
- **Kali Linux VM:** Acts as the **attacker** machine with pre-installed security tools.

---

## 🏗️ Lab Setup Steps

1. **Install Oracle VirtualBox**
   - Download from [virtualbox.org](https://www.virtualbox.org/) and install it on your host machine (your main computer).

2. **Create Windows VM (Victim)**
   - Use a Windows installation ISO or pre-configured image.
   - Allocate resources: 2-4 GB RAM, 20-40 GB disk space.
   - Configure network as **Internal Network** to isolate lab traffic.
   - Complete Windows installation and update the OS.

3. **Create Kali Linux VM (Attacker)**
   - Download Kali Linux ISO from [kali.org](https://www.kali.org/get-kali/).
   - Allocate resources: 2-4 GB RAM, 20 GB disk space.
   - Configure network on the same **Internal Network** as Windows VM.
   - Install Kali Linux and update all tools.

4. **Configure Networking**
   - Use **Internal Network** mode in VirtualBox for both VMs.
   - This ensures VMs can communicate only with each other, not the outside world.
   - Verify network connectivity by pinging between VMs.

---

## ⚔️ Lab Roles

| VM             | Role       | Purpose                             |
|----------------|------------|-----------------------------------|
| Windows VM     | Victim     | Simulate a target system to test attacks |
| Kali Linux VM  | Attacker   | Use tools to perform penetration testing |

---

