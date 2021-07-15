# Twitch Extractor

### Application

L'application <a href="https://twitchextractor.herokuapp.com/" target="_blank">Twitch Extractor</a> est accessible en ligne. 

### Pré-requis
<p>Il est nécessaire de déclarer une application Twitch et de récupérer des identifiants API depuis la <a href="https://dev.twitch.tv/console/apps" target="_blank">console Developers</a>. </p>

### Description
<p>Cette application permet d'analyser les vidéos archivées sur une chaine Twitch. L'application se connecte à l'API Twitch, récupère les informations générales de la chaine ainsi que les métadonnées des archives vidéos. Un rapport est généré présentant les principales métriques d'activité de la chaine :
<ul>
  <li>Key metrics : total de vidéos publiées, vues cumulées, total d'heures cumulées de contenus pour l'ensemble des vidéos archivées</li>
  <li>KPIs sur les 12 derniers mois d'activité</li>
  <li>Classement des vidéos les plus vues</li>
  <li>Tableau de l'ensemble des métadonnées de vidéos capturées, téléchargeable au format csv</li>
</ul></p>

### Notes
<p>Cette application capture uniquement les vidéos archivées sur la chaine. Il est nécessaire de prendre cela en compte lors de l'interprétation des données : 
<ul>
  <li>L'application ne capture pas les streams lives, ni les clips de la chaine.</li>
  <li>Il peut exister un différentiel important entre le nombre de vues cumulées de la chaine (métrique incluant la performance des streams live) et le total de vues cumulées des vidéos archivées</li>
  <li>Twitch limite la durée de stockage des vidéos selon le type de chaine</li>
  <li>Les streams live ne sont pas systématiquement archivées sur une chaine, le streameur sélectionne les vidéos à archiver</li>
  <li>Twitch peut supprimer des vidéos qui enfreignent des copyrights</li>
</ul></p>
