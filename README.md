# unicode-flag-finder
A TypeScript/JavaScript library to find the Unicode for flags based on country name or code

# Usage

## Calling
`flag = Flags.find(country)`

Country can be either a full country name, or the two letter code for the country.

e.g. 

`flag = Flags.find("AU")`

or

`flag = Flags.find("Australia")`

This will return an object with four properties.

## Return object properties

`flag.country`

The name of the given country.

e.g. Australia

`flag.ISO`

The two letter ISO code of the given country.

e.g. AU

`flag.native`

The native unicode for the given flag

e.g. 🇦🇺

`flag.unicode`

The unicode codepoints for the given flag

e.g. U+1F1E6 U+1F1FA

# Attribution

All data was scraped from https://apps.timwhitlock.info/emoji/tables/iso3166
