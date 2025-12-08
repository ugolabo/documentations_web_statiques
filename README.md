# Documentations avec sites web statiques

Une recension d'outils pour construire des documentations web mises à jour en continu pour :

- le développement et la gestion de projets,
- les documentations techniques et les banques de connaissances,
- le contenu de coaching, d'enseignement de logiciels, d'insertion d'employé,
- la production de rapport et de tableaux de bord
- et bien plus.

## Générateurs de sites web statiques

Au-delà de l'utilisation des fonctionnalités de GitHub Pages, par exemple, il existe une bonne quantité de <a href="https://jamstack.org/generators/" target="_blank">générateurs</a> en différents langages et pour différents usages.

<img src="img/documentations_web_statiques.png" alt="" width="500px" >

Avec la majorité des générateurs, la création du contenu (texte, images, liens, etc.) est faite en Markdown; un langage typographique qui simplifie le langage HTML. Le générateur sert à émuler et à construire le site en local.

Certains générateurs offrent des thèmes alors que d'autres nécessitent l'ajout d'un thème avec un template. Selon le générateur, la diversité des thèmes peut ou non couvrir un vaste évantail de besoins qui dépassent les documentations en ligne (blogue, CV en ligne, portfolio, etc.). Il reste que tout se personnalise modifiant le HTML et en injectant plus de CSS et de JavaScript.

Le résultat peut ensuite être hébergé en ligne avec différents services dont GitHub, GitLab, Atlassian Bitbucket, des fournisseurs cloud, avec ou sans nom de domaine. Certains générateurs offrent l'option de publier en divers formats : HTML, PDF, ePub, Word.

Voici des exemples utilisés à de nombreuses occasions :

- **Read the Docs** avec un thème fixe, peu de personnalisation, mais une standardisation qui offre de la stabilité.
    - <a href="https://docs.readthedocs.com/platform/stable/index.html" target="_blank">Exemple de leur site</a>.
- **GitBook** avec ses thèmes standards et plus de personnalisation.
    - <a href="https://gitbook.com/docs/" target="_blank">Exemple de leur site</a>.
- **MkDocs** avec ses thèmes standards dont celui de **leur site** et ses thèmes indépendants dont <a href="https://squidfunk.github.io/mkdocs-material/" target="_blank">Material</a>. Deux exemples avec le thème Material :
    - https://ugolab.gitlab.io/formation/
    - https://ugolab.gitlab.io/projetNF/
- **Hugo** avec une vaste collection de <a href="https://themes.gohugo.io/" target="_blank">thèmes</a>. Avec Hugo, il faut utiliser un service comme Netlify pour construire et héberger le site avec les fichiers d'un dépôt de données (le dépôt privé est sur Bitbucket) :
    - https://ugofolio.netlify.app/portfolio/
- **Quarto** pour créer des rapports, des articles, des dashboards, des sites web et des blogs.

## Générateurs de documentation de programmes

Doxygen est spécialisé dans l'analyse du code source d'un programme pour en extraire les informations pertinentes (fonctions, classes, variables, structures, fichiers, etc.) et les transformer en une documentation structurée. C'est plus automatisé qu'avec les générateurs de sites web qui permettent de documenter n'importe quoi. Doxygen utilise ce qu'on appelle la documentation intégrée (source-level documentation ou docstrings) pour plusieurs langages : C/C++, C#, Java, PHP, Python, JavaScript/TypeScript et bien d'autres.

Doxygen remplace d'autres solutions spécialisées :

- Sphinx et pydoc, spécialisés en projets Python.
- Javadoc, spécialisé en projets Java.
- jsdoc, spécialisé en projets JavaScript.

D'autres générateurs sont hyper-spécialisés dans des projets d'API :

- OpenAPI.
- Postman.
