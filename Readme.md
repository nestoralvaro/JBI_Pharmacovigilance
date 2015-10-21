# JBI Pharmacovigilance
This repository contains the datasets used in our submission to the Journal of Biomedical Informatics Special Issue on Mining the Pharmacovigilance Literature.

## Structure
This project contains 4 folders:
* **1548_CrowdFlower**: Contains the 1548 annotations we retrieved from Crowdflower.
* **899_CrowdFlower**: Contains the 899 annotations used in the *First evaluation using the initial data set* section of our paper.
* **661_CrowdFlower_Expert**: Contains the 661 annotations used in the *Second evaluation using the initial data set* section of our paper.
* **3211_Experts**: Contains the 3211 annotations used in the *Extended evaluation* section of our paper.

To download the tweets you can either build a custom tool or use the [script provided by DIEGO LAB Biomedical Informatics Lab at ASU: http://diego.asu.edu/downloads/download_binary_twitter_data.py](http://diego.asu.edu/downloads/download_binary_twitter_data.py) replacing **fields[1]** in line saying **userid = fields[1]** with any existing Twitter user name (such as "twitter") and obtaining **userid = "twitter"**. We have included on this repository a version of the script with the needed change already performed.

The way in which the script should be invoked is:
* **python download_binary_twitter_data.py** *INPUT_FILE_NAME* **>** *OUTPUT_FILE_NAME*
* So in order to download the the 661 annotations used in the *Second evaluation using the initial data set* section of our paper the needed command would be:
  * **python download_binary_twitter_data.py** *661_CrowdFlower_Expert.tsv* **>** *output661.txt*
    * In this example the generated file (*output661.txt*) will contain the following 3 fields separated by tabs.
      * Tweet Identifier (tweet_ID).
      * Annotation for that tweet.
      * Text of the tweet.

Alternatively, you can use Twitter API to retrieve the tweets using the ID as described in [the documentation: https://dev.twitter.com/rest/reference/get/statuses/show/%3Aid](https://dev.twitter.com/rest/reference/get/statuses/show/%3Aid)

Our publication can be found at: **TBD** .

If you use any of these data, please cite our publication: **TBD** .