<h1>Bienvenue dans le repo de Leo et Antho</h1>
<p> Pas de Bundle install, ici tu ne trouvera que du Front en statique, tu vas bien t'amuser ! </p>
<p> le kit UI se trouve sur la page KIT_UI_Flatly.html </p>

<h2>1. Introduction</h2>
<p>Hier tu as vu comment faire un kit UI à partir de rien. Tu as réussi à définir un charte graphique, et c'est un bon début pour des sites pas trop moches. Aujourd'hui, nous allons te donner un kit déjà préfait, puis tu vas devoir construire des molécules et organismes à partir de ce kit. L'objectif est de te faire coder les quelques molécules qui vont prendre 80% de ton site, et comme ceci tu auras juste à les insérer pour un front qui déchire.</p>

<h2>2. Le projet</h2>
<p>Pour ce projet, nous allons te demander de partir sur un kit UI préfait. Ceci a deux avantages : </p>

<ul>
	<li>Déjà, tous les atomes sont désignés. Les tables, les forms, les alertes et bien d'autres. Pas d'oubli et tu seras prêt à faire des molécules et organismes au top</li>
	<li>Ensuite, avec un kit UI déjà préfait, la mise en page sera beaucoup plus simple grâce au système de mise en page de Bootstrap</li>
</ul>

<p>Ensuite, tu auras à réaliser les molécules et organismes suivants :</p>

<ul>
	<li>Une navbar</li>
	<li>Un footer</li>
	<li>L'organisme "formulaire d'authentification"</li>
	<li>La bannière</li>
	<li>Plusieurs formats de cartes de présentation
	<ul>
		<li>Puis les organismes qui représentent la listes de ces cartes</li>
	</ul></li>
	<li>La molécule commentaire
	<ul>
		<li>L'organisme "section commentaires"</li>
	</ul></li>
	<li>Une section "présentation ressource" qui sera grossomodo la section qui présente le show de n'importe quelle ressource</li>
	<li>Une section qui présente un élément (à gauche du texte, à droite une image)</li>
	<li>Un organisme de ton choix</li>
</ul>

<p>Pour l'organisation ce sera simple, tu feras un fichier <code>index.html</code> qui va afficher plein de liens pour des pages contenant les molécules et organismes concernés. Ainsi, tu auras des fichiers <code>navbar.html</code>, <code>footer.html</code>, <code>authentification_form.html</code>, <code>banner.html</code>, etc. Le code CSS sera dans un fichier unique <code>style.css</code>, appelé par toutes tes pages.</p>

<p>Enfin, pour ce projet, nous allons te demander de l'imaginer pour ton projet Eventbrite. En effet, demain tu insèreras toutes les molécules dans ton application lorsque nous te montrerons la force de l'atomic design conjugué à Rails.</p>

<h3>2.1. Choix d'un kit UI</h3>
<p>Pour commencer, nous allons te demander de choisir un kit UI qui va bien. Va sur <a href="https://bootswatch.com/" target="_blank">Bootswatch</a>, puis choisis le thème qui t'inspire le plus pour Eventbrite.</p>

<div class="card box-shadow-0 border-info">
  <div class="card-content collapse show">
    <div class="card-body">
      <h4 class="card-title">🚀 ALERTE BONNE ASTUCE</h4>
      <p>Hier, tu as vu comment choisir des couleurs de BG et polices qui vont bien. Les thèmes Bootswatch ne sont au final qu'un fichier CSS que tu as à appeler dans ton application, et tu peux le modifier à ta guise. Par exemple faire un <i>find and replace</i> sur les codes couleur te permettra de changer aisément les couleurs de ton application.</p>
    </div>
  </div>
</div>

<h3>2.2. Conception des molécules et organismes</h3>
<p>Le gros de la journée, tu vas concevoir les molécules et organismes demandés. Pour ceci, tu vas devoir les imaginer pour la partie <i>utilisateurs</i> de l'application Eventbrite (ne prends pas en compte la partie Admin).</p>

