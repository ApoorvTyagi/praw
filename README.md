# Praw
Change your desktop wallpaper to Reddit's hot🔥 posts of famous subreddit like r/wallpaper, r/naturepics, r/earthporn


I have used the python reddit API wrapper to get the top posts from any random specified subreddits and bloom filters to make sure that wallpapers does not repeat as there might be chances that the program picks the same post again. After downloading and setting the wallpaper it automatically deletes the image from your drive so that it doesn't accumulate and takes your disk space. 

If you want to explore more about bloom filters then here's 👉 the [LINK](https://apoorvtyagi133.blogspot.com/2020/05/bloom-filter.html) to my blog post where i have explained how a bloom filter works in detail.

## Install requirements by running
pip install -r requirements.txt

## How to RUN
First you need to get [PRAW credentials](https://praw.readthedocs.io/en/latest/getting_started/quick_start.html) from Reddit. Then :

<ul>
<li>git clone https://github.com/ApoorvTyagi/praw.git </li>
<li>cd praw <l/i>
<li>python main.py </li>
<ul>
