Shorten clipboard content with YOURLS, then copy short URL to clipboard

== SETUP ==

Fill out the configuration settings (or edit the "Run Script" utility). You will need to insert the domain (without the http or https) of your YOURLS installation and your signature token, which you find by going to your Admin Interface and clicking on "Tools".

The workflow itself works via the keyword "y", though you can change that of course, and it looks for the URL in your clipboard. The resulting short URL is then again copied to your clipboard. Optionally you can type something after the keyword separated by "*". E.g. you can short type, `y google.com*my search` and you get "yourshortdomain/my-search"

== Credit == 
Based on the work of:

- https://github.com/smoitzheim/alfred_yourls and
- https://gist.github.com/jazzsequence/95e40ec6a2a3faf9e04e