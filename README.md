## Description

Converts QIF files downloaded from First Direct and OFX files from Barclaycard, converts them into compatible OFX files, and uploads them to [MoneyTracker](https://github.com/chrisroos/money-tracker).

## Requirements

* Ruby (tested on v2.2)
* sed
* iconv (tested with GNU libiconv 1.11)
* [fixofx](https://github.com/wesabe/fixofx)
 * Python >= v2.6
* OS X Automator

## Environment variables

    FIRST_DIRECT_SORTCODE
    MONEY_TRACKER_HOST
    MONEY_TRACKER_USERNAME
    MONEY_TRACKER_PASSWORD
    PATH_TO_FIXOFX
    OUTPUT_PATH
