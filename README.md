# Personal Page 
*<div style="text-align: right"> based on [Minimal Mistakes Jekyll theme](https://mmistakes.github.io/minimal-mistakes/) </div>*

[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/mmistakes/minimal-mistakes/master/LICENSE)
[![Jekyll](https://img.shields.io/badge/jekyll-%3E%3D%203.7-blue.svg)](https://jekyllrb.com/)


**Note:** The theme uses the [jekyll-include-cache](https://github.com/benbalter/jekyll-include-cache) plugin which will need to be installed in your `Gemfile` and must be retained in the `plugins` array of `_config.yml`. Otherwise you'll encounter `Unknown tag 'include_cached'` errors at build. More features are listed in the original repo.

<!--
  Dev note: The version number is currently hard-coded in these files:

    - package.json
    - README.md (this file)
    - docs/_data/theme.yml
    - docs/_pages/home.md (in Front Matter "excerpt")

  `package.json` holds the authoritative version number, and the others can be updated with `bundle exec rake version`.

  The following files should also be regenerated:

    - _includes/copyright.html, _includes/copyright.js, _sass/minimal-mistakes/_copyright.scss
      (Run `bundle exec rake clean` then `bundle exec rake copyright` - all three references `package.json`)
    - assets/js/main.min.js (Run `bundle exec rake js`, references `_includes/copyright.js`)

  *Tip*: The default Rake task will update all of the above files at once.

  Additionally, the license year is hard-coded in these files and are NOT covered by a Rake task:

    - README.md (this file, near the end)
    - LICENSE
-->


## Development

To set up the environment to develop this theme, run `bundle install`.

To test the theme, run `bundle exec rake preview` and open your browser at `http://localhost:4000/test/`. This starts a Jekyll server using content in the `test/` directory. As modifications are made to the theme and test site, it will regenerate and you should see the changes in the browser after a refresh.

## Credits & License

Credits to [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)

The MIT License (MIT): [Original](https://mmistakes.github.io/minimal-mistakes/) | [Modified](LICENSE)
