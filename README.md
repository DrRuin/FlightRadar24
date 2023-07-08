# FlightRadar24 Airport Ratings Analysis

**Disclaimer**: If you intend to use the data collected via the API for commercial purposes, it is required to subscribe to [Flightradar24's Business Plan](https://www.flightradar24.com/premium/). For further details, please refer to [Flightradar24's Terms and Conditions](https://www.flightradar24.com/terms-and-conditions).

## Project Description

Welcome to my first data science project! I've decided to dive into the world of airport ratings and see what we can learn from the data available on FlightRadar24 and Skytrax.

Here's what I did:

- I started with FlightRadar24, where I found a bunch of useful info about airports around the world. But the data I got felt a bit thin, just a list of airport names and their countries.

- So, I rolled up my sleeves and said "Its sherlock time !" . I went beyond the API and manually collected more detailed data, like recent reviews, review dates, ratings, total reviews and more. This was a lot of work, but it really gave the project some life!

- Next, I crunched the numbers to find the best airports by country and the top 100 airports overall. For the top 100, I came up with a weighted logarithmic calculation method that really helped me make sense of the data.

- To make things even more interesting, I brought Skytrax into the mix. They also publish a list of top 100 airports every year based on a global survey. I thought it'd be fun to see how their list compares to FlightRadar24's.

- Comparing the two lists was quite intruiging. About 43% of the airports on FlightRadar24's top 100 list also appeared on Skytrax's top 100. But despite these differences, both lists agreed on one thing: Singapore Changi Airport is the best in the world!

## Libraries

This project utilizes several Python libraries. To install them, use the command:

```bash
pip install warnings pandas requests json folium numpy beautifulsoup4 matplotlib wordcloud
```
