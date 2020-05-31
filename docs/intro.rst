Introduction
============

At the beginning...
-------------------
It all started when my youngest son picked up introductory computer science
courses at high school. When the Covid-19 crisis and social distancing response
started, I decided to give him some additional help with algorithmics and Python
programming. As a learning exercise, we started a small project to implement a
`Connect Four`_ game in Python. The initial version was a text-based player
versus player implementation. From here, we used Pygame_ to go for a graphics
and sound version, and then a player versus computer version using Minimax_
algorithm... (we'll publish it one day, once we tidy up the source code)

Getting interested in Python and Pygame, I began to write other games to follow
up on this promising path. With `John Horton Conway`_'s untimely passing, I thus
wrote a little `game of life`_ implementation.

The next step was to write a multi-player game...


How to write a multi-player game with Pygame?
---------------------------------------------
Full of hope, I went to the `Pygame group on Facebook`_ and asked if there was
some framework to make multi-players network games with PyGame. To my surprise
the answer seemed to be negative, people using relatively low level network APIs
such as `UDP Communication`_ or `python-socketio`_.

That was not what I was searching for!

Of course, a network API would enable two players, already knowing each other
and having already decided on a playing time, to play some game, but I had more
general things in mind.

I then headed to GitHub to look for games/players lounge/lobby software. I found
some interesting projects (for example, with focus on match making or
blockchain usage) but none exactly fitting my purpose.

So I decided to go for it myself.


The problem I want to tackle
----------------------------
TODO

.. _`Connect Four`: https://en.wikipedia.org/wiki/Connect_Four
.. _Pygame: https://www.pygame.org/
.. _Minimax: https://en.wikipedia.org/wiki/Minimax
.. _`John Horton Conway`: https://en.wikipedia.org/wiki/John_Horton_Conway
.. _`game of life`: https://github.com/HubTou/JeuDeLaVie
.. _`Pygame group on Facebook`: https://www.facebook.com/groups/pygame/
.. _`UDP Communication`: https://wiki.python.org/moin/UdpCommunication
.. _`python-socketio`: https://python-socketio.readthedocs.io/en/latest/
