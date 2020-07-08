# Conversion Rate Predictor
Problem Statement - Build a model to predict conversion rate 
<br> Data utilised - Conversion Rate table
<br>Columns:
<br> 1.country - user country based on the IP address
<br> 2.age - user age. Self-reported at sign-in step.
<br> 3.new_user - whether the user created the account during this session or had already an
account and simply came back to the site
<br> 4.source - marketing channel source
<br>○ Ads - came to the site by clicking on an advertisement
<br>○ Seo - came to the site by clicking on search results
<br>○ Direct - came to the site by directly typing the URL on the browser
<br> 5.total_pages_visited - number of total pages visited during the session. This is a proxy for
time spent on site and engagement during the session.
<br> 6.converted - this is our label. 1 means they converted within the session, 0 means they
left without buying anything. 
<br>The company goal is to increase conversion rate: # conversions / total sessions.
