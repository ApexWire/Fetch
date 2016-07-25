apexwire/fetch changelog
---------------------------

## v0.10.1 on 2016.07.25

- fix bug: Undefined property: stdClass::$host. Message.php(807)

## v0.10.0 on 2016.05.24

- add function: closeConnection

## v0.9.1 on 2016.05.24

- fix bug: Undefined property: stdClass::$bytes. Attachment.php(102)
- fix bug: Undefined property: stdClass::$subject. Message.php(256)

## v0.9.0 on 2016.05.16

- Add rawEmail in Message
- Add function encodingsIdToString 
- Now rawBody associative array

## v0.8.0 on 2016.04.15

- The minimum version of php 5.4
- Add rawBody in Message
- Add changelog.md
- README.md rename README_EN.md. Add README.md - russian 
- Merge pull request [#147](https://github.com/tedious/Fetch/pull/147) from linniksa/patch-mime-decoder 
- Changes from the pull request [#151](https://github.com/tedious/Fetch/pull/151)

## v0.7.1 on 2 Aug 2015

- Merge pull request [#145](https://github.com/tedious/Fetch/pull/145) from tedious/supress_php_warning
- Suppressed imap_open warning

## v0.6.1 on 8 Jan 2015

- Merge pull request [#109](https://github.com/tedious/Fetch/pull/109) from tedious/release-0.6.1
- Changed function names for cs consistency


## v0.5.3 on 14 Mar 2014

- Merge pull request [#40](https://github.com/tedious/Fetch/pull/40) from bjornpost/fix-multipart-messagebody
- In a multipart email messageBody() keeps headers


## v0.5.2 on 21 Jan 2014

- Merge pull request [#33](https://github.com/tedious/Fetch/pull/33) from tedivm/testing_update
- Separate Mail Server Setup into Development Package


## v0.5.1 on 19 Dec 2013

- Removed autoloader reference


## v0.4.5 on 1 Dec 2013

- Merge pull request [#27](https://github.com/tedious/Fetch/pull/27) from ArabCoders/master
- fixed bug in getting reply_to addresses


## v0.4.4 on 28 Jul 2013

- Merge pull request [#19](https://github.com/tedious/Fetch/pull/19) from codyfletcher/master
- Added support for "bcc" as a type of processed object.


## v0.4.3 on 12 Jul 2013

- Merge pull request [#17](https://github.com/tedious/Fetch/pull/17) from abimus/fix/flags
- Fix behavior on Server::setFlag()


## v0.4.2 on 2 Jul 2013

- Added bug fixed.

## v0.4.1 on 26 Nov 2012

- First release since migrating to github
