+++
title = 'Project 5'
date = 2023-04-23T19:36:23-07:00
draft = false
relPermalinkOverride = '/docs/project-5/price_elasticity.html'
+++

**This page is still in work**

{{ range site.RegularPages }}
  {{ $href := .RelPermalink }}
  {{ with .Params.relPermalinkOverride }}
    {{ $href = . }}
  {{ end }}
  <h2><a href="{{ $href }}">{{ .Title }}</a></h2>
  {{ .Summary }}
{{ end }}