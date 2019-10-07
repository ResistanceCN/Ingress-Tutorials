<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Example](#example)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Example

This example project contains a configuration for the German language. All
footer and search labels (or placeholders), as well as link titles have been
translated to German. Use this example as a starting point for a project with
another language than English.

The translations can be changed in `theme/partials/language.html`:

``` jinja
{% macro t(key) %}{{ {
  "language": "de",
  "edit.link.title": "Seite editieren",
  "footer.previous": "Vorherige Seite",
  "footer.next": "Nächste Seite",
  "meta.comments": "Kommentare",
  "meta.source": "Quellcode",
  "search.languages": "de",
  "search.placeholder": "Suche",
  "search.result.placeholder": "Suchbegriff eingeben",
  "search.result.none": "Keine Suchergebnisse",
  "search.result.one": "1 Suchergebnis",
  "search.result.other": "# Suchergebnisse",
  "source.link.title": "Quellcode",
  "toc.title": "Inhaltsverzeichnis"
}[key] }}{% endmacro %}
```
