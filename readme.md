# Template for building a Shopware plugin using GitHub actions

At the moment this is just a simple template that helped us building our [Shopware monitoring plugin](ihttps://www.koality.io/de/magazin/de/articles/marketplace/shopware-6-monitor-plugin). It is not generalized yet, but we thought it could be a good idea to open source it and let the community doo its part.

The [release.yml](release.yml) file should be stored in the `<repo root>/.github/workflows/` directory. 

## Todos

- extract the plugin name from composer.yml and use it in all the tasks
- write the release name to the composer.yml file (already stored in `$RELEASE`)
- install all composer depedencies (withod dev deps)

## GitHub Action

It should be possible to create a single GitHub action that could do all the stuff at once. But until then you can use this one.
