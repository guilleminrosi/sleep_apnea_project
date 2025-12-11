<h1>Analyse de données liées au sommeil et estimation de score de risque d'apnée obstructive du sommeil par modèle de machine learning</h1>

<h2>Objectif du projet</h2>
<p>L’objectif de ce projet est d’analyser un ensemble de données synthétiques provenant de montres connectées, afin d’étudier différents paramètres liés au sommeil et plus précisément à l’apnée du sommeil.
<p>Plus précisément, nous cherchons à comprendre comment ces montres connectées calculent un score de « risque d’apnée du sommeil » et quels facteurs influencent ce score.</p>
<p>Pour cela, nous avons :
  <ul>
    <li>exploré les relations entre les variables physiologiques et comportementales ;</li>
    <li>cherché à identifier les facteurs les plus impactants ;</li>
    <li>comparé nos observations à des sources médicales et scientifiques ;</li>
    <li>développé un modèle de Machine Learning permettant de prédire ce score ;</li>
    </ul>
</p>

<h2>Intérêt</h2>
<p>Ce projet nous permet de mieux comprendre le fonctionnement des montres connectées, ainsi que l’algorithme derrière l’estimation du score de « risque d’apnée du sommeil ».</p>
<p>L’apnée du sommeil est un trouble fréquent (30% des personnes de plus de 65 ans seraient impactées), et ce projet peut potentiellement permettre de mettre en avant le « score de risque d’apnée du sommeil » affiché par les montres connectées, et sensibiliser davantage les personnes à ce phénomène.
Nous avons construit un modèle prédictif basé sur les variables identifiées comme pertinentes, nous permettant de prédire le score de « risque d’apnée du sommeil » affiché par les montres connectées selon les informations récoltées.</p>

<h2>Outils utilisés pour l’analyse</h2>
<h3>Kaggle</h3>
<p>L’ensemble de données utilisé provient du site Kaggle, il s’agit d’un ensemble de données synthétiques mais réalistes sur le suivi du sommeil, généré pour aider les étudiants, les chercheurs, les Data Scientists et les ingénieurs en IA autour de l’analyse du sommeil.</p>
<h3>Google Colab - Python</h3>
<p>Afin de mener à bien notre projet, nous avons majoritairement utilisé du Python sur Google Colab. Cet outil nous a permis une exploration de grande envergure sur l’ensemble de données, ainsi qu’un nettoyage efficace de l’ensemble de données. Nous avons également fait une recherche approfondie sur les corrélations pouvant exister pour le score d’apnée du sommeil. Enfin nous avons fait des tests de Machine Learning afin de tester et vérifier nos corrélations.</p>
<h3>BigQuery</h3>
<p>Nous avons utilisé BigQuery afin de stocker notre ensemble de données dans un outil accessible à tous, et sur lequel il est facile d’ajouter/retirer des colonnes dans nos données. Quelques requêtes SQL nous ont permis de nettoyer notre base de données en conséquence.</p>
<h3>Looker Studio</h3>
<p>Enfin nous avons utilisé Looker Studio pour organiser une présentation à la fois visuelle et descriptive, visant à rendre plus claire la relation entre le score de risque d’apnée et les autres variables suivies par les montres connectées.</p>

<h2>Sources</h2>
  <ul>
    <li>Base de données utilisée : </li>
      <ul>
        <li>kaggle.com</li>
      </ul>
    <li>Articles médicaux/chercheurs dans le domaine du sommeil et de l’apnée :</li>
      <ul>
        <li>amelie.fr</li>
        <li>pubmed.ncbi.nlm.nih.gov</li>
        <li>jtsm.org</li>
        <li>vidal.fr</li>
        <li>frontiersin.org</li>
        <li>Inserm.fr</li>
        <li>Info Somnolence</li>
        <li>Fréquence Médicale</li>
        <li>Vidal</li>
      </ul>
  </ul>

<h2>Contributeurs</h2>
<p>Les personnes ayant contribuées à ce projet :</p>
  <ul>
    <li>Guillemin Rosi</li>
    <li>Thomas Van Den Broeck</li>
    <li>Charles Silvestre</li>
    <li>Lena Thevenet</li>
  </ul>