<p>On ne recommandera jamais assez, mais la partie <a href="https://getbootstrap.com/docs/4.0/examples/" target="_blank">examples</a> du site de Bootstrap contient un joli nombre de molécules exemples, avec une structure type d'une page html. Enfin, ce n'est jamais simple de devoir concevoir des molécules à partir de son imagination. Ainsi, pour chaque élément demandé, n'hésite pas à aller voir des exemples : les exemples de Bootstrap, ou alors les exemples <a href="https://themes.getbootstrap.com/" target="_blank">des thèmes officiels</a> de Bootstrap. À partir de ces exemples, tu prendras ton préféré, puis tu le dessineras sur un bout de papier, avant de concevoir le CSS de la molécule ou organisme.</p>

<p>L'exercice te demandera principalement de :</p>

<ul>
	<li>Essayer d'imaginer un design de molécule à partir de composants : jouer avec les briques des legos</li>
	<li>Jouer avec du CSS et les classes Bootstrap pour faire de la mise en page</li>
</ul>

<h4>2.2.1. La navbar</h4>
<p>Toute application qui se respecte se doit d'avoir une navbar qui permet de naviguer facilement dans les pages. Cet organisme sera assez simple à réaliser : tu n'as qu'à prendre un des exemples de Bootstrap et l'adapter à l'application Eventbrite !</p>

<h4>2.2.2. Un footer</h4>
<p>Pour cet exemple, tu devras faire un peu de CSS. Réfléchis bien à ce que tu veux mettre dans le footer, prends des exemples, puis designe-le.</p>

<h4>2.2.3. Formulaire d'authentification</h4>
<p>Aller sur un site professionnel et tomber sur <a href="https://i.imgur.com/qU6TAhL.png" target="_blank">cela</a> quand tu veux changer de mot de passe, cela ne fait pas très professionnel. L'avantage est que ce genre de formulaire se ressemble beaucoup : deux-trois champs de formulaire, une checkbox, des liens, un bouton, et hop ! Par exemple, voici deux pages différentes au design très similaire : <a href="https://htmlstream.com/preview/space-v1.2/html/pages/signin-simple.html" target="_blank">page 1</a>, et <a href="https://htmlstream.com/preview/space-v1.2/html/pages/signup-simple.html" target="_blank">page 2</a>.</p>

<p>Imagine un design type pour tous les formulaires d'authentification :</p>

<ul>
	<li>Inscription</li>
	<li>Connexion</li>
	<li>Rentrer son email pour mot de passe oublié</li>
	<li>Changement de mot de passe</li>
</ul>

<p>Fais un design générique qui sera adapté à tous les formulaires.</p>

<h4>2.2.4. Une bannière</h4>
<p>En général, tout site qui se respecte se doit d'avoir au moins deux types de bannière :</p>

<ul>
	<li>Une grosse bannière, que l'on retrouve sur la page d'accueil (<a href="https://htmlstream.com/preview/space-v1.2/html/pages/careers.html" target="_blank">exemple</a>)
	<ul>
		<li>Elle contient une image, un énorme titre, un paragraphe, puis un call to action</li>
	</ul></li>
	<li>Une bannière plus petite, que l'on retrouve sur d'autres pages (<a href="https://htmlstream.com/preview/space-v1.2/html/pages/contacts-agency.html" target="_blank">exemple</a>)
	<ul>
		<li>Elle contient en général une image, puis le titre de la page où nous nous trouvons</li>
	</ul></li>
</ul>

<p>Imagine un design pour les deux types de bannière, puis code-les.</p>

<h4>2.2.5. Les cartes de présentation, molécules et organismes</h4>
<p>Les cartes sont très importantes. Tu en auras besoin pour :</p>

<ul>
	<li>Afficher une liste de carte d'événements</li>
	<li>Afficher la liste des cartes des participants à un événement (des cartes horizontales <a href="https://getbootstrap.com/docs/4.0/examples/offcanvas/" target="_blank">comme celles-ci</a>)</li>
	<li>Afficher une liste de cartes de villes</li>
