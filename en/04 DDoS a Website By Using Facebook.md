# Some Basic Facebook "Hacks" - Hack no. 4: DDoS a Website By Using Facebook

So, today I'm going to share with you a trick to DDoS a certain website by using Facebook's notes feature. The process, although pretty simple, is a bit more complicated than previous posts I wrote in this series.

So, what do you need to do?

Well, first of all, you go to the target's website and create a list with unique photos posted on that website. You put them in appropriate HTML tag like this:

    <img src="http://targetname/file?r=1" />
    <img src="http://targetname/file?r=2" />
    ...
    <img src="http://targetname/file?r=1000" />

The next thing you need to do is to write a note on [m.facebook.com](http://m.facebook.com/) (it's a mobile version of Facebook).

Now, you need to duplicate that note a couple of times with one *or* several other Facebook accounts.

After you've done that, all you need to do is to open that notes at the same time and watch the site go down. This process will generate thousands of HTTP requests in a couple of seconds to the target site.
