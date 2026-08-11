# Code and data for developers

HEP Training is committed to the FAIR principles: making data findable, accessible, interoperable and re-usable. As such, all content in HEP Training is available under the CC BY 4.0 licence, and can be accessed through our API and widgets. The HEP Training codebase is also available to re-use under the BSD Licence, and can be found on GitHub.


::::{grid} 1 1 2 2
:class-container: text-center
:gutter: 3

:::{grid-item-card}

{octicon}`mark-github` **Software**
^^^

The source code for HEP Training [is available on GitHub](https://github.com/ElixirTeSS/HEP Training), under the [BSD 3-Clause](https://heptraining.cern.ch/about/developers#api:~:text=available%20under%20the-,BSD%203%2DClause,-license.) license. 
We welcome [contributions](https://github.com/ElixirTeSS/HEP Training/blob/master/CONTRIBUTING.md).
:::


:::{grid-item-card}

{fas}`plug;sd-text-secondary` **Data**
^^^

Data in HEP Training can be accessed via our [API](#api), under the [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/).
:::

::::


## Widgets
Widgets are chunks of javascript code that can be copied into website source code to display HEP Training content. There are several different styles and functionalities available from our configurable widget suite. Widgets can be used to enhance your site and offer your community lists of relevant events or training resources.

```{button-link} https://elixirtess.github.io/TeSS_widgets/
:color: primary
View our available widgets
```

```{admonition} See also guidance from the ELIXIR Training Platform
:class: seealso
* [Integrating HEP Training widgets on your web site](https://elixir-europe-training.github.io/ELIXIR-TrP-HEP Training/chapters/chapter_03/)
```

## API

HEP Training has a fully functioning JSON API. You can explore our JSON-API by appending `.json_api` to the end of the URL of most pages (excluding parameters). For example:

```
https://heptraining.cern.ch/events.json_api
https://heptraining.cern.ch/materials.json_api?scientific_topics=RNA-Seq
https://heptraining.cern.ch/content_providers.json_api
https://heptraining.cern.ch/workflows.json_api
https://heptraining.cern.ch/materials/how-to-make-your-messy-data-usable-openrefine.json_api
```

To get [Bioschemas](https://bioschemas.org) JSON-LD representation of individual materials or events, append `.jsonld` instead:

```
https://heptraining.cern.ch/materials/how-to-make-your-messy-data-usable-openrefine.jsonld
```

The full documentation for the HEP Training JSON API can be found here:

```{button-link} https://heptraining.cern.ch/api/json_api
:color: primary
View the JSON-API documentation
```

If you already use the old API, technical information is still available in the [legacy API documentation](https://heptraining.cern.ch/api/legacy).


## Developer guides

There are additional guides for installing and configuring a HEP Training instance.

```{button-link} https://github.com/ElixirTeSS/HEP Training/tree/master/docs
:color: primary
View the developer guides (on GitHub)
```