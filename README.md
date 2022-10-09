# CV

Template for my CV layout, supporting both viewing in-browser and via printed
documents :tada: 

You can see it in action [here](https://jedevc.github.io/cv-template).

## Development

To get started, [click here](https://github.com/jedevc/cv-template/generate) to
create your own CV based on this repo.

Then you can clone your copy:

    $ git clone https://github.com/<your-username>/cv-template.git
    $ cd cv

Run a live site preview (ensuring [hugo](https://gohugo.io) is installed):

    $ hugo serve

You should then be ready to get started!

- First, fill out the contents of [config/_default/config.toml](./config/_default/config.toml),
  with your site name and url - while the CV will work with the defaults,
  you'll want to update them for best results.

- Next, you can customize [config/_default/params.yaml](./config/_default/params.yaml),
  with your CV!
  
- Finally, if you really want to dive deep, you can modify the templates in 
  [layouts/default/](./layouts/_default/) or switch up the styling in
  [assets/style/](./assets/style/) and get creative!

## Deployment

To deploy the site, just push your changes to your `main` branch - the
[GitHub Action](./.github/workflows/gh-pages.yaml) will deploy it automatically
to the `gh-pages` branch.

## License

This software is released under the UNLICENSE.

The contents of the `config/` directory is personal information, and is
withheld with all rights reserved.
