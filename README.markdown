TextMate Bundle for Factory Girl
================================
Yay!!!!

* <http://github.com/tinogomes/factory_girl-tmbundle>

Usage: <http://github.com/thoughtbot/factory_girl/wiki/Usage>

DESCRIPTION:
------------

The TextMate Bundle for Factory Girl - Inspiration from Factory Girl Snippets on <http://github.com/drnic/ruby-shoulda-tmbundle>

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

MAINTAINERS
-----------

* Tino gomes (<http://github.com/tinogomes>)
* Bruno Barros (<http://bkether.github.com/>)
