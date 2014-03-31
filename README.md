# Beerclub

A simple, static site generated by [Jekyll](http://jekyllrb.com) and hosted on [Github Pages](http://pages.github.com) which lists the beers enjoyed by the BeerClub at [R/GA London](http://rga.com)

[http://beerclub.hawksworx.com](http://beerclub.hawksworx.com)


## Contributing

Pull requests and contributions are welcome. The content is managed by Jekyll's data system, so adding a beer to the list is as simple as editing the [_data/drops.yml](_data/drops.yml) file.

The images are all hosted on Instagram. Add a public Instagram page URL (without a trailing `/`) to the `_data/drops.yml` file in order to include the image in the site.

You can now add an award for each bear you add on the website. Add a line in the [_data/drops.yml](_data/drops.yml) file like this : "award: your award here".

## Deployment

The site is generated via Github's Jekyll support. Pushing code to the `gh-pages` branch will envoke a build and deployment.
