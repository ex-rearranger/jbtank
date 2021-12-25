---
title: 찾아오시는 길
date: 2021-12-25 21:02:10
updated:
type: map
keywords:
description:
top_img: false
comments:
mathjax:
katex:
aside:
aplayer:
highlight_shrink:
---
<div style="margin-top: -10px;">
<a class="btn-map" target="_blank" rel="noopener" href="https://map.kakao.com/?itemId=8070143&amp;q=중부탱크터미널" title="카카오맵에서 열기"><i class="far fa-hand-point-right"></i> 카카오맵에서 열기</a>
<a class="btn-map" target="_blank" rel="noopener" href="https://map.naver.com/v5/entry/place/17760664" title="네이버 지도에서 열기"><i class="far fa-hand-point-right"></i> 네이버 지도에서 열기</a>
</div>
<div id="map" style="width:100%;height:600px;max-height:50vh;"></div>


<table>
<tbody>
<tr>
<td style="padding: 0; width: 60%;">

![](/img/maps.jpg)</td>
<td style="padding: 20px;font-size: 1.1em">
중부고속도로 음성IC 진출 <br>
-> 광혜원 방향 우회전 1.5Km 직진 <br>
-> 만승교사거리 진천 방향 좌회전 <br>
-> 300m 진행 후 예랑빌라 끼고 우회전 <br>
정면 간판 보고 들어 오시면 됩니다.
</td>
</tr>
</tbody>
</table>






- 주소 : (27811) 충청북도 진천군 광혜원면 월성안길 40
- 전화번호 : 043-535-6530
- 팩스번호 : 043-535-6540
- 이메일 : [jbtk@hanmail.net](mailto:jbtk@hanmail.net)
- 카카오톡 : [중부탱크터미널 (아이디: jbtank)](https://pf.kakao.com/_Sexfbb/chat)




<script type="text/javascript" src="//dapi.kakao.com/v2/maps/sdk.js?appkey=d2d57ee9cff9917887f3630b30650876"></script>
<script>
  var mapContainer = document.getElementById("map"),
  mapOption = {
      center: new kakao.maps.LatLng(36.9778603,127.4442646),
      level: 8
  };
  var map = new kakao.maps.Map(mapContainer, mapOption);
  var marker = new kakao.maps.Marker({
    position : new kakao.maps.LatLng(36.9778603,127.4442646),
    title: "중부탱크터미널",
    clickable: true
  });
  marker.setMap(map);
  var mapTypeControl = new kakao.maps.MapTypeControl();
  map.addControl(mapTypeControl, kakao.maps.ControlPosition.TOPRIGHT);
  var zoomControl = new kakao.maps.ZoomControl();
  map.addControl(zoomControl, kakao.maps.ControlPosition.RIGHT);
</script>

<style>
#article-container .btn-map {
  margin: 0 0 6px;
  padding: 0 15px;
  display: inline-block;  
  background-color: #eee;
  color: #999;
  text-align: center;
  line-height: 2;
  margin-top: 4px;
  -webkit-transition: none;
  -moz-transition: none;
  -o-transition: none;
  -ms-transition: none;
  transition: none;
  overflow-wrap: break-word;
}
#article-container .btn-map:hover {
  background-color: #a2c8f1;
  color: #fff;
}
#article-container .btn-map:active {
  background-color: #ffbfc9;
  color: #fff;
}
</style>