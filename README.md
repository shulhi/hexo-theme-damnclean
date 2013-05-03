# DamnClean

This is one damn clean minimalist theme for [Hexo](http://zespia.tw/hexo). Based on Hexo default theme, Light.

Demo is [here](http://shulhi.github.io)

**Note** : This is still in beta, so far it works fine for me. But I haven't fully test it yet with Gallery, or add in picture in post etc. I only tested simple text entry, and code as that is mainly what I need. Feel free to fork and change to your need.

## Install

Execute the following command and modify `theme` in `_config.yml` to `damnclean`.

```
git clone https://github.com/shulhi/hexo-theme-damnclean.git
```

## Update

Execute the following command to update DamnClean.

```
cd themes/damnclean
git pull
```

## Config

Default config:

``` yaml
menu:
  Home: /
  Archives: /archives

widgets:
- search
- category
- tag
- twitter

excerpt_link: Read more

github:
  username: 

twitter:
  username:
  show_replies: false
  tweet_count: 5

addthis:
  enable: true
  pubid:
  facebook: true
  twitter: true
  google: true
  pinterest: true

fancybox: true

google_analytics:
rss:
```

- **menu** - Main navigation menu
- **widget** - Widgets displaying in sidebar
- **excerpt_link** - Display read more link at bottom of post (leave empty to disable)
- **github** - Github follow button
  - **username** - Github username
- **twitter** - Twitter follow button
  - **username** - Twitter username
  - **show_replies** - Enable displaying replies
  - **tweet_count** - Tweets display in widget
- **addthis** - Share buttons at the buttom of articles (Powered by [AddThis])
  - **enable** - Enable share buttons
  - **pubid** - Profile ID of [AddThis]
  - **facebook** - Enable Facebook button
  - **twitter** - Enable Twitter button
  - **google** - Enable Google+ button
  - **pinterest** - Enable Pinterest button
- **fancybox** - Enable [Fancybox]
- **google_analytics** - Google Analytics ID
- **rss** - RSS subscription link (change if using Feedburner)