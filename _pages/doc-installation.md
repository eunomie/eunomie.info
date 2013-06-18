---
layout: doc
---

# Installation

The main part of _Web log today_ is based on [sub](https://github.com/37signals/sub) so the installation is really easy.

You just need git, ruby 1.9.3 and gem.

1. Get the sources in `~/.wlt` by example
    
    ```sh
    git clone git://github.com/eunomie/wlt.git ~/.wlt
    ```

2. Run [bundler][]

    ```sh
    cd ~/.wlt
    bundle
    ```

3. Install it.

    For bash :
    ```sh
    echo 'eval "$(~/.wlt/bin/wlt init -)"' >> ~/.bash_profile
    exec bash
    ```

    For zsh :
    ```sh
    echo 'eval "$(~/.wlt/bin/wlt init -)"' >> ~/.zshenv
    source ~/.zshenv
    ```

Here we go! `wlt` is installed. So easy, isn't it?

[bundler]: http://gembundler.com/
