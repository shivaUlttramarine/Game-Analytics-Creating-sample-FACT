# Game-Analytics-Creating-sample-FACT
here I am using GA event logs.
We aim analyzing a small  dynamic of our match-tree Game called "LUXURY EVENTS" to increase ARPU. They are activated every week on Thursdays, including 10 evels.
user can start them and play them during upcoming 7 days. User can Jump out and play normal levels in between, and comes back.

Here I create a fact based on all the related events. I can give us a 360-degree view of Users who are entering that event. 

In next steps, I try to ask questions and get ready to do some analysis on the fact in order to gain some insight, reaching some actionable results.



##################################################

here are how we create the LUX-USER-FACT:

#A) creating below data sets, with granularity of, User_id, level, Week:
1. starting-gem dataset
2. defeat-cnt dataset
3. extra-move-purchase dataset
4. booster-purchase-cnt dataset (in defeat and win situation)
5. evergy-purchased-cnt dataset

#B) joining them all

#C) adding some metrics based on existing Fields like:
    last_energy_cnt 
    enrgey_purchased flag 
    lux_start time
    lux_finish time
    max_level_reached on lux levels
    lux_gem_start
    lux_gem_finish
    avg_lv_dur_min: avg duration time of each Luxury level for each level
    median_lv_dur_min
    last_lv_dur_min: duration of very last level that user played in Lux series. (showing how hard the last level was, which made some gamers quite)
    tot_defeat_cnt
    last_defeat_cnt:  how many times did the gamer lose on last level? (showing how hard the last level of gamed n that serie was)
    moreto come...




D) Asking some Questions to ask from this Data to gain insight
