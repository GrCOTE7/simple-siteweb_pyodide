# 📘 Toutes les Admonitions MkDocs Material

:point_right: Ici, avec !!! mais ??? et ???+ possibles

!!! note "Remarque générale"
    Cette boîte sert à ajouter une information complémentaire sans importance critique.

!!! abstract "Résumé ou URL"
    Présente une synthèse ou un aperçu du contenu.

!!! info "Information"
    Fournit une donnée neutre ou contextuelle.

!!! tip "Astuce"
    Donne un conseil ou une bonne pratique.

!!! success "Succès"
    Indique une action réussie ou validée.

!!! question "Question"
    Pose une interrogation ou invite à réfléchir.

!!! warning "Avertissement"
    Signale un risque ou une précaution à prendre.

!!! failure "Échec"
    Informe d’une erreur ou d’un résultat négatif.

!!! danger "Danger"
    Alerte sur un problème critique ou une menace.

!!! bug "Bug"
    Mentionne un dysfonctionnement ou une anomalie.

!!! example "Exemple"
    Illustre un concept ou une méthode.

!!! quote "Citation"
    Met en avant une parole ou un extrait inspirant.

👉 [Un lien d'une ancre d'un doc target=_blank](/simple-siteweb_pyodide/chapitre_plusieurs_pages/chapitre2_page2/#ii-paragraphe-2){:target="_blank" }

👉 [Un lien externe target=_blank](http://github.com/PyMoX-fr){:target="_blank" }

![paysage](assets/images/logo_aeif_300.png){ width=5%;}
![paysage](assets/images/logo_aeif_300.png){ width=10%;}
![paysage](assets/images/logo_aeif_300.png){ width=15%;}


👉 ![paysage](assets/images/logo_aeif_300.png){ width=20%; : .center }
Le texte se place **en dessous** de l'image centrée.

![paysage](assets/images/logo_aeif_300.png){ width=10%; align=right }

👉 Le texte se place **à gauche** de mon image placée à droite.

👉 [Référence <span style="font-size:14px;">:arrow_upper_right:</span>](https://docs.forge.apps.education.fr/modeles/tutoriels/tutoriel-site-simple/02_basique/2_page_basique){.md-button target="_blank" rel="noopener"}

Nous allons utiliser la touche <kbd>2</kbd>

Dans la phrase "Je lis un tutoriel." Le verbe "lis" est au $\hspace{7em}$ de l'indicatif.

---

=== "Panneau 1"
        Ici du texte concernant ce panneau 1

        Il peut prendre plusieurs lignes

    === "Panneau 1"
        Ici du texte concernant ce panneau 1

    === "Panneau 2"
        Ici du texte concernant ce panneau 2

        Un panneau peut prendre plusieurs lignes

---

```mermaid
    %%{init: {'themeVariables': {'fontFamily': 'monospace'}}}%%
    flowchart TB
        n0(15) --> n1(6)
        n1 --> n3(1)
        n1 --> n4(10)
        n0 --> n2(30)
        n2 --> n8[Null]
        n2 --> n5(18)
        n5 --> n6(16)
        n5 --> n7(25)
```

```mermaid
    %%{init: {'themeVariables': {'fontFamily': 'monospace'}}}%%
    flowchart TB
        n0(15) --> n1(6)
        n1 --> n3(1)
        n1 --> n4( )
        n0 --> n2(30)
        n2 --> n8( )
        n2 --> n5(18)
        n5 --> n6(16)
        n5 --> n7(25)
        linkStyle 2 stroke-width:0px;
        linkStyle 4 stroke-width:0px;
        style n4 opacity:0;
        style n8 opacity:0;
```


[Lien vers différentes options de nœuds et flèches](https://coda.io/@leandro-zubrezki/diagrams-and-visualizations-using-mermaid/flowcharts-3){ .md-button target="_blank" rel="noopener" }


[lien vers la documentation mermaid - essais en ligne de mermaid](https://www.mermaidchart.com/play){ .md-button target="_blank" rel="noopener" }

```mermaid
flowchart TD
    A[Christmas] -->|Get money| B(Go shopping)
    B --> C{Let me think}
    C -->|One| D[Laptop]
    C -->|Two| E[iPhone]
    C -->|Three| F[:car: Car]
```
