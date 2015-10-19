# JBI Pharmacovigilance
This repository contains the datasets used in our submission to the Journal of Biomedical Informatics Special Issue on Mining the Pharmacovigilance Literature.

## Structure
This project contains 4 folders:
* **1548_CrowdFlower**: Contains the 1548 annotations we retrieved from Crowdflower.
* **899_CrowdFlower**: Contains the 899 annotations used in the *First evaluation using the initial data set* section of our paper.
* **661_CrowdFlower_Expert**: Contains the 661 annotations used in the *Second evaluation using the initial data set* section of our paper.
* **3211_Experts**: Contains the 3211 annotations used in the *Extended evaluation* section of our paper.

To download the tweets you can either build a custom tool or use the [script provided by DIEGO LAB Biomedical Informatics Lab at ASU: http://diego.asu.edu/downloads/download_binary_twitter_data.py](http://diego.asu.edu/downloads/download_binary_twitter_data.py) Replacing the line saying **userid = fields[1]** with **userid = "twitter"** or any other existing Twitter user name.

Alternatively, you can use Twitter API to retrieve the tweets using the ID as described in [the documentation: https://dev.twitter.com/rest/reference/get/statuses/show/%3Aid](https://dev.twitter.com/rest/reference/get/statuses/show/%3Aid)

Our publication can be found at: **TBD** .

If you use any of these data, please cite our publication: **TBD** .