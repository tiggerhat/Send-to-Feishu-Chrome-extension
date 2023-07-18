# Send-to-Feishu for Google Chrome

[![visitors](https://visitor-badge.glitch.me/badge?page_id=phguo.Send-to-Feishu-Chrome-extension)](https://github.com/phguo/Send-to-Feishu-Chrome-extension) [![Chrome Web Store](https://img.shields.io/chrome-web-store/users/dgblfklicldlbclahclbkeiacpiiancc?color=brightgreen&logo=google-chrome)](https://chrome.google.com/webstore/detail/send-to-Feishu-for-goog/dgblfklicldlbclahclbkeiacpiiancc) [![license: MIT](https://img.shields.io/badge/license-MIT-green)](https://github.com/phguo/Send-to-Feishu-Chrome-extension/blob/master/LICENSE)

<a href="https://www.producthunt.com/posts/send-to-Feishu-a-chrome-extension?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-send&#0045;to&#0045;Feishu&#0045;a&#0045;chrome&#0045;extension" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=338928&theme=light" alt="Send&#0032;to&#0032;Feishu&#0058;&#0032;A&#0032;Chrome&#0032;Extension - Send&#0032;web&#0032;content&#0032;to&#0032;your&#0032;Feishu&#0032;bot&#0032;privately&#0046; | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

__** IT WORKS (UPDATED: 2023-03-03) **__

This is a Chrome extension that allow you to send web content (tab, text, image) to your own "Feishu Bot" using official Feishu API, such that your can sync interesting things across devices, i.e., your phone, your PC, and your laptop. 

This project is an alternative for [Pushbullet](https://www.pushbullet.com/) which stopped release on iOS ([Not Available on iOS : PushBullet](https://www.reddit.com/r/PushBullet/comments/eirc1m/not_available_on_ios/)). Since third party server is not required for this extension, so you do not need to worry about privacy.

This extension can be installed from [Chrome Web Store - Send to Feishu for Google Chrome](https://chrome.google.com/webstore/detail/send-to-Feishu-for-goog/dgblfklicldlbclahclbkeiacpiiancc) (recommended) or the [release page](https://github.com/phguo/Send-to-Feishu-Chrome-extension/releases/latest).

## Getting Start

0. Install "Send to Feishu for Google Chrome" from [Chrome Web Store](https://chrome.google.com/webstore/detail/send-to-Feishu-for-goog/dgblfklicldlbclahclbkeiacpiiancc).
1. Create a Feishu Bot following [Feishu official introduction](https://core.Feishu.org/bots#6-botfather) and get your bot `<API token>`.
2. Get your `<User ID> ` by visiting `https://api.Feishu.org/bot<API token>/getUpdates` after you send arbitrary content to your bot in Feishu APP. The field "id" in the HTTP response is your `<User ID>`.
3. Fill your `<API token>` and `<User ID>` in the extension setting page. If everything is going on smoothly, the setting page will show a green "Saved!" and your bot will send your a massage of "Setting for 'Send-to-Feishu' successfully."

## Usage

You can use this extension intuitively:

- Send **tab** to your bot
  - click on the top right extension icon <img src="https://github.com/phguo/Send-to-Feishu-Chrome-extension/blob/master/feishu.png" alt="Feishu icon" width="15" height="15">.
- Send **text** to your bot
  - select web content and right click -> `Push this selection to Feishu Bot`.
- Send **image** to your bot
  - right click on an image -> `Send to Feishu for Google Chrome`.
- Send **URL** to yout bot
  - right click on a URL -> `Send to Feishu for Google Chrome`.

## Changelog

- [v0.9](https://github.com/phguo/Send-to-Feishu-Chrome-extension/releases/tag/v0.9) - Mar. 31, 2021
  - The first release.

## TODO

- [ ] Open link sent from phone.
- [ ] Add shortcut (suggested by [brucmao](https://www.v2ex.com/t/777006#r_10550028)).
- [ ] Add user interface for sending custom content (suggested by [he110comex](https://www.v2ex.com/t/777006#r_10544806) and [Tgeek](https://www.v2ex.com/t/777006#r_10549271)).
- [ ] Send image file instead of URL (suggested by [jemyzhang](https://www.v2ex.com/t/777006#r_10527353)).
- [ ] Set up API URL manually (suggested by [windyskr](https://www.v2ex.com/t/777006#r_10527433)).
- [ ] Obtain `<API token>` automatically.
- [ ] Open new tab in Chrome when a URL is send to bot from phone.

## License

This project is licensed under the MIT License, see the [LICENSE](https://github.com/phguo/Send-to-Feishu-Chrome-extension/blob/master/LICENSE) file for details.

## Acknowledgments

This project was forked from [rahimnathwani/pushover-for-chrome](https://github.com/rahimnathwani/pushover-for-chrome) for Pushover.
