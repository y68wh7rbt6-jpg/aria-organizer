# ARIA — première base PWA

Cette version est un prototype web installable (PWA) pour iPhone.

## Fonctionnalités incluses
- Accueil avec priorités et prochains événements
- Agenda Jour / Semaine / Mois / Année
- Ajout, modification et suppression d'événements
- To-do list avec catégories, cases à cocher et suppression
- Planification d'une tâche dans l'agenda
- Progression globale et par univers en pourcentage
- Sauvegarde locale dans le navigateur (`localStorage`)
- Cache hors-ligne de l'interface via service worker

## Installer sur iPhone
Une PWA doit être publiée sur une adresse HTTPS pour être installée.
1. Héberger le contenu de ce dossier sur un hébergement statique HTTPS (par exemple GitHub Pages, Netlify ou un hébergement web personnel).
2. Ouvrir l'adresse publiée dans Safari sur l'iPhone.
3. Toucher Partager, puis « Sur l'écran d'accueil », puis Ajouter.

## Important
- Les données restent sur l'appareil et dans le navigateur utilisé. Elles ne sont pas synchronisées entre plusieurs appareils.
- Fais régulièrement une sauvegarde du navigateur / appareil. Une fonction d'export/import et une synchronisation sécurisée seront à prévoir avant un usage important.
- L'agenda ne se connecte pas encore à Apple Calendar et n'envoie pas de notifications.
- Les horaires professionnels affichés dans les exemples sont des blocs de départ modifiables, pas des rendez-vous confirmés.
- Le service worker fonctionne uniquement depuis HTTPS ou localhost.
