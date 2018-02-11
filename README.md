# Web táborských Pirátů

Pro psaní článků je třeba umět [markdown](https://cs.wikipedia.org/wiki/Markdown).
Web má admin rozhraní pro úpravu článků.
Pro úpravu ostatního je potřeba umět [Jekyll](http://jekyllrb.com/).
A je třeba seznámit se alespoň se základy gitu.

### Lokální test (pro experty)

V adresaři s repozitářem spustíme příkaz:
`bundle exec jekyll serve --incremental --baseurl '' `
což spustí server s webem a my si ho můžeme prohlédnout.

#### Update zavislosti

```
git submodule update --remote --merge
```

#### init zavislosti

```
git submodule add https://github.com/pirati-web/layouts _layouts
git submodule add https://github.com/pirati-web/partials _includes/shared/
git submodule init
```
