rubystack CHANGELOG
==================

This file is used to list changes made in each version of the rubystack cookbook.

0.1.3
-----
- Initial release of rubystack

0.1.4
-----
- Update `database_sl` version to `0.1.8`

0.1.5
-----
- Install node as deployer user

0.1.6
-----
- Fix nodejs install process in `rails_deploy` recipe

0.1.7
-----
- Fix nodejs install process in `rails_deploy` recipe

0.1.8
-----
- Locks `ridley` and `net-ssh` gems to fit travis ci (group `travis_ci` in `Gemfile`)

0.1.9
-----
- Updates `rvm_sl` cookbook version to `0.2.0` to create `.gemrc` with no
  documentation options.
- Sets the primary group of deployer user to apache run group

- - -
Check the [Markdown Syntax Guide](http://daringfireball.net/projects/markdown/syntax) for help with Markdown.

The [Github Flavored Markdown page](http://github.github.com/github-flavored-markdown/) describes the differences between markdown on github and standard markdown.
