### Downloads the following tumblr post types

1. Photos
2. Videos

### Setting up

Install python's requests library
`pip install requests`

Replace `API_KEY` with your own API key, tumblr's embedded API key included for demonstration purposes

`DOWNLOAD_RAW` set to False by default. [Read this](https://e621.net/wiki/show/howto:sites_and_sources#tumblr) for information on tumblr's raw photos

### How to use

Open command line in the same folder as the python script

Run it using

`python dl_tumblr_post.py {TUMBLR_POST_URL}`

Works for both python 2 and 3
