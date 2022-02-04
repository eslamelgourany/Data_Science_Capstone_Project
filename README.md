


<center> <p> <img src="https://imagesvc.meredithcorp.io/v3/jumpstartpure/image?url=https://cf-images.us-east-1.prod.boltdns.net/v1/static/1660653193/de3508ea-4f3c-4dc2-967e-698e49ec71db/52b2b6c0-36b7-4398-ab85-24ec67da47b2/640x360/match/image.jpg&w=1280&h=720&q=90&c=cc" alt="Starbucks" class="center" </p> </center>
     

#### Table of Contents

1. [About The Project](#about-the-project)
2. [Project Motivation](#motivation)
3. [Prerequisites](#Prerequisites)
5. [File Descriptions](#File-Structure)
6. [License](#License)
7. [Contact](#Contact)
8. [Acknowledgments](#Acknowledgments)


<!-- ABOUT THE PROJECT -->
## About The Project

The project includes data set that contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

The idea is to get this data, clean it and make analysis to be able to conclude important insights.

<!-- MOTIVATION -->
## Project Motivation <a name="motivation"></a>




<!-- TOOLS -->

## Prerequisites <a name="Prerequisites"></a>

This section list any major frameworks/libraries used to complete the project:

* [Python](https://python.org/)
* [Scikit Learn](https://scikit-learn.org/)
* [Pandas](https://pandas.pydata.org/)
* [NumPy](https://numpy.org/)


<!-- FILE asa -->
## Files Structure <a name="File-Structure"></a>




**profile.json**
*users (17000 users x 5 fields)*
* gender: (categorical) M, F, O, or null
* age: (numeric) missing value encoded as 118
* id: (string/hash)
* became_member_on: (date) format YYYYMMDD
* income: (numeric)


**portfolio.json**

*Offers sent during 30-day test period (10 offers x 6 fields)*
* reward: (numeric) money awarded for the amount spent
* channels: (list) web, email, mobile, social
* difficulty: (numeric) money required to be spent to receive reward
* duration: (numeric) time for offer to be open, in days
* offer_type: (string) bogo, discount, informational
* id: (string/hash)


**transcript.json**

*Event log (306648 events x 4 fields)*

* person: (string/hash)
* event: (string) offer received, offer viewed, transaction, offer completed
* value: (dictionary) different values depending on event type
* offer id: (string/hash) not associated with any "transaction"
* time: (numeric) hours after start of test


<!-- LICENSE -->

## License <a name="License"></a>

Distributed under the MIT License. See `LICENSE.txt` for more information.


<!-- CONTACT -->
## Contact <a name="Contact"></a>

[@Eslam Elgourany](https://www.linkedin.com/in/eslam-elgourany-75b346111) - eslamelgourany@hotmail.com


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments <a name="Acknowledgments"></a>
I find it very helpful and useful to provide such nice data and information to the public.

