# Mapping Success in Women's Basketball: 
##### How to run computer vision code:
In order to run the computer vision code, an account at RoboFlow is needed. The jupyter notebook file contains all necessary information, except API key obtained from a personal account/subscription with RoboFlow.

All necessary packages are included at the top of the notebook file.

While not necessary, Docker Desktop was used to run the API locally as to not interfer with other packages on our personal devices. Instructions for how to start the Docker Desktop is included in the notebook before the relevant cell. Follow application instructions for download and set up. (https://www.docker.com/products/docker-desktop/)

##### How to run regression and exploration notebooks:
This code was created in google colab. Add the combined_data.csv file to the same location as the notebooks, and all code cells will be able to function. 

## Data Access:

In order to access the ESPN data used, use the web_crawl_for_ESPN_data.ipynb. This notebook allows you to use CBBPy in order to scrape data for each women's basketball March Madness game and save it into a CSV file. 

In order to generate the data needed for the computer vision, obtain full game videos or videos that include necessary information for desired project. We used yt-dlp, a command line video downloader, to export the YouTube videos for the March Madness games. (https://github.com/yt-dlp/yt-dlp/releases) (https://www.spacebar.news/yt-dlp-best-way-to-download-videos-audio/) 

Full game videos and frames cannot be posted publicly here. All folders in repository contain partial frames.
