@import url("https://fonts.googleapis.com/css?family=M+PLUS+Rounded+1c:700,900");
body {
  overflow: hidden;
  background-color: rgba(0, 0, 0, 0);
}

yt-live-chat-item-list-renderer #items {
  overflow: hidden !important;
}

yt-live-chat-item-list-renderer #item-scroller {
  overflow: hidden !important;
}

yt-live-chat-header-renderer,
yt-live-chat-message-input-renderer {
  display: none !important;
}

yt-live-chat-text-message-renderer #author-badges {
  display: none !important;
  vertical-align: text-top !important;
}

yt-live-chat-text-message-renderer #timestamp {
  color: #999999 !important;
  font-size: 16px !important;
  line-height: 16px !important;
}

yt-live-chat-text-message-renderer a,
yt-live-chat-legacy-paid-message-renderer a {
  text-decoration: none !important;
}

yt-live-chat-text-message-renderer[is-deleted],
yt-live-chat-legacy-paid-message-renderer[is-deleted] {
  display: none !important;
}

yt-live-chat-ticker-renderer {
  background-color: transparent !important;
  box-shadow: none !important;
}

yt-live-chat-ticker-renderer {
  display: none !important;
}

yt-live-chat-mode-change-message-renderer,
yt-live-chat-viewer-engagement-message-renderer,
yt-live-chat-restricted-participation-renderer {
  display: none !important;
}

yt-live-chat-renderer {
  background-color: transparent !important;
}
yt-live-chat-renderer * {
  font-family: "M PLUS Rounded 1c", sans-serif;
}
yt-live-chat-renderer #author-name {
  font-weight: 900 !important;
}
yt-live-chat-renderer #message {
  font-weight: 700 !important;
}
yt-live-chat-renderer yt-live-chat-text-message-renderer #content,
yt-live-chat-renderer yt-live-chat-text-message-renderer[is-highlighted] #content,
yt-live-chat-renderer yt-live-chat-paid-message-renderer #content,
yt-live-chat-renderer yt-live-chat-legacy-paid-message-renderer #content {
  overflow: visible !important;
}

