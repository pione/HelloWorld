# PIONE package "HelloWorld"

PIONE(Process-rule for Input/Output Negotiation Enviromenment) is a rule-based workflow engine and PIONE package is the package of process flow. This is the simplest PIONE package "HelloWorld".

## How to process the package

### Install PIONE

    $ gem install pione

### Process as a git package

    $ pione-client https://github.com/pione/HelloWorld.git

### Process as archive package

    $ pione-package --build --git-repository https://github.com/pione/HelloWorld.git --tag "v0.1.0"
    $ pione-client HelloWorld[v0.1.0]~a5dd7b0d.ppg

### Process as a single PIONE document

    $ pione-client https://raw.github.com/pione/HelloWorld/master/HelloWorld.pione

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## License

HelloWorld package is free software distributed under MIT license.

## Links

* [PIONE project homepage](http://pione.github.io/)
    * [repository on github](https://github.com/pione/pione)
* [Yasunaga Laboratory](http://www.yasunaga-lab.bio.kyutech.ac.jp/)
    * [EOS](http://www.yasunaga-lab.bio.kyutech.ac.jp/Eos/)([ja](http://www.yasunaga-lab.bio.kyutech.ac.jp/EosJ/))
* [Japan Science and Technology Agency](http://www.jst.go.jp/EN/index.html)([ja](http://www.jst.go.jp/))
     * [Develoment of Systems and Technology and for Advanced Measurement and Analysis](http://www.jst.go.jp/sentan/en/)([ja](http://www.jst.go.jp/sentan/))
* [NaU Data Institute Inc.](http://www.nau.co.jp/index_en.html)([ja](http://www.nau.co.jp/))

