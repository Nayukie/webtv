# webtv
Make it better

theme for stylish 

Chrome https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?hl=en

FF https://addons.mozilla.org/en-US/firefox/addon/styl-us/

```
@-moz-document url-prefix("http://webtv.jptvpro.net") {
.tvplayer {
    width: 100vw;
    height: 100vh;
    border: 0px;
}
.tv_main {
    width: 100vw;
    height: 100vh;
    background-size: cover;
    background: black;
}
.tv_right {
    width: calc( 100vw - 70px);
    left: 70px;
    z-index: 1;
    top: 45px;
    height: calc( 100vh - 45px);
}
.tv_userinfo,
.tv_userinfo_detail {
    font-size: 12px;
    line-height: normal;
    background-size: contain;
    height: 17px;
}
.tv_left {
    top: 0;
    height: 100%;
    width: 70px;
    z-index: 2;
    background: rgba(0, 0, 0, .80);
    left: 0;
}
.tv_left:hover {
    width: auto;
}
.tv_left .tv_items_container {
    opacity: 0;
}
.tv_left:hover .tv_items_container {
    opacity: 1;
}
.tv_epg_item:hover,
.tv_channel_item:hover,
.tv_nav_item:hover {
    background: #ac1010;
}
.tv_channels_items_wrapper {
    width: 100%;
    height: calc( 100vh - 77px);
    font-size: 22px;
}
.tv_video {
    width: calc(100vw - 70px - 285px);
    border: none;    
    height: calc( 100vh - 100px);
    z-index: 1;
}
.tv_ts_info {
    margin: 0;
}
.tv_video_info  {
    z-index: 1;
}
.tv_ts_info_main {
position: absolute;
    left: 0;
    bottom: 0;
    right: 0;
    height: 50px;
    overflow: hidden;
    z-index: 3000;
    border-top: 1px solid #bf0808;
    background: rgba(0, 0, 0, .73);
}
.tv_ts_info_main:hover {
    height: auto;    
    overflow: visible;
}
@media only screen and (max-width: 1024px) {
    .tv_info {
        top: -37px;
        position: absolute;
        z-index: 1002;
        height: 40px;
        overflow: hidden;
        background: rgba(0, 0, 0, .73);
    }
    .tv_info:hover {
        height: auto;
    }
    .tv_video {
        width: calc(100vw - 80px);        
    }
    .tv_epg_item .epg_time {
        width: 10vw;
    }
    .tv_epg_item .epg_title {
        width: 60vw;
    }
    .tv_ts_info_header .header_item {
        width: 11vw;
    }
    .tv_ts_info_header .header_item,
    .tv_ts_info_header .header_text .day {
        font-size: 12px;
    }
}

}
```