yt-live-chat-text-message-renderer,
yt-live-chat-text-message-renderer[is-highlighted] {
  margin: 0 0 8px 0;
  padding: 0 8px;
}
yt-live-chat-text-message-renderer #author-photo,
yt-live-chat-text-message-renderer[is-highlighted] #author-photo {
  width: 24px !important;
  height: 24px !important;
  border-radius: 24px !important;
}
yt-live-chat-text-message-renderer #content,
yt-live-chat-text-message-renderer[is-highlighted] #content {
  padding: 8px 16px;
  background: #fff;
  border: 1px solid #c0c4d5;
}
yt-live-chat-text-message-renderer #content #author-name,
yt-live-chat-text-message-renderer[is-highlighted] #content #author-name {
  color: #333 !important;
  font-size: 18px !important;
  line-height: 20px !important;
}
yt-live-chat-text-message-renderer #content #author-name:after,
yt-live-chat-text-message-renderer[is-highlighted] #content #author-name:after {
  content: "\a";
  white-space: pre;
}
yt-live-chat-text-message-renderer #content #message,
yt-live-chat-text-message-renderer[is-highlighted] #content #message {
  display: block;
  margin-top: 4px;
  color: #333 !important;
  font-size: 16px !important;
  line-height: 18px !important;
}
yt-live-chat-text-message-renderer[author-type=owner],
yt-live-chat-text-message-renderer[is-highlighted][author-type=owner] {
  display: flex;
  flex-direction: row-reverse;
  background: none;
}
yt-live-chat-text-message-renderer[author-type=owner] #author-photo,
yt-live-chat-text-message-renderer[is-highlighted][author-type=owner] #author-photo {
  margin-left: 8px;
}
yt-live-chat-text-message-renderer[author-type=owner] #content,
yt-live-chat-text-message-renderer[is-highlighted][author-type=owner] #content {
  position: relative;
  margin: 4px 8px 0 8px;
  border-radius: 16px 0 16px 16px;
  background: #ffd600;
}
yt-live-chat-text-message-renderer[author-type=owner] #content:before,
yt-live-chat-text-message-renderer[is-highlighted][author-type=owner] #content:before {
  content: "";
  position: absolute;
  top: -6px;
  right: -5px;
  border: 5px solid transparent;
  border-bottom: 5px solid #c0c4d5;
  transform: rotate(-45deg);
}
yt-live-chat-text-message-renderer[author-type=owner] #content:after,
yt-live-chat-text-message-renderer[is-highlighted][author-type=owner] #content:after {
  content: "";
  position: absolute;
  top: -5px;
  right: -3px;
  border: 5px solid transparent;
  border-bottom: 5px solid #ffd600;
  transform: rotate(-45deg);
}
yt-live-chat-text-message-renderer[author-type=owner] #content #author-name, yt-live-chat-text-message-renderer[author-type=owner] #content #message,
yt-live-chat-text-message-renderer[is-highlighted][author-type=owner] #content #author-name,
yt-live-chat-text-message-renderer[is-highlighted][author-type=owner] #content #message {
  color: #333 !important;
}
yt-live-chat-text-message-renderer:not([author-type=owner]) #author-photo,
yt-live-chat-text-message-renderer[is-highlighted]:not([author-type=owner]) #author-photo {
  margin-right: 8px;
}
yt-live-chat-text-message-renderer:not([author-type=owner]) #content,
yt-live-chat-text-message-renderer[is-highlighted]:not([author-type=owner]) #content {
  position: relative;
  margin: 4px 8px 0 8px;
  border-radius: 0 16px 16px 16px;
}
yt-live-chat-text-message-renderer:not([author-type=owner]) #content:before,
yt-live-chat-text-message-renderer[is-highlighted]:not([author-type=owner]) #content:before {
  content: "";
  position: absolute;
  top: -6px;
  left: -5px;
  border: 5px solid transparent;
  border-bottom: 5px solid #c0c4d5;
  transform: rotate(45deg);
}
yt-live-chat-text-message-renderer:not([author-type=owner]) #content:after,
yt-live-chat-text-message-renderer[is-highlighted]:not([author-type=owner]) #content:after {
  content: "";
  position: absolute;
  top: -5px;
  left: -3px;
  border: 5px solid transparent;
  border-bottom: 5px solid #fff;
  transform: rotate(45deg);
}
yt-live-chat-text-message-renderer[author-type=moderator] #content,
yt-live-chat-text-message-renderer[is-highlighted][author-type=moderator] #content {
  position: relative;
  margin: 4px 8px 0 8px;
  border-radius: 0 16px 16px 16px;
  background: #5e84f1;
}
yt-live-chat-text-message-renderer[author-type=moderator] #content:before,
yt-live-chat-text-message-renderer[is-highlighted][author-type=moderator] #content:before {
  content: "";
  position: absolute;
  top: -6px;
  left: -5px;
  border: 5px solid transparent;
  border-bottom: 5px solid #c0c4d5;
  transform: rotate(45deg);
}
yt-live-chat-text-message-renderer[author-type=moderator] #content:after,
yt-live-chat-text-message-renderer[is-highlighted][author-type=moderator] #content:after {
  content: "";
  position: absolute;
  top: -5px;
  left: -3px;
  border: 5px solid transparent;
  border-bottom: 5px solid #5e84f1;
  transform: rotate(45deg);
}
yt-live-chat-text-message-renderer[author-type=moderator] #content #author-name, yt-live-chat-text-message-renderer[author-type=moderator] #content #message,
yt-live-chat-text-message-renderer[is-highlighted][author-type=moderator] #content #author-name,
yt-live-chat-text-message-renderer[is-highlighted][author-type=moderator] #content #message {
  color: #fff !important;
}
yt-live-chat-text-message-renderer[author-type=member] #content,
yt-live-chat-text-message-renderer[is-highlighted][author-type=member] #content {
  position: relative;
  margin: 4px 8px 0 8px;
  border-radius: 0 16px 16px 16px;
  background: #0f9d58;
}
yt-live-chat-text-message-renderer[author-type=member] #content:before,
yt-live-chat-text-message-renderer[is-highlighted][author-type=member] #content:before {
  content: "";
  position: absolute;
  top: -6px;
  left: -5px;
  border: 5px solid transparent;
  border-bottom: 5px solid #c0c4d5;
  transform: rotate(45deg);
}
yt-live-chat-text-message-renderer[author-type=member] #content:after,
yt-live-chat-text-message-renderer[is-highlighted][author-type=member] #content:after {
  content: "";
  position: absolute;
  top: -5px;
  left: -3px;
  border: 5px solid transparent;
  border-bottom: 5px solid #0f9d58;
  transform: rotate(45deg);
}
yt-live-chat-text-message-renderer[author-type=member] #content #author-name, yt-live-chat-text-message-renderer[author-type=member] #content #message,
yt-live-chat-text-message-renderer[is-highlighted][author-type=member] #content #author-name,
yt-live-chat-text-message-renderer[is-highlighted][author-type=member] #content #message {
  color: #fff !important;
}

