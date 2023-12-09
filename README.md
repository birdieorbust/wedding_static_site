# Static Wedding Site

A static site I built in 2024 for guests of our wedding to get more information on the days events and where to stay.

Thank you to [Nathan Orick](https://github.com/cnorick) for building this Jekyll template which was very customisable and did exactly as I wanted.

## Learnings

* Not being that familiar with Jekyll templates and having to overwrite the JS to get the web form to capture the details I wanted. Same goes with updating the scss files to get the styling I wanted. My repo has this hybrid approach where it gets what it needs from the theme but then has it's own _webpack files. I'm not used to npm so I found running that tricky at first.
* Hosting on Github pages and setting up a custom domain. It didn't play ball and I had difficultly getting HTTPS to auto work.
* Utilising the themes template RSVP form submit to record data to a google sheet. Had CORS issues with Google Appscript not allowing complex "JSON" header POST requests. 