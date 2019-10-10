@import url('https://fonts.googleapis.com/css?family=Space+Mono');
:root {
  /*  ✨ HIGH CONTRAST COLOR ✨
      change only j-red / j-green / j-blue
  */
  --k-red: 13;
  --k-green: 13;
  --k-blue: 13;

  /*  ✨ AUTO COLORS ✨
      do not touch!
  */
  --k-accessible-color: calc((((var(--k-red) * 299) + (var(--k-green) * 587) + (var(--k-blue) * 114)) - 128000) * -1000);
  --k-color: rgb(var(--k-accessible-color), var(--k-accessible-color), var(--k-accessible-color));
  --k-back: rgb(var(--k-red), var(--k-green), var(--k-blue));
}

li#userspace {
  padding: 9px 4px;
}

li#userspace i.nav-left__item-icon {
  /*background: url(https://i.imgur.com/oajiYl5.png) no-repeat;*/
  background-position: 0px -2px;
  height: 32px;
  text-indent: -999px;
  width: 32px;
}

#room .app-right {
  opacity: 0.86 !important;
}

#room .app-header {
  background-color: rgba(28, 31, 37, 0.86);
  opacity: 0.86 !important;
}

#room .header-panel-bar {
  background: rgba(28, 31, 37, 0.75);
}

#room .history-button {
  background-color: rgba(28, 31, 37, 0.75);
}

#room .plug-menu {
  background-color: rgba(40, 44, 53, 0.94) !important;
}

#room .plug-menu .legal {
  background-color: rgba(68, 74, 89, 0.46) !important;
}

#room .settings {
  background-color: rgba(10, 10, 10, 0.89) !important;
}

#room .settings .header {
  background-color: rgba(28, 31, 37, 0.78) !important;
}

#chat {
  background-color: rgba(10, 10, 10, 0.75);
}

#dj-button {
  background-color: rgba(40, 44, 53, 0.75) !important;
}

#chat .message:nth-child(2n+1),
#chat .mention:nth-child(2n+1),
#chat .skip:nth-child(2n+1),
#chat .moderation:nth-child(2n+1),
#chat .emote:nth-child(2n+1),
#chat .update:nth-child(2n+1),
#chat .welcome:nth-child(2n+1) {
  background-color: rgba(17, 19, 23, 0.32);
}

#chat .mention {
  background-color: rgba(53, 75, 124, 0.22) !important;
  border-left: #ac76ff 3px solid;
  font-weight: 700;
  padding-left: 1px;
}

#chat .update .text {
  color: #00FF4A;
}

#chat-messages {}

#chat-input-field {}

#chat-messages .msg img {
  clear: both;
  display: inherit !important;
}

#chat-messages .msg video {
  display: inherit !important;
}

#chat-messages .timestamp {
  position: absolute;
  right: 5px;
  text-align: right;
  top: 5px;
}

#chat-messages .clickable {
  margin-bottom: 0px;
}

#chat .from {
  display: inline-block;
  float: left;
  margin-bottom: 0px;
  margin-right: 5px;
  position: initial;
  z-index: 2;
}

#chat .emote,
#chat .mention,
#chat .message,
#chat .moderation,
#chat .skip,
#chat .system,
#chat .update,
#chat .welcome {
  min-height: initial;
}

#chat .msg {
  padding: 5px 8px 6px 15px;
}

#chat .msg .from {
  height: 14px;
}

#chat-messages .text {
  display: block;
  padding-left: 0;
  padding-right: 40px;
  position: initial;
  z-index: 1;
}

#chat-messages .text table {
  margin-top: 20px;
  width: 100%;
}

#chat-messages span.text {
  display: block;
}

#chat-messages .userspace-chatalert .text a {
  padding-left: 0px;
  z-index: 3;
}

#chat-messages .from .icon {
  height: 16px;
  top: 0px;
  width: 16px;
}

#chat .fromID-placeholder .un {
  float: left;
  margin-top: -3px;
}

#chat-messages .cm.promo {
  display: none !important;
}

