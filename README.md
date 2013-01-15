# Dump Excel

This is a quick script that takes the latest DECC 2050 Model Excel spreadsheet and turns it into a series of web pages.

## Instalation

Requires:

1. Ruby 1.9+
2. The Bundler gem ```sudo gem install bundler```

Setup:

1. git clone http://github.com/decc/turn_decc_2050_model_into_web_pages.git
2. Setup a virtual host to point to the public folder (example in this folder)
3. Setup a crontab to periodically update the decc_2050_model: ``bundle update``
4. Setup a crontab to periodcially update the generated html: ``update``

