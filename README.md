# give-more-safety-online

## Running locally

This is a Middleman app. Clone or fork this repo, `cd` into it and run `$ middleman serve`.

## Help translate

To add a translation PR you need to
- provide a locale.yml with all the translations to the `locales` directory
- add a link to your locale [in the nav](https://github.com/lislis/give-more-safety-online/blob/master/source/layouts/layout.erb#L23). Give the link the locale as class
- add the locale and class name of the index page class (most likely `locale_index`) to the map in [the navigation highlight sass](https://github.com/lislis/give-more-safety-online/blob/master/source/stylesheets/_nav-highlight.sass#L1)

# Thanks

Insprired by [@plexus' give-a-safer-web](https://github.com/plexus/give-a-safer-web)!
