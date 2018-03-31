# NAME

App::diceware - A simple Diceware passphrase generator.

[![Build Status](https://travis-ci.org/jorol/App-diceware.png)](https://travis-ci.org/jorol/App-diceware)
[![Coverage Status](https://coveralls.io/repos/jorol/App-diceware/badge.png?branch=master)](https://coveralls.io/r/jorol/App-diceware?branch=master)
[![Kwalitee Score](http://cpants.cpanauthors.org/dist/App-diceware.png)](http://cpants.cpanauthors.org/dist/App-diceware)
[![CPAN version](https://badge.fury.io/pl/App-diceware.png)](http://badge.fury.io/pl/App-diceware)

# SYNOPSIS

    # via command line
    $ diceware.pl
    earthlinghandbookspiltunwillingappendage
    $ diceware.pl --language en --length 2 --pretty
    earthling-handbook

    # in Perl
    use App::diceware;

    my $diceware = App::diceware->new({language => 'en'});
    my $passphrase = diceware->passphrase({length => 5, pretty => 1});

# DESCRIPTION

App::diceware is a simple Diceware passphrase generator. It supports English 
and German wordlists.

# AUTHOR

Johann Rolschewski <jorol@cpan.org>

# COPYRIGHT

Copyright 2018- Johann Rolschewski

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO

[Dicewware](https://en.wikipedia.org/wiki/Diceware)
