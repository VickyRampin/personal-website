[![forthebadge](http://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](http://forthebadge.com)
[![forthebadge](http://forthebadge.com/images/badges/contains-cat-gifs.svg)](http://forthebadge.com)

### About
My website, [vickysteeves.com](http://vickysteeves.com), upgraded from coding-by-hand (n00b) to [Nikola](https://getnikola.com/), a static site generator.

### Building
This site relies on Python and [Nikola](https://getnikola.com/), a static site generator.

I would recommend you use a virtualenv to build and view this website. This is a Python tool to create isolated Python environments. The HitchHiker's Guide to Python has a [great guide](http://docs.python-guide.org/en/latest/dev/virtualenvs/) on virtual environments that I used to learn how to use/interact with virtualenvs. 

Here's how to make and activate a virtual environment:
<pre><code># install the tool virtualenv
$ pip install virtualenv

# create the Python 3 virtual environment
$ virtualenv -p python3 my-website

# activate the virtual environment
$ source my-website/bin/activate
</pre></code>

Now, you can get started and install all of the dependecies of my website!

<pre><code># install the dependencies
$ pip install Nikola['extras']

# clone this repo
$ git clone git@gitlab.com:VickySteeves/personal-website.git

# change directory (cd) so you are in the right folder for the website
$ cd personal-website

# build the website
$ nikola build

# see the website
$ nikola serve -b
</pre></code>

You should now be able to see and interact with my website locally!

### RSS Feed
Found here: [http://vickysteeves.com/rss.xml](http://vickysteeves.com/rss.xml)