#chat .badge-box {
  border-radius: 0px;
  color: #1C1F25;
  height: 0px;
  width: 0px;
}

#chat-messages .userspace-chatalert .badge-box {
  height: 30px !important;
  position: absolute !important;
  width: 30px !important;
}

#chat-messages .userspace-chatalert {
  display: block;
  float: none !important;
}

#chat-messages .userspace-chatalert span.timestamp {
  column-count: initial;
  display: inline !important;
  position: absolute !important;
  width: auto;
}

#chat-messages .userspace-chatalert .msg {
  padding-left: 40px;
}

#chat-messages .userspace-chatalert .from {
  display: block !important;
  float: none !important;
  padding-left: 5px !important;
}

#chat-messages .userspace-chatalert.senpai .icon {
  /*background: url(https://i.imgur.com/fWkM6c9.png) !important;*/
  background-position: 0 0 !important;
  padding-left: 10px;
}

#chat .badge-box .no-badge .rsshit.sml .badge-box.no-badge {
  background-image: url('') !important;
}

#chat .icon .icon-p3 {
  background-image: url('') !important;
}

#chat .bdg {
  background-image: url('') !important;
}

#footer {
  background-color: rgba(0, 0, 0, 0.5) !important;
}

#footer-user .info {
  background-color: rgba(0, 0, 0, 0.8) !important;
}

#your-next-media .eta.dark-label {
  color: rgba(230, 219, 219, 1) !important;
}

.social-menu .icon-twitter,
.social-menu .icon-facebook {
  opacity: 9;
}

.social-menu .icon-twitter {
  background-image: url('https://i.imgur.com/Mw0Psat.png') !important;
  background-position: 1px 0px;
}

.icon.icon-facebook {
  background-image: url('https://i.imgur.com/VfuvHLu.png') !important;
  background-position: 1px 0px;
}

#user-meta {
  color: #FFF;
}

#user-meta .label {
  color: #FFF;
}

#user-meta .avatar-thumb {
  background-color: rgba(255, 255, 255, 0.1);
}

#user-panel .score {
  background: rgba(28, 31, 37, 0.59);
}

#dj-button.is-locked .left,
#dj-button.is-full .left,
#vote .crowd-response.disabled .bottom {
  background: rgba(68, 74, 89, 0.75);
}

#dj-button.is-quit .left,
#dj-button.is-leave .left,
#playlist-delete-button:hover {
  background: linear-gradient(to bottom, rgba(244, 107, 64, 0.74) 0, rgba(240, 79, 48, 0.75) 100%);
}

#chat .emote,
#chat .mention,
#chat .message {
  -moz-animation: fadein 0.33s;
  -ms-animation: fadein 0.33s;
  -o-animation: fadein 0.33s;
  -webkit-animation: fadein 0.33s;
  animation: fadein 0.33s;
  background-color: #0E0E0F;
}

#chat .message:hover,
#chat .emote:hover,
#chat .update:hover {
  border-left: #FFFFFF 3px solid;
  padding-left: 3px;
  text-decoration: none;
  -moz-transition: 100ms linear 50ms;
  -o-transition: 100ms linear 50ms;
  -webkit-transition: 100ms linear 50ms;
  transition: 100ms linear 50ms;
}

#chat .moderation:hover {
  border-left: #ac76ff 3px solid;
  padding-left: 3px;
  text-decoration: none;
  -moz-transition: 100ms linear 50ms;
  -o-transition: 100ms linear 50ms;
  -webkit-transition: 100ms linear 50ms;
  transition: 100ms linear 50ms;
}

#chat [data-cid|='3560664'].emote {
  background-color: rgba(53, 75, 124, 0.22) !important;
  border-left: #FF9900 3px solid !important;
}

#chat .rsshit.sml.rs-log-song-stats .badge-box,
#chat .rsshit.sml.rs-log-now-playing .badge-box {
  display: none;
}

#chat .rsshit.sml.rs-log-song-stats .from,
#chat .rsshit.sml.rs-log-now-playing .from {
  float: right;
}

