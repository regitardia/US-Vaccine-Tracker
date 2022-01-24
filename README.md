Introduction

It can be a troubling time, but we do have hope on the horizon, with the news we get daily about vaccines. Multiple companies are releasing and getting their vaccines approved; we may soon see a path forward.

Using the robust toolset provided by Kaggle, I'll show you how to create an interactive map to track, for each state, the percentage of inhabitants that have been vaccinated against COVID-19.

US Vaccine Tracker

We'll use two datasets.

The first dataset has the total number of inhabitants of each state, along with latitude and longitude data for each state's capital city. This dataset is pulled from the 2019 US Census, and I've uploaded it here.

The second dataset contains a recent estimate for the total number of people that have been vaccinated in each state. This vaccine dataset is drawn from Our World In Data, who update their vaccine datasets from the CDC quite regularly. Every time you run this notebook, you'll use the most recent version of their data.

In the next code cell, we load and preprocess the data. As output, you'll see the total percent of the population that has been vaccinated in the US, along with a preview of the Pandas DataFrame that we'll use to make the tracker.
