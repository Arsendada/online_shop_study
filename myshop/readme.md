To run this site, you need to install all the dependencies from the requirements.txt file,
run redis and celery.
This site provides the ability to place products, add them to the cart,
place orders and pay for them using the stripe service.
The site integrates celery for optimization, as well as redis as a broker and for generating
a list of recommendations for purchases.
The site is localized in 2 languages