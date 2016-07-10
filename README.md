# SocialTD

Currently in the United States 1 in 4 teens contract a sexually transmitted disease every year. In 2008, there were an estimated 110 million prevalent STIs among women and men in the U.S. Of these, more than 20% (22.1 million) were among women and men aged 15 to 24 years.

SocialTD is a tool people can use to combat the spread of STDs. SocialTD uses mobile to server encryption to ensure the data isn't seen by any internet onlookers. The app and all of its data is also password protected so it can't be seen by any nearby onlookers.

In the app, users input "encounters" they have had with others. They list what they have done in that encounter, and we determine (via science) how "risky" it is. If they are tested clean, all of the encounters are marked green because they have little to worry about.

If the user finds out they have something, they can choose to notify people they have had encounters with either anonymously or not.
If the user notifies someone anonymously, it will notify the other party via text (twilio) or email that they might have something.

If the user notifies someone non-anonymously, it will notify the other party with a link to the app and a code, which the app will use to figure out which user sent the warning, and it will mark which people need to be notified for the second user.

Users can also upload pictures of their tests so that other users can trust that their partners are clean. Hopefully this can foster a culture of sharing results with others.
