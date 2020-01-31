# Tech-reportsportaal Data Studio

Urban Analytics is de oprichter en ontwikkelaar van de Data Studio, een omgeving waar onderzoekers, leraren en studenten samenwerken met bedrijven en overheden. Dit gebeurt door het activeren van geïnterreseerden, door data en kennis samen te brengen, door middel van meet-ups, maar ook door het samen werken tijdens project in het veld van data science.

Het publiceren van tech reports is één van onze methoden om te verbinden met het publiek door ons onderzoek te delen met bedrijven en overheden. Deze rapporten gaan over gerichtte metingen die wij uitvoeren tot aan data analyses, maar ook data visualisaties en het ontwikkelen van software applicaties. 

## Hoe kan je bijdragen?
Er zijn verschillende manieren waarop kan worden bijgedragen aan de website. Alles gebeurt via Github, maar het kan ook handig zijn om RStudio te hebben. Via RStudio kan je namelijk eenvoudig tech reports maken met behulp van R-Markdown.

Als je fouten ziet in een tech report zou je dat door middel van een pull request met veranderingen kunnen doorgeven aan de beheerders van deze repository.

In de toekomst zal er ook een beschrijving worden gepubliceerd in de vorm van een tech report die zal uitleggen hoe je je eigen tech report kunt schrijven!

## Directories
.
├── R                       # R scripts die uitgevoerd worden voor het renderen
├── config                  # Configuratie bestanden Academic theme
├── content                 # Verschillende formats om content te weergeven 
├── data                    # Hierin staan onze aanpassingen aan de thema
├── layouts                 # Hierin staan aangepaste partials voor de thema
├── resources               # Gegenereerde bestaanden door HUGO
├── static                  # Static bestanden voor de websites, zoals plaatjes
├── themes                  # Verschillende thema's die gekozen kunenn worden
├── LICENSE.md              # License voor het gebruiken van deze code
├── README.md               # Beschrijving van de repository
├── config.toml             # Config bestand voor website
├── netlify.toml            # Config bestand voor CI op Netlify
├── update_academic.sh      # Update bestand academic thema
└── view.sh                 # Config bestand voor netlify


## Technologieen
- [Academic Theme](https://themes.gohugo.io/academic/) - Thema die in gebruik wordt genomen in Hugo
- [Blogdown](https://github.com/rstudio/blogdown) - R package voor het genereren van websites
- [Hugo](https://github.com/gohugoio/hugo) - HUGO is de website rederer gebasseerd op GO
