---
title: Suche
description: Durchsuche Inhalte der We Play Webseite
keywords: [Suche, Seitensuche]
schemaOrg: SearchResultsPage
menu: footer
customJs:
  - ts/suche.ts
customCss:
  - scss/suche.scss
---

<form itemprop="potentialAction" itemscope itemtype="http://schema.org/SearchAction">
  <meta itemprop="target" content="{{.Site.BaseURL}}/search.html?q={query}" />
  <input class="wp-search-field" itemprop="query-input" placeholder="Suche..." type="search" name="query" />
</form>

<ol class="results">
</ol>
