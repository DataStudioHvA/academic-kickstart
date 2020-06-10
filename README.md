# Tech-reportsportaal Data Studio

Urban Analytics is de oprichter en ontwikkelaar van de Data Studio, een omgeving waar onderzoekers, leraren en studenten samenwerken met bedrijven en overheden. Dit gebeurt door het activeren van geïnteresseerden, door data en kennis samen te brengen, door middel van meet-ups, maar ook door het samen werken tijdens project in het veld van data science.

Het publiceren van tech reports is één van onze methoden om te verbinden met het publiek door ons onderzoek te delen met bedrijven en overheden. Deze rapporten gaan over gerichtte metingen die wij uitvoeren tot aan data analyses, maar ook data visualisaties en het ontwikkelen van software applicaties. 

## Hoe kan je bijdragen?
Er zijn verschillende manieren waarop kan worden bijgedragen aan de website. Alles gebeurt via Github, maar het kan ook handig zijn om RStudio te hebben. Via RStudio kan je namelijk eenvoudig tech reports maken met behulp van R-Markdown.

Als je fouten ziet in een tech report zou je dat door middel van een pull request met veranderingen kunnen doorgeven aan de beheerders van deze repository.

In de toekomst zal er ook een beschrijving worden gepubliceerd in de vorm van een tech report die zal uitleggen hoe je je eigen tech report kunt schrijven!

[Zie hier hoe je tech reports kan toevoegen!](https://github.com/DataStudioHvA/blog_tech_reports/tree/master/content/post)

## Folder structuur
    ├─ .forestry          # CMS (geimplementeerd, maar niet verder getest)
    ├─ .github            # Github templates e.g. issue_template
    ├─ R                  # Script die worden gerund voor renderen van de website
    │  └─ build.R         # Build script, roept submodule van git aan
    ├─ config             # Configuratie Academic thema
    ├─ content            # Content folder voor verschillende doeleinden
    │  ├─ authors
    │  ├─ courses
    │  ├─ home
    │  ├─ post            # Hierin komen de tech reports
    │  ├─ project
    │  ├─ publication
    │  ├─ slides
    │  ├─ talk
    ├─ data               # Overschreven theme aanpassingen voor de website 
    ├─ layouts            # Overschreven HTML partials voor de website
    ├─ resources          # Resources folder voor gebruikte tools (HUGO)
    ├─ static             # Static bestanden voor website
    ├─ themes             # Folder voor thema's
    ├─ .editorconfig      # VS code instellingen
    ├─ .gitignore         # Ignore files
    ├─ .gitmodules        # Submodules
    ├─ LICENSE.md         # Licensing
    ├─ README.md          # Repository uitleg
    ├─ config.toml        # Blogdown instellingen
    ├─ netlify.toml       # Netlify instellingen
    ├─ update_academic.sh # Update academic theme
    └─ view.sh            # Update academic theme


## Technologieen
- [Academic Theme](https://themes.gohugo.io/academic/) - Thema die in gebruik wordt genomen in Hugo
- [Blogdown](https://github.com/rstudio/blogdown) - R package voor het genereren van websites
- [Hugo](https://github.com/gohugoio/hugo) - HUGO is de website rederer gebasseerd op GO
