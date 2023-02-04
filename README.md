# Future News

Future news hosts ai / human generated content in the style of an online media outlet.
* * *

### Beta

Betad development is hosted [HERE](https://lookingglass.netlify.com/)

* * *

### Deployment

To run the theme locally, navigate to the theme directory and run `bundle install` to install the dependencies, then run `bundle exec jekyll serve` to start the Jekyll server.

I would recommend checking the [Deployment Methods](https://jekyllrb.com/docs/deployment-methods/) page on Jekyll website.


* * *

### Documentation
To develop this repo you need to have a ruby development environment. This is required if you need to fully verify a post before submitting.

#### Install ```rbenv```

```rbenv``` is a tool that helps you manage multiple Ruby versions on a single system. It allows you to switch between different versions of Ruby easily.

##### macOS

You can install ```rbenv``` using Homebrew:```brew install rbenv```

##### Linux

You can install ```rbenv``` using Git:bash
```bash
git clone https://github.com/rbenv/rbenv.git ~/.rbenv
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' &gt;&gt; ~/.bashrc
echo 'eval "$(rbenv init -)"' &gt;&gt; ~/.bashrc
```
##### Windows

You can install ```rbenv``` on Windows using the Windows Subsystem for Linux (WSL). Follow the Linux instructions after installing WSL.

#### Installing Ruby

Now that you have ```rbenv``` installed, you can use it to install a version of Ruby.```rbenv install 3.1.3```

You can check the available versions of Ruby by running:css

```css
rbenv install --list
```

Choose the version you want to install and replace ```3.1.3``` with that version in the command above.

#### Installing Bundler

Bundler is a tool that manages dependencies for futurenews.```gem install bundler```

#### Running Jekyll

Install the dependencies by running:```bundle install```

You can now serve futurenews by running
```
bundle exec jekyll serve
```

futurenews should now be running at http://localhost:4000.

