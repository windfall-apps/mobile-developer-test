Hi!

This is an off-site test for the Flutter Mobile Engineer position at Lukky.

# Context

With the Lukky mobile app, our users connect to their Instagram so we can interact with their posts.

From their feed, users can easily import or draw a contest.

You can find examples of publication and contest data models in the `assets/datasets` folder.

# Exercise

One of our mostly used widget allows users to see their feed and start a contest draw from the 
publication in 1 tap.

Based on a set of contests and a set of publications, you will have to check if a publication 
match a contest to decide which screen to navigate to:

- No contests matches the publication: navigate to "New contest draw" screen
- A contest match the publication: navigate to "Contest details" screen

We prepared a Figma so you can see the UI and get the design system details at this URL 
https://www.figma.com/file/KnvjDIeWeLW3SOA0tlWddH/Lukky-Mobile-Engineer-test?node-id=0%3A1.
Required assets (fonts & images) are part of this repository.

Mock datasets are available in the `assets/datasets` folder and represents successful API responses:

- The `contests.json` file contains a collection of existing contests for the current user
- The `publications.json` file contains the collection of publications from the Instagram feed of 
  the current user
  
# Rules

1. You can use any package you want
2. You can use any architecture you want (we mainly use BLoC)
3. If you feel something needs to be clarified, please open an issue with your question

# What we pay attention to

- Cleanliness & structure of the code
- Respect of KISS and DRY principles
- UI integration 
- Use of git

# How to

1. Fork the repo
2. Do the exercise
3. Ping us when you're done with your fork
4. We will contact you to discuss your solution