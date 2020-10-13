# EIJC2020 - Tracking vessels online with Python

![DataHarvest Logo](https://pbs.twimg.com/profile_banners/1123934898501373952/1594060240/1500x500)

### The idea

There are many websites that allow us to monitor and track vessels online : 

* [MarineTraffic](https://www.marinetraffic.com/)
* [MyshipTracking](https://www.myshiptracking.com/)
* [Fleetmon](https://www.fleetmon.com/)
* [VesselFinder](https://www.vesselfinder.com/)
* ...

Commercial products, most of them provide very useful information for free and tracking vessels online can be done by everyone.
But monitoring can be time consuming, especially during long term surveillance, on several ships...

For example, we, at [OpenFacto](https://openfacto.fr), issued a report concerning [Embargo violations in Libya](https://openfacto.fr/2020/07/03/nouveau-rapport-par-openfacto-turkeys-shadow-arms-deliveries/) in june 2020 and we tracked several vessels night and day for this purpose...

We think that Python can be very interesting for journalists to automatically collect data online, even with beginners in programing.

This repository contains two jupyter notebooks that explain how to scrape the data from a website, by first creating a simple script to do the job on one vessel (Vessel1), and then creating a function from this initial script in order to put it in a simple loop.


### Libraries and prerequisites

We use the following extra libraries for Python3 : 

* Pandas
* BeautifulSoup4
* Requests

As we want the code to remain simple, yet efficient and friendly user, we also use a GoogleSpreadheet but any other online spreadsheet with csv output can be used.

Of course, Jupyter Notebook must be installed on your laptop.

*This said*, If you want to efficientely start coding we recommand you to use a real IDE, a tool to code, such as [VSCodium](https://vscodium.com/).

### Acknowledgments

We want to thank all the crew at DataHarvest for their commitment, their help, their trust. Special Thanks to Adriana Homolova, our moderator on this session!

This session and code is inspired on [BearHunt](https://twitter.com/bearhunt11)'s brilliant work [here](https://medium.com/analytics-vidhya/tracking-ships-and-visualize-them-in-qgis-35c074810937)


![logo OpenFacto](https://openfacto.fr/wp-content/uploads/2019/05/BW-Padded.png)
