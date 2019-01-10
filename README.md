# Data Science Onboarding
Get started with Open Industrial Data!

**January 2018**

The `OID.ipynb` notebook is plagiarized shamelessly from the wonderful SDK examples (see [here](https://github.com/cognitedata/cognite-sdk-python/blob/master/examples/basics/Learn%20to%20use%20CDP.ipynb)).
Let's use this as a jumping board into the Open Industrial Dataset!

Pick an equipment, load and examine the P&IDs and or asset hierarchy to find relevant sensors. Create a notebook that visualizes the sensor data to tell a story about the operation of the equipment and merge it back into this repo.

<hr>

### Setup: Set up your environment (Ask for HELP!)
- Set up your development environment according to [python at Cognite](https://cognitedata.atlassian.net/wiki/spaces/COG/pages/25788445/Python+at+Cognite) (pdf included in case you cannot access Confluence)
- Clone down this repo and switch to a new branch (`<github handle>/onboarding-01`)
- Build the environment from the Pipfile (`pipenv install --dev`)
- If you haven't yet, get yourself an API key from http://openindustrialdata.com/. Drop the key into your .env file, and keep the .env file off of git!
- Start up your notebook server (`pipenv run jupyter`)
- *Help out your colleagues to get everyone to this point!*

### Goal 1: Explore industrial data using CDP
- Take OpInt for a spin, starting from the infographic view presented (https://publicdata.opint.cogniteapp.com/infographics/-LOHKEJPLvt0eRIZu8mE).
- OpInt is great, but think of all the analysis we could do with the data in notebooks! Enter the Cognite SDK! Start working through the `OID.ipynb` notebook, run it, adapt it, explore it! Pay particular attention to how information is organized in CDP: this is your bread and butter when working on use cases!
- Create your own notebook `./201801/<github handle> - <analysis name>.ipynb` and look into the data for the same, or even better, a different equipment! Borrowing from other notebooks is encouraged, but do try and keep things tidy from the start.
- Load up P&IDs and try and decipher them together! Ask your friendly subject matter expert for help.
- *Help your colleagues to get to this point!*
- The rest is open ended! See additional inspiration below.

### Goal 2: Ongoing collaboration
- As soon as possible get your notebook (`./201801/<github handle> - <analysis name>.ipynb`) up on your own branch (`<github handle>/onboarding-01`) on github.com
- Push your code up frequently so that your colleagues can borrow ideas! Open a PR and label it WIP while you continue to work on it. Here's an [example PR](https://github.com/cognitedata/ds-onboarding/pull/1).
- *Help your colleagues to get to this point!*
- At the end of your analysis, neaten up your notebook, and get that PR reviewed by a colleague and merged!

<hr> 

### Notes:
*Help your colleagues to get to this point!* was mentioned 3 times, it's important! We have mixed competencies in Data Science and can do a lot more together!

Additional notebook inspiration:
- For more examples of accessing and analyzing OID see
the [publicdata repo](https://github.com/cognitedata/publicdata)
- For examples of analysis see the
[ml-stories repo](https://github.com/cognitedata/ml-stories)
