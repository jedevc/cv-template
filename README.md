# CV

Template for my personal CV :tada: You can see it in action [here](https://cv.jedevc.com).

The single page on the site is generated using the parameters in
[config/_default/params.yaml](./config/_default/params.yaml),
while site-wide configuration can be found in
[config/_default/config.toml](./config/_default/config.toml).

## Development

To get started, [click here](https://github.com/jedevc/cv-template/generate) to
create your own CV based on this repo.

Then you can clone your copy:

    $ git clone https://github.com/<your-username>/cv-template.git
    $ cd cv

Run a live site preview (ensuring [hugo](https://gohugo.io) is installed):

    $ hugo serve

You can also just build the site:

    $ hugo
    
## Deployment

To deploy the site, just push your changes to your `main` branch - the
[GitHub Action](./.github/workflows/gh-pages.yaml) will deploy it automatically
to the `gh-pages` branch.

## License

This software is released under the UNLICENSE.

The contents of the `config/` directory is personal information, and is
withheld with all rights reserved.
