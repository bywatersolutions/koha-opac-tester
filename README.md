# koha-opac-tester
A small utility to test a Koha OPAC to ensure it is functioning correctly.

This utility will search and opac and return a good status code if the site gives back a 200 and the string to look for is found.

## Usage
test-koha-opac -v -d catalog.mylibrary.org -s "cat in the hat" -l "The Cat in the Hat"

-v --verbose      - Prints output for puny humans ( optional )
-d --domain       - The opac domain to be checked
-s --search-term  - The word or words to search for
-l --look-for     - The phrase to check the resultant html for, defaults to the search term if not provided