#chat .rsshit.sml .badge-box {
  border-radius: 0px;
  color: #1C1F25;
  display: none;
  height: 0px;
  width: 0px;
}

#chat .delete-button {
  font-size: 8px !important;
  padding: 4px;
  text-indent: 9999px;
  top: -12px;
  top: auto;
  white-space: nowrap;
  width: 10px;
}

#volume .slider {
  display: block !important;
}

#chat .delete-button:before {
  bottom: 0;
  content: "x";
  display: inline-block;
  font-size: 12px;
  left: 0;
  position: absolute;
  right: 0;
  text-align: center;
  text-indent: 0px;
  top: 0;
}

#chat-messages .kouhai .text,
#chat-messages .senpai .text {
  padding-right: 0;
}

#chat .rsshit.context .timestamp,
#chat .moderation .timestamp {
  display: none !important;
}

#chat .rsshit.sml.context .msg .text,
#chat .moderation .msg .text {
  margin-left: 0;
}

#chat .moderation .un {
  padding-right: 3px;
}

/*#chat .message:hover .msg, #chat .emote:hover .msg, #chat .update:hover .msg {
     padding: 5px 3px 6px 15px;
     transition: 100ms linear 50ms;
}
*/
/*#chat [data-cid|='3560664'].emote {
     display: none;
}
*/
#chat .rsshit.sml.rs-log-song-stats .badge-box,
#chat .rsshit.sml.rs-log-song-stats .from .timestamp,
#chat .rsshit.sml.rs-log-now-playing .badge-box,
#chat .rsshit.sml.rs-log-now-playing .from .timestamp {
  display: none;
}

#chat .rsshit.sml.rs-log-song-stats .text,
#chat .rsshit.sml.rs-log-now-playing .text {
  color: #F6FF74;
  font-weight: inherit;
}

#chat .from:hover .rcs-user-info {
  display: inline-block;
  z-index: 9999;
}

#chat .rcs-user-info {
  background: #282c35;
  box-shadow: inset 0 0 0 1px #a5dc42;
  display: none;
  left: 100%;
  margin-left: 0;
  padding: 5px 0px;
  position: absolute;
  right: 0;
  text-align: center;
  top: -4px;
  width: 120px;
  z-index: 0;
}

/* The following is a shitty hack that turns off user info under certain conditions due to User Info being displayed oddly when clicking on "user joined" messages. (After some changes on our end.)*/
#chat .rsshit.context .from:after {
  background: transparent;
  bottom: 0;
  content: '';
  left: 0;
  position: absolute;
  right: 0;
  top: 0;
}

#chat [data-cid|='3560664'].emote {
  color: #FF9900 !important;
}

#chat [data-cid|='3560664'].emote .text {
  color: #FFFFFF !important;
  font-style: normal;
  font-weight: bold;
}

[data-cid|="3560664"] .msg .from .icon-chat-manager {
  background-image: url('https://i.imgur.com/DO20H9J.png') !important;
}

