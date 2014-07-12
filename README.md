Pod::SAX
========

System for making Pod::To::Something converters

## Pod::SAX::Goes::HTML

System that uses Pod::SAX to reform Pod objects to HTML representation.
On work currently. You can see example of the module's work at http://atroxaper.github.io/Pod-SAX/. This is the part of S26.

### Current highlighted features

* Most part of L<>
* Case then we have D<> (or D<|;>) and corresponding L<defn:>
* Formating B<> R<> I<> C<>
* Code blocks with formating
* Tables
* Table of contents

### Known issues

* Pod::SAX::Goes::HTML can throw SIGSEGV on Rakudo Parrot