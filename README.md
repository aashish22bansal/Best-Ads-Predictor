# Best-Ads-Predictor
<p>
  <p>
Here, we will be using the concept of Reinforcement Learning. We know that Supervised Learning in which we have the labelled dataset and unsupervised learning which has the unlabelled dataset. Reinforcement Learning is very similar to the way we teach children or pets by giving a positive remark whenever they do something good or obey us properly and we give a negative remark or scold them whenever they do something good. for this, we have two methods:
    <ol>
      <li>Upper Confidence Bound</li>
      <li>Thompson Sampling</li>
    </ol>
  </p>
  <p>
    We know about the problem of Multi-armed Bandit, in which we have some machines in which we put the money and all the machines have some algorithm running in them, and based on the amount of money which we put in them, we get some outcome, for example, a part of money or some chocolates, etc. in which case we win. In this, our goal is maximize the return. Each machine has its own distribution set. Now, initially we will go to each and every machine and we try it out and if we get a high-return, then we send more on that machine. The application of this problem is in the advertisement industry in which we have different ads and we want to which ad has more impact on the user. we can do this on a trial basis and if the user clicks on the ad, then it means that the person is getting impacted by the ad and that ad will give more significance of the product. Suppose we have D arms and, for example, arms are the ads that we display to the user, when they connect to a webpage. Now, each time a user connects to a web page, it makes a Round. At each Round 'n', we choose an ad to display to the user. For each Round n, the ad 'i' gives the reward ri(n)={0,1} (If the user clicks on the ad, then we give it a '1' else we give it a '0'). Our goal is to maximize the total reward.
  </p>
</p>

