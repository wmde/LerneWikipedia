# LerneWikipedia
[Lerne Wikipedia](https://de.wikipedia.org/wiki/Wikipedia:Wikimedia_Deutschland/LerneWikipedia) is a page in German Wikipedia which provides one central starting point for new editors in Wikipedia. It is aimed at new editors who want to start contributing to the project and need some advice on how to proceed and how to learn the basic principles of Wikipedia. The page was launched in Oktober 2019.

## Setup and Deployment
*Lerne Wikipedia* is written in WikiText/HTML and takes advantage of a Set of Templates (Template:LerneWP/) and Template-Styles. The .html .wiki and .css files need to be synchronized with the MediaWiki manually.

The visual appearance is defined by a StyleSheet that is compiled from a SASS file, to make development easier. The compilation itself is done via node-sass. Please install the package.json for setup:
`npm install`

To update the CSS file automatically use:
`npm run scss`

## Contributing
If you found a bug, would like to contribute ideas or code or are interested in bringing *Lerne Wikipedia* to another Wikipedia feel free to initiate a pull request to this repo.

Please use the discussion page in Wikipedia to get in contact with the makers of this project.

## License
The version developed in this repository is licensed under MIT license.
