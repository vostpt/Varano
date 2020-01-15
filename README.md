# Varano
A keyword/hashtag monitoring tool for twitter 

## CONTEXT

Despite the number of social monitoring tools available in the market none of them is free and all of them seem to be focused on the needs of marketeers and social media managers, and none of them really fulfil the needs that a virtual operation support team (VOST) - or a SMEM (Social Media for Emergencies) dedicated account - has in an emergency situation.

## SOLUTION

To develop a tool that has the needs of VOST and SMEM at the centre, as well as focusing on the biggest problem with information online: the validity of that data based on user profile.
In a first phase we'll start with Twitter but future versions should include other social networks (reddit, instagram, facebook, etc.)

## REQUIREMENTS

What is required in this project is an interface that allows for:

- An automatic way to start monitoring by starting a new project. This project should be saved, with all the information collected in a database
- The monitoring of up to 5 hashtags/keywords at the same time on twitter, with granular filtering, making use of Twitter's API and other tools available ([twint] (https://github.com/twintproject/twint/wiki/Basic-usage)?)
- Appending useful metadata to those tweets, by user, such as: 
  - number of followers;
  - number of tweets;
  - account creation date;
  - user predefined location in bio;
  - tweet geolocation.
- An automatic way to stop monitoring and thus ending the project

(More info about requirement #2 and #3 is available at https://github.com/vostpt/varano/issues/1, thanks to @suvl)

## DELIVERABLES

- An interface module that allows to start a new project, stop project, and consult previous projects
- An interface module that shows in real time keyword usage: total since start, last hour, hourly evolution, by location, by device/app
- An interface module that shows users by category (@tomahock will provide specs in order to differentiate types of users)
- An interface module that has a timeline of images being shared with chosen keywords
- An interface module that allows to refine the keywords being searched at any time
- An interface module that maps users by bio-location or geo-location
- An interface module that allows for data, at any time, to be exported dynamically to a .csv or .json file for ArcGIS online integration
- An interface module that allows for a PDF report to be generated of current results
- An interface module that allows for tweets to be sent to a specific account with information regarding the project, with an appended image.

## NOTES

Benchmarks: https://www.brandwatch.com/blog/top-social-media-monitoring-tools/
