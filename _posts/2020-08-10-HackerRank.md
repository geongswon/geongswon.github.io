---
layout:     post
title:      "[HackerRank] Problem Solving (Python)"
date:       2020-08-10 
catalog: true
---

**Simple Array Sum**

{% highlight js %}
def simpleArraySum(ar):
    return sum(ar)
{% endhighlight %}


**Compare the Triplets**

{% highlight js %}
def compareTriplets(a, b):
    score_a = 0
    score_b = 0
    for i in range(len(a)):
        if a[i] > b[i]:
            score_a += 1
        elif a[i] < b [i]:
            score_b += 1
        else:
            i += 1
    return (score_a, score_b)  
{% endhighlight %}


**A Very Big Sum**

{% highlight js %}
def aVeryBigSum(ar):
    sum = 0
    for i in range(len(ar)):
        sum += ar[i]

    return (sum)
{% endhighlight %}

