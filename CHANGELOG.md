# Version 0.1.8

## Bugfixes

* None

## Features

* Enhance NamingDirectory functionality with recursive bind/search functionality

# Version 0.1.7

## Bugfixes

* None

## Features

* Add session-ID, necessary for lookup stateful session beans SFBs, to lookup() and sibling methods

# Version 0.1.6

## Bugfixes

* None

## Features

* Add NamingDirectory and NamingDirectoryInterface

# Version 0.1.5

## Bugfixes

* Allow specification of default transport protocol for remote lookup handling => defaults to HTTP now

## Features

* None

# Version 0.1.4

## Bugfixes

* Allow a minus char (-) in context name when parsing naming directory identifier passed to InitialContext::prepareResourceIdentifier() method

## Features

* None

# Version 0.1.3

## Bugfixes

* None

## Features

* Using nikic/phlexy as lexer for parsing JNDI style bean names in InitialContext::lookup() method

# Version 0.1.2

## Bugfixes

* None

## Features

* Switching to from ResourceIdentifier => EnterpriseBeanResourceIdentifier for InitialContext::lookup() method

# Version 0.1.1

## Bugfixes

* None

## Features

* Switching to new techdivision/persistencecontainer version > 0.7

# Version 0.1.0

## Bugfixes

* None

## Features

* Initial Release