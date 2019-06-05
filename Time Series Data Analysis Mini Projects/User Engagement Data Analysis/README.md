#Take Home Challenge Exercise
##Problem: User Engagement Data Analysis
Given a user table with data on 12,000 users who signed up for the product in the last two years and usage summary table that user logged-in hitstory, defining an "adopted user" as a user who has logged into the product on three separate days in at least one sevenday period, identify which factors predict future user adoption.

##Data
A user table ( "takehome_users" ) with the following columns:
name: the user's name
object_id: the user's id
email: email address
creation_source: how their account was created. This takes on one of 5 values:
PERSONAL_PROJECTS: invited to join another user's personal workspace
GUEST_INVITE: invited to an organization as a guest (limited permissions)
ORG_INVITE: invited to an organization (as a full member)
SIGNUP: signed up via the website
SIGNUP_GOOGLE_AUTH: signed up using Google Authentication (using a Google email account for their login id)
creation_time: when they created their account
last_session_creation_time: unix timestamp of last login
opted_in_to_mailing_list: whether they have opted into receiving marketing emails
enabled_for_marketing_drip: whether they are on the regular marketing email drip
org_id: the organization (group of users) they belong to
invited_by_user_id: which user invited them to join (if applicable).
A usage summary table ( "takehome_user_engagement" ) that has a row for each day that a user logged into the product.

##Approach
Apply data wrangling to fix data types and fill missing values and fix outliers if applicable.
Define adopted user using time series analysis techniques.
Analyze features predict future user adoption using logistic regression and ensemble method.


Deliverables
Data wrangling, exploratory data analysis & modeling code in Python notebook.
