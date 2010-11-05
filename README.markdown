TextMate Bundle for Factory Girl
================================

* [http://github.com/tinogomes/factory_girl-tmbundle](http://github.com/tinogomes/factory_girl-tmbundle)

DESCRIPTION:
------------

The TextMate Bundle for Factory Girl - Based from Factory Girl Snippets on [http://github.com/drnic/ruby-shoulda-tmbundle](http://github.com/drnic/ruby-shoulda-tmbundle)

You can asking in your mind? Why this Bundle? Well, in my case, I use Factory Girl with RSpec and I don't want to install Ruby Shoulda Bundle on my TextMate. Only this.

INSTALATION:
------------

with Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/tinogomes/factory_girl-tmbundle.git FactoryGirl.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget http://github.com/tinogomes/factory_girl-tmbundle/tarball/master
    tar zxf tinogomes-factory_girl-tmbundle*.tar.gz
    rm tinogomes-factory_girl-tmbundle*.tar.gz
    mv tinogomes-factory_girl-tmbundle* "FactoryGirl.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

MAINTAINER
----------

* Celestino Gomes (<http://blog.tinogomes.com/>)

LICENSE:
--------

<a rel="license" href="http://creativecommons.org/licenses/by/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/3.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/3.0/">Creative Commons Attribution 3.0 Unported License</a>.