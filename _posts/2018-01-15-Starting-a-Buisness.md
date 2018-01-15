---
title: Starting a Buisness
layout: post
author: joey.bennetts
permalink: /starting-a-buisness/
source-id: 1MOU_RIUPTMqU6UU8Y0Gc3llCepVzUm_NgoDf5Yh-x5A
published: true
---
27/12/2017

Today was the first day of it, we found out that we were starting a spreadsheet that could help at a place like Tescos or Waitrose. The spreadsheet has many functions that could help both a small business as well as a big one to. We started by making a list of item in column "A" and putting the price in column “B”, this would give us a list that we search from. Then we started making our table which would do all the maths for us, we started by creating a “Data Validation” this allow us to find the item (To create the data validation go to,m Data, Data Validation and select the list of items.). Then I did a code called v-lookup which find the item and pairs it with the price, however if there is an error it will show 0, here is the code: =iferror(vlookup(F4, $B:$C,2,false), )    . Next lesson I want to add a total price for it all.

