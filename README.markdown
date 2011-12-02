TextMate Bundle for Factory Girl 2.0
====================================
Yay!!!!

* [http://github.com/bkether/factory_girl-tmbundle](http://github.com/bkether/factory_girl-tmbundle)

DESCRIPTION:
------------

The TextMate Bundle for Factory Girl - Based from Factory Girl Snippets on [http://github.com/drnic/ruby-shoulda-tmbundle](http://github.com/drnic/ruby-shoulda-tmbundle) and the old factory_girl sintaxe version < 2.0 [http://github.com/tinogomes/factory_girl-tmbundle](http://github.com/tinogomes/factory_girl-tmbundle). Thx guys!

tinogome: You can asking in your mind? Why this Bundle? Well, in my case, I use Factory Girl with RSpec and I don't want to install Ruby Shoulda Bundle on my TextMate. Only this.

bkether: factory_girl-tmbundle is old. So the new sintaxe for factory girl 2.0 does not work. This is my motivation!

INSTALATION:
------------

with Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/bkether/factory_girl-tmbundle.git FactoryGirl.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget http://github.com/bkether/factory_girl-tmbundle/tarball/master
    tar zxf bkether-factory_girl-tmbundle*.tar.gz
    rm bkether-factory_girl-tmbundle*.tar.gz
    mv bkether-factory_girl-tmbundle* "FactoryGirl.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

MAINTAINER
----------

* Celestino Gomes (<http://blog.tinogomes.com/>) old version
* Bruno Barros (<http://bkether.github.com/>) new version