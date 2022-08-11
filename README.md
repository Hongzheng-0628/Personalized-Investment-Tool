# Personalized Investment Tool

## Introduction
This project aims to develop an App to help users find relevant companies to invest in a specific investment criterion. Other than other existing searches which return millions of results with too much noise, our App provides users with a more personalized experience by offering several filter options and models and returning a small number of high potential companies for users to do investment research on. With this APP, you can better understand your company lists and discover new companies matching your investment profile. 

## Example
#### Google result
When we want to google some fintech related companies, we will probably get results like the picture below.
When we open these links, these web pages only contain some basic information of these fintech companies and some descriptions about the quality of the companies. But it's clear that some professional investors and potential competitors want to see more than that.

<img width="700" alt="123" src="https://user-images.githubusercontent.com/95459565/184057452-69cf8116-bf48-4bce-af64-d32753a6b3e6.png">

#### Our APP result
In our app, when you search for fintech, we use jina neural search framework to display the most relevant companies, and at the same time, we also display company size information (employees + revenue) and company growth data for these companies, We partnered with BrightQuery to obtain this information from government documents. Our clients use company search to enrich the lists of existing companies they are already tracking and to find new companies that are not on their radar.

<img width="700" alt="126" src="https://user-images.githubusercontent.com/95459565/184061223-24d7c3ba-79f0-4f8e-8499-680c8f041fd0.png">
<img width="700" alt="125" src="https://user-images.githubusercontent.com/95459565/184061103-9259b84f-3685-4430-9b74-d535714b2462.png">

## Filter features
Our app also adds some useful filters to make user search results more precise. For example we have a location filter, a company employee count filter and a company revenue filter.



