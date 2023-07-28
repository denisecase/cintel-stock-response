# cintel-stock-response

Testing Yahoo Finance API 

## Test the URL

First, try the URL in your browser. I requested 

https://query1.finance.yahoo.com/v7/finance/options/F

## Pretty JSON

Then, make it pretty.  I copy and pasted the whole result into https://jsonformatter.org/json-pretty-print (just do a each for online JSON pretty).

The pretty JSON is included below after deleting all of the option data that makes it huge (used the GitHub Dev environment to delete it. 

## Find the Key

From this, we see that regularMarketPrice is likely the key we need. 