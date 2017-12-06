# Gnip Support

## Example simple scripts

*“As a developer wanting to exercise a Twitter Tweet API, I want an example script that I can quickly configure and start making API request, and see the raw output.”*

This repository contains example code that demonstrate the basic API methods available on Twitter Enterpise APIs. These simple scripts can be configured and executed quickly to start working with the API and better understand how it works. These examples are designed to run from the command-line and have no user-interface.

These examples should serve as an example only for the basic API functions, and do not provide additional functionality that will be crucuial to the success of your application (e.g. reconnect logic, batching rule updates, complying with rate limits, validating rules, retrying failed updates, error handling, etc.). 

Examples are avaialble for the following APIs:

+ **Historical APIs**  
  + Search API - Send requests to Twitter Search API
    + Works with enterprise search, both 30-day and full-archive APIs. 
    + Separate examples for POST and GET requests. 
  + Historical PowerTrack API - Create and monitor Historical PowerTrack jobs
  
+ **Real-time PowerTrack**
  + Real-time PowerTrack streaming API - Establish a streaming connection to Twitter PowerTrack and volume streams, using gzip compression
  + Real-time PowerTrack Rules API -Add, Delete, and List rules on PowerTrack real-time streams

### Language coverage

We try to provide examples in as many language as is practical. These examples are first written back in 2012, and were updated for PowerTrack 2.0 in 2016. These examples are mainly in Java, Python, Ruby, C#, and PHP. Next there will likely be examples in node. If you want to share some example code in other languages, please let us know at [https://twittercommunity.com].  

### Other examples

Typically used in-house, often developed as a partner engineering tool. 

Search API examples (these two work with premium and enterprise search APIs):
+ Python search client - https://github.com/twitterdev/twitter_search_api
+ Ruby search client - https://github.com/jimmoffitt/search-tweets-ruby




 
