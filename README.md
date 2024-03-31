# HTML - Exercice CV

## Instructions

Sans utiliser de balises div et span, écrivez le code html constitutif d'une page CV.
Vous utiliserez à minima les balises html, head, body, title, meta, header, main, footer, form, label, input, button, img, ul, li, p, h1, h2,..., section, nav, avec les attributs associés et dans le respect du validateur du w3c (<https://validator.w3.org/>) et des règles du rgaa (<https://disic.github.io/guide-integrateur/> ou <https://accessibilite.numerique.gouv.fr/>).

## Comment j'ai procédé ?

### Content

J'ai découpé mon CV en 3 parties:

- Home: l'accueil avec mes coordonnées

- Education: Mes formations et diplômes

- Experiences: Mes expériences professionnelles

### Template

- Header: titre de la page

- Main: Le contenu principal de la page à laquelle j'imbrique une ou des sections

- Footer: Le pied de la page à laquelle j'imbrique ma navigation à travers la balise nav contenant elle-même un ul avec des li pour une liste à puces de nos liens

### Home

Je trouvais que pour imbriquer le formulaire dans un CV, le classique username et password ne serait pas approprié dans notre cas. Je suis donc parti sur une évaluation de notes.

### Education & Experiences

Je les ai filtré de cette manière afin de pouvoir imbriqué la balise article pour chaque formation et expérience ajoutée.
J'ai décidé d'utiliser des images ainsi que des liens externes pour mettre l'utilisateur dans le contexte.
