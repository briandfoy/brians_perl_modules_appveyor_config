# brian's Standard Configuration for Perl 5 Modules on AppVeyor

[AppVeyor](https://www.appveyor.com/) is a continuous integration service for Windows and Linux. I test my [public Perl modules](https://github.com/briandfoy) on it and they often have the same configuration. I created this repository to version a file that show up in most of my repositories.

You can get the latest version of the file (say, in a shell script). Note that the file you want is *perl-appveyor.yml*, not the *.appveyor* file in the repo (which tests this repo, not Perl repos):

	$ curl -o .appveyor.yml https://raw.githubusercontent.com/briandfoy/brians_perl_modules_appveyor_config/master/perl-appveyor.yml

I have similar repositories:

* [GitHub Actions for Perl 5 Modules](https://github.com/briandfoy/github_actions)


And sometimes I write about these things:

* [IntermediatePerl.com posts tagged with "appveyor"](https://www.intermediateperl.com/tag/appveyor/)
