---
layout: post
title: Generic
description: Lorem ipsum dolor est
image: assets/images/pic11.jpg
nav-menu: true
---

<script src="http://code.jquery.com/jquery-latest.min.js" type="text/javascript"></script>

<script>
    $(document).ready(function () {
        if (navigator.userAgent.toLowerCase().indexOf("android") > -1) {
            window.location.href = 'market://details?id=<appID>';
        }
        if (navigator.userAgent.toLowerCase().indexOf("iphone") > -1) {
            window.location.href = 'itms-apps://itunes.apple.com/app/<appID>';
        }
    });
</script>
