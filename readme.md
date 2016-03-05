# Web Praha

Nový web Pirátů v Praze. Web je zamýšlen pro celé krajské sdružení - zastupitele (magistrát i mč), veřejnost, členy i pracovníky. Náhled je k dispozici na: http://pirati-cz.github.io/webpraha2/

Toto readme je čistě technické a metodické.

## Adresařova struktura

```
├── _config.yml       - konfigurační soubor
├── _data             - yaml soubory nahrazující DB
├── _includes         - html snippety (hlavička, patička, ...)
│   ├── footer.html   -- patička stránky
│   ├── header.html   -- hlavička stránky
│   └── head.html     -- meta hlavička stránky
├── _layouts          - kompletní šablony stránek
├── _people           - vlastní kolekce obsahující stránky jednotlivých osob
├── _posts            - příspěvky pro blog v markdownu
├── _sass             - sass styly (konvertované do css)
├── _site             - vygenerovaná stránka
├── assets            - přílohy (obrázky, pdf etc.)
│   └── img           
├── blog              - složka blog
│   └── index.html    -- Stránka /blog
└── index.html        - úvodní stránka
```

## Náhled a kompilace

Stránka je k vidění na `http://pirati-cz.github.io/webpraha2/`,
lokálně je třeba kompilovat: `jekyll serve --baseurl ''`

## Standardizace tagů

Městské části: praha-1, praha-2, ..., praha-10, ..., praha-22, praha-Běchovice, ...

Praha jako celek: Praha, ZHMP

## Použité technologie

- [CSS / JS frontend Foundation 6](http://foundation.zurb.com/), [dokumentace](http://foundation.zurb.com/sites/docs/)
- [CSS template](http://foundation.zurb.com/templates-previews-sites-f6/news-magazine.html)
- integrace soc. sití
  - [Integrace FB](https://365tipu.wordpress.com/2015/07/04/tip185-co-je-to-open-graph-a-proc-je-potreba-aby-designeri-webu-vedeli-o-co-jde/)
  - [Ladění FB](https://365tipu.wordpress.com/2015/04/13/tip103-co-delat-kdyz-facebook-odmita-vlozit-odkaz-na-web/)
- [Disqus a Google analytics, Twitter light share](http://joshualande.com/jekyll-github-pages-poole)
- [Responsibilita](http://design.google.com/resizer/)
