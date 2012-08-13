Diamond Brite
========

This is a website that I am putting together for a buddy of mine for his pool service. Been trying to brush up some front end skills so here is my go at front end development. It uses twitter bootstrap with modified parallax fluid css.

Demo at  [diamond brite poolservice][homepage].


Installation
========

Install RVM
========

curl -L https://get.rvm.io | bash -s stable --ruby

Look at [RVM][rvm] for more details.


Install Padrino with RVM
========

rvm gem install padrino 

Look at [Padrino][pad] for more documentaion on [Padrino][pad].

Clone the pad-db Repo
=======
``` ruby
git clone git@github.com:lkkadiri/pad-db.git
````

Get into the directory
=======

``` ruby
cd pad-db/
```

Bundle Install
======
``` ruby
bundle install
```

Create, Migrate and seed the padrino database
=====

``` ruby
padrino rake ar:create

padrino rake ar:migrate

padrino rake seed
```

Start Padrino
======

``` ruby
padrino start
```
Goto Site
=====

Point your browser to 
``` ruby
http://localhost:3000/
```

Who Are You?
============
I'm [Leela Krishna Kadiri][lkk].


[homepage]:http://diamondbritepoolservice.com/
[lkk]:https://github.com/lkkadiri
[rvm]:https://rvm.io/rvm/install/
[pad]:http://www.padrinorb.com/