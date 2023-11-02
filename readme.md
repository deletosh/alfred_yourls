Shorten clipboard content with YOURLS, then copy short URL to clipboard

### [Download Workflow](https://github.com/deletosh/alfred_yourls/raw/main/Shorten%20URL%20with%20YOURLS.alfredworkflow)

![](https://i.imgur.com/6boCXFC.gif)


### Pre-req
1. Install php: `brew install php`

#### Setup

1. Fill out the configuration settings (or edit the "Run Script" utility). 
2. Enter the domain (without the http or https) of your YOURLS installation 
3. Enter your signature token (which you find by going to your Admin Interface and clicking on "Tools")
4. Done.

This workflow works with the keyword "y", you can change that of course.


The resulting short URL is then again copied to your clipboard. Optionally you can type something after the keyword separated by "*". E.g. you can short type, `y google.com*my search` and you get "yourshortdomain/my-search"

#### Credit
Based on the work of:

- https://github.com/smoitzheim/alfred_yourls and
- https://gist.github.com/jazzsequence/95e40ec6a2a3faf9e04e