</ul>

<p>Les cartes dans l'atomic design sont un élément très important, et c'est bien d'avoir plein de genre de cartes. Heuresemment, Bootstrap sont sympas et ont <a href="https://getbootstrap.com/docs/4.0/components/card/" target="_blank">prévu le coup</a>.</p>

<h5>2.2.5.1. Les molécules : cartes</h5>
<p>Construis les trois types de carte pour ce qui a été dit plus haut.</p>

<h5>2.2.5.2. Les organismes : listes de cartes</h5>
<p>Maintenant imagine les organismes qui vont aller avec ces cartes. Nous allons avoir besoin de listes pour les afficher :</p>

<ul>
	<li>Une liste qui affiche plusieurs cartes d'événements (mets-en le nombre que tu veux dans une <code>row</code>), qui sera un des organismes principaux de ta page d'accueil</li>
	<li>Une liste qui affiche plusieurs cartes horizontales d'utilisateurs, qui sera un élément important dans la page qui affiche les participants à un événement</li>
</ul>

<h4>2.2.6. Les commentaires : molécule et organisme</h4>
<p>Imaginons que l'on veuille afficher les commentaires de ton application. Voici comment nous allons procéder :</p>

<ul>
	<li>Il va falloir créer une molécule de commentaire, avec prénom de l'auteur, photo, contenu, et heure de post du commentaire</li>
	<li>Puis nous allons devoir ajouter un <code>textarea</code>, un bouton "commenter", quelques séparateurs, et nous avons un organisme "section de commentaires".</li>
</ul>

<p>Construis la molécule de commentaire, puis constuis l'organisme de la section de commentaires</p>

<h4>2.2.7. Présentation ressource</h4>
<p>Quand tu arrives sur la page d'un événement ou d'un utilisateur, il faut que ce soit affiché joliment. Par exemple, pour le vrai site Eventbrite, <a href="https://www.eventbrite.fr/e/billets-ai-france-summit-2019-55022263070?aff=ehomecard" target="_blank">la page qui affiche les événements</a> est bien organisée :</p>

<ul>
	<li>Tout dans un container</li>
	<li>Une molécule d'une image qui prend 8 colonnes, et une section d'informations importantes qui prend 4 colonnes</li>
	<li>Une molécule avec des icones, puis un bouton</li>
	<li>Une molécule de la description qui prend 8 colonnes et du reste des informations sur les 4 colonnes restantes</li>
	<li>Enfin, quelques icones de réseaux sociaux</li>
</ul>

<p>Si tu arrives à faire cet organisme, il te sera très aisé de le reproduire pour d'autres ressources et d'autres pages show. Designe un organisme passe-partout, puis construis la molécule à partir de cela.</p>

<h4>2.2.8. Présentation d'un élément</h4>
<p>Sur les pages d'accueil, il arrive de présenter des éléments en mode : une photo à droite / gauche, du texte à gauche / droite. Tu peux trouver des exemples <a href="https://themes.getbootstrap.com/preview/?theme_id=5348&show_new=" target="_blank">ici</a>. Designes et construis ces sections.</p>

<h4>2.2.9. Un organisme de ton choix</h4>
<p>Tu as construit plein d'organismes, nous allons te demander de constuire un dernier : celui de ton choix. Réfléchis à l'application Eventbrite, puis essaie de voir une fonctionnalité en front qu'il manquerait. Designe-la, et construis-la.</p>



<h2>3. Rendu attendu</h2>
<p>Nous attendons à ce que tu rendes un dossier contenant toutes les molécules et organismes demandés. Petit bonus si tu arrives à présenter tout cela proprement :</p>

<ul>
	<li>Une page qui présente tout ton kit UI avec seulement les atomes (la page Bootswatch)</li>
	<li>Puis plusieurs pages qui affichent les différentes molécules et organismes que tu as codés</li>
</ul>
