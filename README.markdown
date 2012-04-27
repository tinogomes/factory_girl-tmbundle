TextMate Bundle for Factory Girl
================================
Yay!!!!

* <http://github.com/tinogomes/factory_girl-tmbundle>

DESCRIPTION:
------------

The TextMate Bundle for Factory Girl - Inspiration from Factory Girl Snippets on <http://github.com/drnic/ruby-shoulda-tmbundle>

To use with Factory Girl, on version 1.x, use tag v1.x

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

SNIPPETS
--------

For factories definition ( _ as cursor stop, {{ ... }} as checkpoint to edit )

* ```facd<tab>``` - FactoryGirl define block

```ruby
FactoryGirl.define do
  _
end
```

* ```facd<tab>``` - FactoryGirl define block with factory

```ruby
FactoryGirl.define do
  factory :{{model_name}} do
    _ # cursor stops here
  end
end
```

* ```fac<tab>``` - FactoryGirl definition

```ruby
factory :{{model_name}} do
  _
end
```

* ```fac<tab>``` - FactoryGirl definition with aliases

```ruby
factory :{{model_name}}, :aliases [:{{alias}}] do
  _
end
```

* ```fac<tab>``` - FactoryGirl definition with parent

```ruby
factory :{{model_name}}, :parent => :{{factory_name}} do
  _
end
```

* ```fac<tab>``` - FactoryGirl definition with class

```ruby
factory :{{model_name}}, :class => {{ModelName}} do
  _
end
```

* ```facs<tab>``` - FactoryGirl sequence definition

```ruby
FactoryGirl.sequence :{{sequence_name}} do { |n| "#{n}_" }
```

* ```faca<tab>``` - FactoryGirl attribute definition

```ruby
{{attribute_name}}} { _ } 
```

* ```facas<tab>```  - FactoryGirl attribute association definition

```ruby
association :{{attribute_association}}, :factory => {{factory_name}}_
```

* ```facab<tab>``` - FactoryGirl after build callback

```ruby
after_build {|{{model_name}}, evaluator| _ }
```

* ```facac<tab>``` - FactoryGirl after create callback

```ruby
after_create {|{{model_name}}, evaluator| _ }
```

* ```facas<tab>``` - FactoryGirl after stub callback

```ruby
after_stub {|{{model_name}}, evaluator| _ }
```

* ```facg<tab>``` - FactoryGirl generate sequence

```ruby
FactoryGirl.generate(:{{sequence_name}})_
```

* ```facb<tab>``` - FactoryGirl build factory

```ruby
FactoryGirl.build(:{{model}}) do
  _
end
```

* ```facb<tab>``` - FactoryGirl build factory

```ruby
FactoryGirl.build(:{{model_name}}) do
  _
end
```
* ```facc<tab>``` - FactoryGirl create factory

```ruby
FactoryGirl.create(:{{model_name}}) do
  _
end
```

* ```facbs<tab>``` - FactoryGirl build stubbed factory

```ruby
FactoryGirl.build_stubbed(:{{model}}) do
  _
end
```

* ```facaf<tab>``` - FactoryGirl attributes for factory

```ruby
FactoryGirl.attributes_for(:{{model}}) do
  _
end
```

* ```facbl<tab>``` - FactoryGirl build factory in list

```ruby
FactoryGirl.build_list(:{{model}}, {{count}}) do
  _
end
```

* ```faccl<tab>``` - FactoryGirl create factory in list

```ruby
FactoryGirl.create_list(:{{model}}, {{count}}) do
  _
end
```

MAINTAINERS
-----------

* Tino gomes (<http://github.com/tinogomes>)
* Bruno Barros (<http://bkether.github.com/>)
