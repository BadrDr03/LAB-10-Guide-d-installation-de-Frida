# LAB-10-Guide-d-installation-de-Frida

### 🛠️ Étape 1 : Installation du client Frida sur Kali Linux

Dans cette étape, nous avons configuré l'environnement de travail sur notre machine d'analyse (Kali Linux).

**Actions effectuées :**
1. Mise à jour des paquets système et installation de `pip3`.
2. Installation de `frida` et `frida-tools` en utilisant le gestionnaire de paquets Python.
3. Utilisation du flag `--break-system-packages` pour contourner les restrictions PEP 668 de la distribution.

**Commandes clés :**
```bash
sudo apt update && sudo apt install -y python3-pip
pip install --upgrade frida frida-tools --break-system-packages

```

![Import OVA](https://github.com/user-attachments/assets/74d1f8cf-a396-45d2-9470-8831e2fd1564)

![Import OVA](https://github.com/user-attachments/assets/ad74caf5-82f6-4d6d-a178-d1b379caee19)

---

