# Hexo-Demo #

<br>

The purpose of this repository is it to demonstrate the use of [Hexo](https://hexo.io/), which is a *Static Site Generator*.
In the repository you'll find the Hexo project and also the web site generated by it.

<br>

The web site generated based on the sources and configurations in the repository can be viewed at:

**https://mdecker-mobilecomputing.github.io/Hexo-Demo/**

<br>

----

## Working with the Hexo project ##

<br>

You'll need a global installation of *Hexo*, so install it as follows:
```
npm install -g hexo-cli
```

<br>

After cloning of this repository you have to call the following command to fetch the dependencies defined in file `package.json`:
```
npm install
```

<br>

Then you can start the preview of the site:
```
hexo server
```

<br>

To create another posting the following command can be used
```
hexo new "title of new posting"
```

<br>

To generate the web content, call the following commands:
```
hexo clean
hexo generate
```

<br>

----

## About this Hexo project/site ##

<br>

In file [_config.yml](_config.yml) the output folder was changed from `public/` to `docs/` (see key `public_dir`).
The reason for this was to enable simple serving of the generated web content with [GitHub pages](https://pages.github.com/).

The source files for the articles and pages written in Markdown syntax can be found in folder [source/](source).

<br>