.fromID-23146932 i {
  background-image: url(https://i.animemusic.me/i/discord.png);
  background-position: 1px 1px;
  background-size: 16px 16px;
  height: 16px;
  margin-left: 1px;
  width: 16px;
}

.fromID-23146932 .un {
  display: none;
}

.discordUser {
  color: #8C9EFF;
  margin-left: -5px;
}

.emote.fromID-23146932 {
  display: none;
}

div[class*="cid-23146932"] a[href*=".gif"],
div[class*="cid-23146932"] a[href*=".png"],
div[class*="cid-23146932"] a[href*=".jpg"] {
  display: block;
}

a[#],
a[#],
a[#],
a[#],
a[#],
a[#] {
  background: url('https://i.imgur.com/JySnHN1.gif') no-repeat;
  display: inline-block;
  height: 119px;
  text-indent: -1000px;
  width: 161px;
}

/* @-moz-keyframes fadein {
     from {
        opacity: 0;
    }
     to {
        opacity: 1;
    }
}
 @-ms-keyframes fadein {
     from {
        opacity: 0;
    }
     to {
        opacity: 1;
    }
}
 @-o-keyframes fadein {
     from {
        opacity: 0;
    }
     to {
        opacity: 1;
    }
}
 @-webkit-keyframes fadein {
     from {
        opacity: 0;
    }
     to {
        opacity: 1;
    }
}
 @keyframes fadein {
     from {
        opacity: 0;
    }
     to {
        opacity: 1;
    }
}
*/
/* body {
     background-size: 100% auto !important;
     background-attachment: fixed 0px 0px !important
}
*/
#now-playing-media .bar-value {
  display: inline-block;
}

#now-playing-media:hover .bar-value {
  -webkit-animation: ticker infinite linear 25s;
  -moz-animation: ticker infinite linear 25s;
  -ms-animation: ticker infinite linear 25s;
  -o-animation: ticker infinite linear 25s;
  animation: ticker infinite linear 25s;
}

#now-playing-media {
  text-overflow: initial;
}

@keyframes ticker {
  0% {
    -webkit-transform: translate3d(0, 0, 0);
    -moz-transform: translate3d(0, 0, 0);
    -ms-transform: translate3d(0, 0, 0);
    -o-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }

  100% {
    -webkit-transform: translate3d(-100%, 0, 0);
    -moz-transform: translate3d(-100%, 0, 0);
    -ms-transform: translate3d(-100%, 0, 0);
    -o-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
  }
}

#playlist-media-first-item .now-playing {
  background: #56348C !important;
  border-bottom: #9366da !important;
}

#dj-booth {
  background: url('https://i.imgur.com/w5S4r1D.png') no-repeat 30px 135px;
  left: 265px;
}

.room-background {
  left: 0 !important;
}

.room-background i {
  display: none;
}

#app {
  /*
  background-image: url('https://i.imgur.com/zSwp5Hm.jpg');
  background-size: cover !important;
  */
  background: #000;
}

#onesignal-bell-container,
.onesignal-bell-container {
  display: none;
}

#onesignal-popover-container,
.onesignal-popover-container {
  display: none;
}

[data-theme] .left-side-wrapper {
  background-image: none;
}

.community .community__playing-bottom-container {
  max-width: 600px;
}

.p3-eta-timer {
  color: white;
  padding-left: 10px;
}

.p3-eta-span {
  display: none;
}

#dashboard-nudge {
  display: none;
}

.pop-up-tooltip {
  display: none;
  z-index: -1000;
}

.is-wait .btn-no-dj-secondary.btn-no-dj-secondary__bottom {
  background-color: #1ba0ff;
}

.is-leave .btn-no-dj-secondary.btn-no-dj-secondary__bottom {
  background-color: var(--k-back);
  color: var(--k-color);
}

@media (min-width: 768px) {
  .community .room-controls--desktop__item .btn-like.clicked {
    color: #a5dc42 !important;
  }

  .community .room-controls--desktop__item .btn-meh.clicked {
    color: #e74c3c !important;
  }

  .community .room-controls--desktop__item .btn-playlist.clicked {
    color: #ac76ff !important;
  }

}

@media (max-width: 769px) {
  .community .room-controls--desktop__item .btn-like.clicked {
    color: #a5dc42 !important;
  }

  .community .room-controls--desktop__item .btn-meh.clicked {
    color: #e74c3c !important;
  }

  .community .room-controls--desktop__item .btn-playlist.clicked {
    color: #ac76ff !important;
  }

}

.community__playlist--desktop[data-song] .icon-playlist {
  color: #ac76ff !important;
}

/*  🎉 NEW STYLES 🎉
*/
#app span {
  font-family: Space Mono, Hack, monospace;
}

.btn-no-dj-secondary__icon {
  overflow: visible;
}

#app .left-side-wrapper {
  background-size: cover !important;
}

.btn,
.btn:hover,
.community .room-controls--desktop {
  border: 2px solid rgba(255, 255, 255, .3);
}

.community .room-controls--desktop {
  background: var(--k-back);
}
