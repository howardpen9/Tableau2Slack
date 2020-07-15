# **Tableau2Slack**
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)] [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)] [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)]

Tableau2Slack is a Python 3.7 script that utilizes the Tableau Server Client Python library to open a specific view on a Tableau Server (including a Tableau Online server), downloads an image of that view to disk, triggers a Slack Bot to post the image to a specific channel in a Slack workspace, then removes the image from disk.

To learn more about this script [check out the Medium article.](https://github.com/bcrant/Tableau2Slack/blob/master/documentation/Tableau2Slack-MediumArticle.md)  

<img src="/documentation/NinaInAction.png" width=500px>

## Contents  
[Tableau2Slack.py](https://github.com/bcrant/Tableau2Slack/blob/master/Tableau2Slack.py)  
requirements.txt  
.env (example for `dotenv` package. Read virtualenvexample.md)  
LICENSE  
README.md  
1-gettingstarted.md  
2-virtualenvexample.md  
3-cronexample.md  

## Documentation  
1. **[Getting Started](https://github.com/bcrant/Tableau2Slack/blob/master/documentation/1-gettingstarted.md)**  
2. **[Virtual Environment Tutorial](https://github.com/bcrant/Tableau2Slack/blob/master/documentation/2-virtualenvexample.md)**  
&emsp;&emsp;I. &emsp; Intro  
&emsp;&emsp;II.&emsp; `virtualenv` Installation  
&emsp;&emsp;III.&emsp;`virtualenv` Set Up  
&emsp;&emsp;IV.&emsp; Environment Variables Example
3. **[Cron Tutorial](https://github.com/bcrant/Tableau2Slack/blob/master/documentation/3-cronexample.md)**  
&emsp;&emsp;I. &emsp; Intro  
&emsp;&emsp;II.&emsp; Under the Hood  
&emsp;&emsp;III.&emsp;Installation

## Contributing  
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.  

Would love to create adaptations for other data visualization tools like Looker, Domo, and Power BI in the future.  

## License  
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://choosealicense.com/licenses/mit/)  

## Authors
Main authors:  
&emsp;&emsp;Brian Crant < brian@briancrant.com >

Special thanks to [Dylan Yile Wu](https://www.linkedin.com/in/yilewu/) for the inspiration. Even if it not used directly, [his work](https://github.com/DylanYileWu/slack_tableau_dashboard/blob/master/slack_tableau_dashboard.py) with the Tableau REST API heavily influenced the functionality of this project.

Many thanks to [John McDonald](https://www.linkedin.com/in/john-mcdonald-dev) for giving freely of his time and expertise to review drafts of the super duper scintillating documentation in this repository for public consumption. Not all heroes wear capes.
