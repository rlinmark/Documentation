# Documentation

Hello, and welcome to the Documentation repo for Wilderness Labs! These docs are probably best viewed at the [developer.wildernesslabs.co](http://developer.wildernesslabs.co), but they should be readable here, as well. You'll also find all the source code to the [samples](samples/) here.


## Running Locally

This repo is also a Ruby site powered by jekyll (which is how it's hosted by GitHub Pages). You can run and browse this site locally, which is especially useful if you're contributing documentation, or you just want an offline experience.

To browse locally:

### 1. [Install Homebrew](https://brew.sh/) (if not already installed)


### 2. Install prerequisites: Ruby, Jekyll, Bundler, and various gems

Open a terminal and navigate to the `Documentation/docs` folder and run:

```
$ brew install ruby
```

Once you have Ruby, you'll need Jekyll and Bundler to build and host the site locally:

```
$ gem install jekyll bundler
```

With the Bundler installed to manage the Ruby gems, you can run a command to install all the prerequisite gems for the site:

```
$ bundle install
```

### 3. Launch local server

Change your terminal working folder to `Documentation/docs` (if it's not aleady) and run:

```
bundle exec jekyll serve
```

The site should be available locally at: `http://127.0.0.1:4001/`. You can verify the IP address and port from the jekyll output in terminal.

Changes should automatically be picked up and displayed on the site.

## [Contributing](Contributing)

Wilderness Labs welcomes and encourages constrictive contributions. We believe that documentation is best when a diverse community of folks with a variety of perspectives and experience share their wisdom and findings with others. Additionally, documentation contributions are a great way to capture learnings that you may even reference yourself.

For more information, please see the [Contributing](Contributing) page.

## License

### Documentation Prose

All the documentation prose is released under a [Creative Commons 
Attribution + Noncommercial + NoDerivatives (CC BY-NC-ND) license](Licenses/CreativeCommons_BY_NC_ND.md). Feel free to share verbatim in non-commercial usage and provide attribution. Commercial usage may be granted in certain use cases. If you need a more permissive license, please contact us at [hello@wildernesslabs.co](mailto:hello@wildernesslabs.co).

![Creative Commons BY-NC-ND Logo](Licenses/Cc-by-nc-nd_icon.png)

[Human Readable Version of the License](https://creativecommons.org/licenses/by-nc-nd/4.0/)

### Code Samples and Code Snippets

All code samples and code snippets, whether they be full applications, or embedded snippets within the documentation are released under the [Apache 2 license](Licenses/Apache2_License.md). Feel free to use and distribute the code as you see fit, under the very permissive terms of the license.
