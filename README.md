# Hospital Chargemasters: Data and Analysis

Collection of United States hospital chargemasters as of March and April 2019.

## Purpose

By centralizing chargemaster data and performing some modeling and some basic analysis, we hope to enlighten the policy debate surrounding cost transparency of the US healthcare industry, at the very least providing actionable advice to the US government on better data policies to be implemented in the future.

## Background

Starting January 1, 2019, the US Department of Health and Human Services [began requiring US hospitals to report lists of their standard charges for items and services.](https://www.nytimes.com/2019/01/13/us/politics/hospital-prices-online.html) However, unfortunately, these lists (known in the industry as "chargemasters") have a variety of problems:

1. They are located in all sorts of [crazy places](https://qz.com/1518545/price-lists-for-the-115-biggest-us-hospitals-new-transparency-law/) on the Internet and not a central location. 
    * **This repo strives to correct this in particular, to the extent feasible for a volunteer project**, by putting the datasets we can find into one place, open to all who want to see them.
2. They are in a myriad of formats, with inconsistent column names
    * We will attempt to combine the chargemasters we have into a single data table
3. The procedures/items listed in them are often encoded using terms that are indecipherable to the untrained eye.
    * It is our hope that, with enough of these chargemasters and some clever natural language processing, we may be able to decode these and make them more layman-readable
4. The prices in the chargemasters are often inflated by seemingly random amounts, the result of attempting to provide more flexibility for hospitals when negotiating actual prices with insurance companies.
    * Once procedures and consumables are decoded and comparable semantically, the distributions of these prices by location, hospital type, etc. will be interesting to investigate.

## Important Notes

After doing some of my own searching and extracting of files (see `chargemasters` folder), I discovered [this wonderful repo](https://github.com/vsoch/hospital-chargemaster) maintained by @vsoch and abandoned my preliminary efforts to collect these chargemasters in favor of using her great collection. So, feel free to ignore what I currently have in my `chargemasters` directory in favor of what's in that repo. Thanks @vsoch!

## License

This project uses the MIT License.