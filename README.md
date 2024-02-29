
# :bird: Installation de Pterodactyl | Version FR

![Test Panel](https://github.com/pterodactyl-installer/pterodactyl-installer/actions/workflows/panel.yml/badge.svg)
![Test Wings](https://github.com/pterodactyl-installer/pterodactyl-installer/actions/workflows/wings.yml/badge.svg)
![Shellcheck](https://github.com/pterodactyl-installer/pterodactyl-installer/actions/workflows/shellcheck.yml/badge.svg)
[![License: GPL v3](https://img.shields.io/github/license/pterodactyl-installer/pterodactyl-installer)](LICENSE)
[![Discord](https://img.shields.io/discord/682342331206074373?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://pterodactyl-installer.se/discord)
[![made-with-bash](https://img.shields.io/badge/-Made%20with%20Bash-1f425f.svg?logo=image%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAyZpVFh0WE1MOmNvbS5hZG9iZS54bXAAAAAAADw%2FeHBhY2tldCBiZWdpbj0i77u%2FIiBpZD0iVzVNME1wQ2VoaUh6cmVTek5UY3prYzlkIj8%2BIDx4OnhtcG1ldGEgeG1sbnM6eD0iYWRvYmU6bnM6bWV0YS8iIHg6eG1wdGs9IkFkb2JlIFhNUCBDb3JlIDUuNi1jMTExIDc5LjE1ODMyNSwgMjAxNS8wOS8xMC0wMToxMDoyMCAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvIiB4bWxuczp4bXBNTT0iaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wL21tLyIgeG1sbnM6c3RSZWY9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9zVHlwZS9SZXNvdXJjZVJlZiMiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIENDIDIwMTUgKFdpbmRvd3MpIiB4bXBNTTpJbnN0YW5jZUlEPSJ4bXAuaWlkOkE3MDg2QTAyQUZCMzExRTVBMkQxRDMzMkJDMUQ4RDk3IiB4bXBNTTpEb2N1bWVudElEPSJ4bXAuZGlkOkE3MDg2QTAzQUZCMzExRTVBMkQxRDMzMkJDMUQ4RDk3Ij4gPHhtcE1NOkRlcml2ZWRGcm9tIHN0UmVmOmluc3RhbmNlSUQ9InhtcC5paWQ6QTcwODZBMDBBRkIzMTFFNUEyRDFEMzMyQkMxRDhEOTciIHN0UmVmOmRvY3VtZW50SUQ9InhtcC5kaWQ6QTcwODZBMDFBRkIzMTFFNUEyRDFEMzMyQkMxRDhEOTciLz4gPC9yZGY6RGVzY3JpcHRpb24%2BIDwvcmRmOlJERj4gPC94OnhtcG1ldGE%2BIDw%2FeHBhY2tldCBlbmQ9InIiPz6lm45hAAADkklEQVR42qyVa0yTVxzGn7d9Wy03MS2ii8s%2BeokYNQSVhCzOjXZOFNF4jx%2BMRmPUMEUEqVG36jo2thizLSQSMd4N8ZoQ8RKjJtooaCpK6ZoCtRXKpRempbTv5ey83bhkAUphz8fznvP8znn%2B%2F3NeEEJgNBoRRSmz0ub%2FfuxEacBg%2FDmYtiCjgo5NG2mBXq%2BH5I1ogMRk9Zbd%2BQU2e1ML6VPLOyf5tvBQ8yT1lG10imxsABm7SLs898GTpyYynEzP60hO3trHDKvMigUwdeaceacqzp7nOI4n0SSIIjl36ao4Z356OV07fSQAk6xJ3XGg%2BLCr1d1OYlVHp4eUHPnerU79ZA%2F1kuv1JQMAg%2BE4O2P23EumF3VkvHprsZKMzKwbRUXFEyTvSIEmTVbrysp%2BWr8wfQHGK6WChVa3bKUmdWou%2BjpArdGkzZ41c1zG%2Fu5uGH4swzd561F%2BuhIT4%2BLnSuPsv9%2BJKIpjNr9dXYOyk7%2FBZrcjIT4eCnoKgedJP4BEqhG77E3NKP31FO7cfQA5K0dSYuLgz2TwCWJSOBzG6crzKK%2BohNfni%2Bx6OMUMMNe%2Fgf7ocbw0v0acKg6J8Ql0q%2BT%2FAXR5PNi5dz9c71upuQqCKFAD%2BYhrZLEAmpodaHO3Qy6TI3NhBpbrshGtOWKOSMYwYGQM8nJzoFJNxP2HjyIQho4PewK6hBktoDcUwtIln4PjOWzflQ%2Be5yl0yCCYgYikTclGlxadio%2BBQCSiW1UXoVGrKYwH4RgMrjU1HAB4vR6LzWYfFUCKxfS8Ftk5qxHoCUQAUkRJaSEokkV6Y%2F%2BJUOC4hn6A39NVXVBYeNP8piH6HeA4fPbpdBQV5KOx0QaL1YppX3Jgk0TwH2Vg6S3u%2BdB91%2B%2FpuNYPYFl5uP5V7ZqvsrX7jxqMXR6ff3gCQSTzFI0a1TX3wIs8ul%2Bq4HuWAAiM39vhOuR1O1fQ2gT%2F26Z8Z5vrl2OHi9OXZn995nLV9aFfS6UC9JeJPfuK0NBohWpCHMSAAsFe74WWP%2BvT25wtP9Bpob6uGqqyDnOtaeumjRu%2ByFu36VntK%2FPA5umTJeUtPWZSU9BCgud661odVp3DZtkc7AnYR33RRC708PrVi1larW7XwZIjLnd7R6SgSqWSNjU1B3F72pz5TZbXmX5vV81Yb7Lg7XT%2FUXriu8XLVqw6c6XqWnBKiiYU%2BMt3wWF7u7i91XlSEITwSAZ%2FCzAAHsJVbwXYFFEAAAAASUVORK5CYII%3D)](https://www.gnu.org/software/bash/)

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
