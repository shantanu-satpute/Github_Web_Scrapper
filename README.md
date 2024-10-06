
# GitHub Web Scrapper
## Project Introduction:

**1**. **Problem statement**:

The objective of this project is to extract and organize information from GitHub's topic pages. GitHub offers a wealth of information on various topics and associated repositories, but manually gathering this data can be time-consuming. The goal is to automate the process of collecting data, organizing it into structured formats, and saving it into CSV files for further analysis or usage.

**2**. **Introduction to Web Scraping and GitHub**:

GitHub is a popular platform for hosting and sharing code repositories, facilitating collaboration and version control. Web scraping involves extracting data from websites, allowing users to gather information in a structured format. In this project, web scraping will be used to extract data from GitHub's topic pages.

**3**. **Tools used**:

1. Python: Backbone of the whole project.

2. Requests: Used to fetch the content of GitHub's topic pages.

3. BeautifulSoup: It helps in navigating and searching through the HTML structure of GitHub pages.

4. Pandas: Use to organize the extracted data into structured formats like CSV files.

**4**. **Useful Links**:

https://github.com/

https://github.com/topics

## Project outline:
1. We are going to scrap : https://github.com/topics

2. We will get a list of topics. For each topic we will get topic title, topic page URL and topic description.

3. For each topic we will get top 20 repositories in the topic from the topic page.

4. For each repositories we will grab the reponame, username(author name), stars and repo URL.

## References:

1. BeautifulSoup Documentation: https://beautiful-soup-4.readthedocs.io/en/latest/

2. Request Documentation: https://pypi.org/project/requests/

3. Pandas Documentation: https://pandas.pydata.org/docs/user_guide/10min.html

## Future Ideas:

1. Develop some functions in the same script to extract the data related to some more topics present on different pages of the same website.

2. Make it more user friendly by asking the topic names to the user itself.

3. Develop some mechanism for real-time data updates by setting up particular frequency.
