☕ Ces étapes sont une procédure d'installation du panneau de gestion Pterodactyl, une solution open-source pour héberger des serveurs de jeux en ligne.

♨️ Version des systèmes d'exploitation pris en charge :

| Système d'exploitation     | Version | Supporté     | Version PHP |
| ---------------- | ------- | ------------------ | ----------- |
| Ubuntu           | 14.04   | :red_circle:       |             |
|                  | 16.04   | :red_circle: \*    |             |
|                  | 18.04   | :red_circle: \*    | 8.1         |
|                  | 20.04   | :white_check_mark: | 8.1         |
|                  | 22.04   | :white_check_mark: | 8.1         |
| Debian           | 8       | :red_circle: \*    |             |
|                  | 9       | :red_circle: \*    |             |
|                  | 10      | :white_check_mark: | 8.1         |
|                  | 11      | :white_check_mark: | 8.1         |
|                  | 12      | :white_check_mark: | 8.1         |
| CentOS           | 6       | :red_circle:       |             |
|                  | 7       | :red_circle: \*    |             |
|                  | 8       | :red_circle: \*    |             |
| Rocky Linux      | 8       | :white_check_mark: | 8.1         |
|                  | 9       | :white_check_mark: | 8.1         |
| AlmaLinux        | 8       | :white_check_mark: | 8.1         |
|                  | 9       | :white_check_mark: | 8.1         |

_\* Indique un système d'exploitation et une version qui étaient précédemment pris en charge par ce script.

📋 Voici une brève description de chaque étape :

⚠️ Mettez à jour et mettez à niveau votre système en exécutant la commande suivante :
```sudo apt update && sudo apt upgrade -y```*
🕊️ Installez Pterodactyl en exécutant la commande suivante :
```bash <(curl -s https://pterodactyl-installer.se)```
✌️ Choisissez l'option **2** pour installer à la fois le **panel** et le **wings**.
💾 Entrez les informations de la base de données que vous souhaitez utiliser. (facultatif)
🌍 Sélectionnez le fuseau horaire correspondant à votre région. "**Europe/Paris**"
👤 Ajoutez les informations de contact.
🌐 Entrez le nom de domaine que vous souhaitez utiliser.
🔥 Répondez "**oui**" lorsque vous êtes invité à configurer le pare-feu.
🔰 Répondez "**oui**" lorsque vous êtes invité à autoriser HTTPS.
⌨️ Procédez à l'installation en appuyant sur "**Entrée**".
🔒 Acceptez les **conditions d'utilisation** de Let's Encrypt.
❌ **Refusez** la configuration de la base de données.
💢 **Refusez** la configuration du pare-feu.
💨 **Refusez** une nouvelle configuration HTTPS.
🤌 Procédez à l'installation pour **finaliser** l'installation de Pterodactyl.

✅ Maintenant que vous avez suivi ces étapes, vous pouvez maintenant utiliser Pterodactyl pour héberger des serveurs de jeux ou autre et gérer leur configuration à partir d'une interface graphique conviviale.

🥸 Si vous rencontrez des problèmes lors de l'installation, n'hésitez pas à rechercher des ressources en ligne pour obtenir de l'aide ou à contacter un expert pour vous assister.
([Pterodactyl](https://pterodactyl.io/) - [GitHub](https://github.com/pterodactyl-installer/pterodactyl-installer) - [Youtube](https://www.youtube.com/watch?v=E8UJhyUFoHM))
