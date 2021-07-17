# Mini-Project-User-Based-Recommendation-System
Mini-Project: User-Based Recommendation System Let’s say we have 6 users, and they have rated 8 different movies on a scale of 1 to 10. Note that not all users have rated all movies. 

UserMovieRatings = { 'Amy': {'Family Plot':10, 'Rebecca':5, 'Spellbound':9, 'Star Trek':6}, 'Bill': {'Apocalypto':8, 'Braveheart':3, 'Rebecca':10, 'Spellbound':5, 'Star Trek':7}, 'Cathy': {'Spaceballs':7, 'The Ice Storm':4, 'Family Plot':5, 'Rebecca':9, 'Spellbound':1}, 'Dave': {'Braveheart':5, 'Rebecca':7, 'Spellbound':4}, 'Ernie': {'Apocalypto':3, 'Braveheart':8, 'Rebecca':1, 'Star Trek':7}, 'Fiona': {'The Ice Storm':3, 'Family Plot':10, 'Rebecca':6, 'Spellbound':10}} 

You can build a simple User-Based Recommendation System as follows: 
• Let’s say you want to make recommendations for UserX 
• Given a UserX, you can find the most similar user or the “nearest neighbor” of UserX by calculating the manhattan distance between UserX and every other user (not including UserX). 
• The person with the smallest manhattan distance is considered the most similar user. Let’s call this person UserXNN. 
• You can now find recommendations for UserX by considering all the movies that UserXNN has rated but that UserX has not.
