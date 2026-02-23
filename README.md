# Example: Using an API with an AI

## Summary

The **demo.py** file in this repository shows how to use an API to submit queries to Anthropic's Claude AI. The process for other AIs, such as OpenAI's ChatGPT, is very similar.

The example uses Claude to interpret a text field filled in by users filing complaints about their vehicles with the National Highway Traffic Safety Administration (NHTSA).

## Input Data

There are two input files that will need to be downloaded from the course Google Drive folder: **COMPLAINTS_RECEIVED_2025-2026.zip** and **column-names.csv**. Please note that the complaints data should not be unzipped: the demo file expects to read the zipped version. The data originally came from the NHTSA web site: [NHTSA Datasets and APIs](https://www.nhtsa.gov/nhtsa-datasets-and-apis). NHTSA provides an API as well but this exercise does not use it.

## Deliverables

**None**. This is an example only and there's **nothing due**.

## Instructions

1. Browse the demo.py to see what techniques it demonstrates.

1. If you'd like to run it, or to use a similar process in your own work, you'll need to do the following things:

    1. Install the `anthropic` module. You'll need version 0.77.0 or later. The most up to date version will be available via Anaconda's `conda-forge` channel and can be installed this way:

        conda install anthropic -c conda-forge

    1. Sign up for an Anthropic developer account at [platform.claude.com](platform.claude.com). Unfortunately, this is not included in the University's license

    1. Go to the "API keys" page of the developer site and create an API key. Be sure to copy the key and store it somewhere on your computer because you won't be able to see it again. However, you could always create a new key if you lose it.

    1. Purchase some credits. In general, requests are very inexpensive so a few dollars will get you a long way. As of February 2026, the cost of one of the queries in this demo was about 0.3 cents so $3 would cover about a thousand of them.
