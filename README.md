# Scribe : enregistreur

Page d'amorce de l'enregistreur de Scribe, l'app interne de notes de réunion de C'Evidentia. Elle est servie par GitHub Pages (`https://pierrebillet.github.io/scribe/`) parce que les pages n8n, en bac à sable, n'ont pas accès au micro.

La page charge la fenêtre d'enregistrement depuis le workflow n8n de Scribe. Elle ne contient aucun secret : le jeton de session vient de la page Scribe, après connexion aux outils internes.

`index.html` est généré par le builder de Scribe : ne pas le modifier à la main.
