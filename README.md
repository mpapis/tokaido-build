# Static Ruby

Compiling static ruby:

    curl -L https://raw.github.com/sm/sm/master/bin/sm-installer | sh
    echo "export PATH=\"$HOME/.sm/bin:$HOME/.sm/pkg/active/bin:\$PATH\"" >> .bashrc
    source ~/.bashrc
    sm ext install tokaidoapp tokaido/tokaido-build
    sm tokaidoapp dependencies
    sm tokaidoapp install

Ruby is installed in `$HOME/.sm/pkg/versions/tokaidoapp/1.9.3-p125/`

