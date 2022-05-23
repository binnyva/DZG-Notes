---
title: "Selection Algorithm - 37% Rule"
tags: ["permanent-notes", "algorithm","problem-solving" ]
date: "2022-05-20 01:44:00"
source: "https://www.youtube.com/watch?v=2VCPmabnBdo"
---

When you want a fast method to select the best option, use this rule.

I'll explain using the example of hiring.

Decide how many total items are there in the pipeline. In the hiring example, say we have 20 candidates.

Examine the first 37% without any intention of selecting those. In example, interview 7 people without hiring them.

Then select the first item that is better than all the previous items. Ie. hire the first person who's better that anyone interviewed so far.

Once you reach 61%, if your best option was in the first 37%, go back to that option and select it. In example, once you reach 12 people, and the best is in the first 7, hire that person.

If you don't know how many items are there in the pipeline, then use the total time available to make the decision. Use 37% of that as the exploration time.

This is a type of problem called the optimal stopping problem. Another category it falls into is the Explore-Exploit Problem.

