# HTML::WikiConverter::Markdown

This module adds HTML-to-Markdown conversion to the HTML::WikiConverter module.

## SYNOPSIS

Converting HTML to wiki markup is easy:

	use HTML::WikiConverter;
	my $wc = new HTML::WikiConverter( dialect => 'Markdown' );
	print $wc->html2wiki( "<b>hello</b>" );

Or from the command line:

	$ html2wiki --dialect Markdown input.html > output.wiki

There's also a web interface if you're so inclined: http://diberri.dyndns.org/wikipedia/html2wiki/

## INSTALLATION

To install this module, run the following commands:

	$ perl Makefile.PL
	$ make
	$ make test
	$ make install

For test coverage metrics run:

	$ perl Makefile.PL
	$ make
	$ cover -delete
	$ make test HARNESS_PERL_SWITCHES=-MDevel::Cover
	$ cover

## SUPPORT AND DOCUMENTATION

After installing, you can find documentation for this module with the perldoc command.

	$ perldoc HTML::WikiConverter::Markdown

You can also look for information at:

* Search [CPAN](	http://search.cpan.org/dist/HTML-WikiConverter-Markdown)
* [CPAN Request Tracker](	http://rt.cpan.org/NoAuth/Bugs.html?Dist=HTML-WikiConverter-Markdown)
* [AnnoCPAN, annotated CPAN documentation](	http://annocpan.org/dist/HTML-WikiConverter-Markdown)
* [CPAN Ratings](	http://cpanratings.perl.org/d/HTML-WikiConverter-Markdown)

## COPYRIGHT AND LICENCE

Copyright (c) David J. Iberri

This program is free software; you can redistribute it and/or modify it
under the same terms as Perl itself.

