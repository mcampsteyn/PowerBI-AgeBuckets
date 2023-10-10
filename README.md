# PowerBI - Age Buckets

Displaying data across an age dimension by year can sometimes be too granular. Grouping multiple years into buckets can help to have more meaningful and condensed visuals. This repository contains two version of a DAX script to create age buckets in Power BI.

Variable BucketSize contains the size of the bucket.
By default the bucket size is 5 years but you can create any bucket size you want.

There are two versions of the bucket script.
The choice depends on you personal preference of how you want to display the buckets.

## version 1

0-4 years

5-9 years

10-14 years

...

## version 2

0-5 years

6-10 years

11- 15 years

...


The first bucket actually holds 6 years worth of data instead of five.
In reality a lost of datasets only an adult population and this first bucket is irrelevant.