yt-live-chat-paid-message-renderer {
  margin: 8px 0;
  padding: 0;
  box-shadow: none !important;
  text-shadow: -1px -1px 0px rgba(51, 51, 51, 0.7), -1px 0px 0px rgba(51, 51, 51, 0.7), -1px 1px 0px rgba(51, 51, 51, 0.7), 0px -1px 0px rgba(51, 51, 51, 0.7), 0px 0px 0px rgba(51, 51, 51, 0.7), 0px 1px 0px rgba(51, 51, 51, 0.7), 1px -1px 0px rgba(51, 51, 51, 0.7), 1px 0px 0px rgba(51, 51, 51, 0.7), 1px 1px 0px rgba(51, 51, 51, 0.7);
}
yt-live-chat-paid-message-renderer #header {
  padding: 8px;
  border-top-left-radius: 16px !important;
  border-top-right-radius: 16px !important;
}
yt-live-chat-paid-message-renderer #header #author-photo {
  margin-right: 8px;
  width: 40px !important;
  height: 40px !important;
  border-radius: 40px !important;
}
yt-live-chat-paid-message-renderer #header #header-content {
  padding-left: 8px;
}
yt-live-chat-paid-message-renderer #header #header-content #author-name {
  margin-top: 4px;
  font-size: 20px !important;
  line-height: 20px !important;
  color: #fff !important;
}
yt-live-chat-paid-message-renderer #header #header-content #purchase-amount {
  margin-top: 4px;
  font-size: 18px !important;
  line-height: 18px !important;
  color: #fff !important;
}
yt-live-chat-paid-message-renderer #content {
  padding: 0 16px 8px;
  background: transparent;
  border-bottom-left-radius: 16px !important;
  border-bottom-right-radius: 16px !important;
}
yt-live-chat-paid-message-renderer #content #message {
  margin-top: 4px;
  color: #fff !important;
}

yt-live-chat-legacy-paid-message-renderer {
  margin: 8px 0;
  padding: 8px;
  box-shadow: none !important;
  border-radius: 16px !important;
  text-shadow: -1px -1px 0px rgba(51, 51, 51, 0.7), -1px 0px 0px rgba(51, 51, 51, 0.7), -1px 1px 0px rgba(51, 51, 51, 0.7), 0px -1px 0px rgba(51, 51, 51, 0.7), 0px 0px 0px rgba(51, 51, 51, 0.7), 0px 1px 0px rgba(51, 51, 51, 0.7), 1px -1px 0px rgba(51, 51, 51, 0.7), 1px 0px 0px rgba(51, 51, 51, 0.7), 1px 1px 0px rgba(51, 51, 51, 0.7);
}
yt-live-chat-legacy-paid-message-renderer #author-photo {
  margin-right: 8px;
  width: 40px !important;
  height: 40px !important;
  border-radius: 40px !important;
}
yt-live-chat-legacy-paid-message-renderer #content {
  padding: 4px 8px;
  background: transparent;
}
yt-live-chat-legacy-paid-message-renderer #content #event-text {
  font-size: 20px !important;
  line-height: 20px !important;
  color: #fff !important;
}
yt-live-chat-legacy-paid-message-renderer #content #detail-text {
  margin-top: 4px;
  font-size: 18px !important;
  line-height: 18px !important;
  color: #fff !important;
}
