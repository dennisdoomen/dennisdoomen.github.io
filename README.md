# Dennisdoomen.github.io

The future home of <http://www.continuousimprover.com/>.

## How to Build this Site

### Prerequisites

* Ruby 2.4.x (note: 2.5 and higher may fail due to the `ffi` ruby lib only supporting < 2.5). 
* An easy way to install it is to download `Ruby+Devkit 2.4.10-1 (x64)` from the [RubyInstaller site](https://rubyinstaller.org/downloads/) and run option 3 from the msys install menu.
* The `bundler` gem (`gem install bundler`). If you receive SSL-related errors while running `gem install`, try running `refreshenv` first. 

### Building

* Clone this repository
* `cd` into the root of the repository
* Run `bundle install`. 
* Run `bundle exec jekyll serve`. To have it monitor your working directory for changes, add the `--incremental` option. 

## Troubleshooting

* Do you receive an error around `jekyll-remote-theme` and `libcurl`? See [this issue on the pages-gem repo](https://github.com/github/pages-gem/issues/526).
* Do you receive an error `Liquid Exception: SSL_connect returned=1 errno=0 state=error: certificate verify failed`? Check out [this solution in the Jekyll repo.](https://github.com/jekyll/jekyll/issues/3985#issuecomment-294266874)
* 