---
layout: post
title: How to prioritise?
truncated_preview: true
excerpt_separator: <!--more-->
---

Prioritisation means deciding what features to build next. It is important as it sets the direction of the product. If you keep building features that create incremental impact, you will keep growing the game.

How to start? First, categorise all the features into three buckets:

1. Business requirement
2. Technical requirement
3. Urgent/live issues

<!--more-->
Business requirements can further be divided into:

1. Big bets: Example - creating a new map in a battle royale game like PUBG. It can take a quarter to build.
2. Small bets: Examples - changing configuration, creating a sale banner, or a login bonus. These take anywhere from 1 to 3 weeks.

## 1. Business Requirement: Start by defining the north star metric (NSM)

### Defining LTV
In games, the north star metric is usually LTV — a function of retention and monetisation.
Improving either, while keeping the other constant, increases LTV.

LTV = how much a user pays each day × lifetime days
For example, if a user pays $0.10 per day and stays for 10 days, the LTV is $1.

When to target retention vs monetisation
1. Between the two, retention is more important. In most cases, focus on improving LTV by improving retention.
2. Focus on monetisation when: Either the game already has industry-level retention. Or, it is bleeding money. Fix monetisation first because lack of revenue can kill the game.

### Bets
Once the NSM is defined, you will have two types of features: 1) Big bets and 2) Small bets. Allocate 40% of the resources to big bets as it generate huge upside and 30% to small bets. Business requirements should consume a total of 70% of all engineering resources.

## 2. Technical debts
If a technical fix helps improve NSM, it is not a debt. It is a bet. Example: Improving the loading of the game which can improve onboarding, retention and thus LTV. 

If a technical debt blocks gameplay or hurts user experience, fix it immediately.

If it does not impact gameplay, move it to the backlog and priortise. Around 20% of your team resources should go into fixing such issues. Small fixes go a long way — users notice and stay longer, which improves LTV.

## 3. Urgent requirements
here will always be some unavoidable requests — such as:

1. Fixing a server crash 
2. Changing a config
3. Fixing a user issue
4. Adding event to track data
5. Handling compliance

These may not directly impact LTV but are important to fix. Ten percent of the resources should go to fixing urgent requirements.

## How to prioritise?
For all bets, prioritise using the following KPIs: Retention, Monetisation, and Effort.

Assign each item a value — Low, Medium, or High. All value should be based on estimate. 

Final score = (Retention × Monetisation) / Effort

Pick the top scorers. Refresh this list every month.

### How to say no to a request?
From time to time, you will receive requests from senior authority. In the absence of your roadmap or feature list, they may assume their suggestion creates more impact.

Steps to handle this:

1. Create a prioritisation score.
2. Show the scores of existing items and how adding this request could delay more impactful features.
3. If they still want to go ahead, build it. Their wisdom might not be visible on paper.


