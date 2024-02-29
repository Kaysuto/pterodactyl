
# :bird: Installation de Pterodactyl | Version FR

![Test Panel](https://github.com/pterodactyl-installer/pterodactyl-installer/actions/workflows/panel.yml/badge.svg)
![Test Wings](https://github.com/pterodactyl-installer/pterodactyl-installer/actions/workflows/wings.yml/badge.svg)
![Shellcheck](https://github.com/pterodactyl-installer/pterodactyl-installer/actions/workflows/shellcheck.yml/badge.svg)
[![Discord](https://img.shields.io/discord/682342331206074373?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/EYzUxYd9Pk)

☕ Ces étapes sont une procédure d'installation du panneau de gestion **Pterodactyl**, une solution **open-source** pour héberger des serveurs de jeux en ligne.

♨️ Version des systèmes d'exploitation pris en charge :

| OS     | Version | Supporté     | PHP |
| ---------------- | ------- | ------------------ | ----------- |
| Ubuntu           | 20.04 à 22.04   | :white_check_mark:       | 8.1            |
| Debian           | 10 à 12       | :white_check_mark:         | 8.1            |
| CentOS           | 6 à 8       | :red_circle: \*       |             |
| Rocky Linux      | 8 à 9       | :white_check_mark: | 8.1         |
| AlmaLinux        | 8 à 9       | :white_check_mark: | 8.1         |

`*` Indique un système d'exploitation et une version qui étaient précédemment pris en charge par ce script.

📋 Voici une brève description de chaque étape :

- ⚠️ Mettez à jour et mettez à niveau votre système en exécutant la commande suivante :

```sudo apt update && sudo apt upgrade -y```*
- 🕊️ Installez Pterodactyl en exécutant la commande suivante :

```bash <(curl -s https://pterodactyl-installer.se)```
- ✌️ Choisissez l'option **2** pour installer à la fois le **panel** et le **wings**.
- 💾 Entrez les informations de la base de données que vous souhaitez utiliser. (facultatif)
- 🌍 Sélectionnez le fuseau horaire correspondant à votre région. "**Europe/Paris**"
- 👤 Ajoutez les informations de contact.
- 🌐 Entrez le nom de domaine que vous souhaitez utiliser.
- 🔥 Répondez "**oui**" lorsque vous êtes invité à configurer le pare-feu.
- 🔰 Répondez "**oui**" lorsque vous êtes invité à autoriser HTTPS.
- ⌨️ Procédez à l'installation en appuyant sur "**Entrée**".
- 🔒 Acceptez les **conditions d'utilisation** de Let's Encrypt.
- ❌ **Refusez** la configuration de la base de données.
- 💢 **Refusez** la configuration du pare-feu.
- 💨 **Refusez** une nouvelle configuration HTTPS.
- 🤌 Procédez à l'installation pour **finaliser** l'installation de Pterodactyl.

✅ Maintenant que vous avez suivi ces étapes, vous pouvez maintenant utiliser **Pterodactyl** pour héberger des serveurs de jeux ou autre et gérer leur configuration à partir d'une **interface graphique** conviviale.

🥸 Si vous rencontrez des problèmes lors de l'installation, n'hésitez pas à me contacter ou à rechercher des ressources en ligne pour obtenir de l'aide. 
- [Site web de Pterodactyl](https://pterodactyl.io/)
- [Github du script d'installation](https://github.com/pterodactyl-installer/pterodactyl-installer)
- [Tuto YouTube](https://www.youtube.com/watch?v=E8UJhyUFoHM)
