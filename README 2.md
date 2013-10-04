#Price Intelligently#
##Tenets##
1. Dashtastic will offer immediate value, free of charge, to any SaaS Stripe Customer
2. Dashtastic will provide users with a delightful experience that is beautiful and naturally shareable
3. Dashtastic will offer enough features and value that the resource could reasonably used through a leadership team on a consisten basis

###Version 1.0###
* Active customer count (no deltas)
*Current monthly recurring revenue (no deltas)
* Gross new MRR last 30 days (cumulative)
* New customers this month
* Churned customers this month, including % of total
* Churned recurring revenue this month, including % of total
* Last five recently churned customers (a list - datetime churned, gravatar image and email address )
* Quantity - average quantity of â€œseatsâ€ for recurring plans â€¦ probably want to include the max and min quantity as well. â€œAverage team sizeâ€ is very important to us.
* Last five new customers (same kind of list as recently-churned)
* Everything should be logically linked to corresponding resource in Stripe (eg. customer count metric should be an element linked to manage.stripe.com/customers)
* Daily/weekly email with top-level metrics
* Ability to subscribe others to metrics email
* For the email, here is an email i have for a product i made that i really enjoy getting: https://www.evernote.com/shard/s4/sh/7164ffc1-d2e8-4b36-a4f9-1364bc946114/5fb557bfe27d0bfc2977a0cc675ea009 maybe useful for some inspiration, maybe not
* Discount rate

###Milestone: Press Launch###
* Delta stats for all top-level metrics: customer count, churn (mrr %)
* Trial info - # of customers in trials, trial conversion rate last 7 days, 30 days, 90 days
* Top-level metrics broken down by Stripe â€œPlanâ€
* Show images of people in each plan (gravatar) and link them to the customer object in Stripe
* Activity stream, pulling from the event log in the Stripe API

###Other Long Term Ideas (don't do now)###
* ANYthing with data processing, bucketing, group discovery, AI/ML
* Google Analytics integration - we can show key pages and events from GA in the dashboard as well, and we have a proof of concept of how to add more events to customersâ€™ GA accounts by adding javascript mixins we provide.
* ANY other payment providers - letâ€™s hold off on that indefinitely until there is a massive unignorable reason to add Recurly etc.
* Ability to email targeted surveys (our relative value and pricing campaigns, but maybe expand to NPS) and break this data down by cohort.
