<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="w3.css">
<style>
div {Font-Family:"PSL Kanda ExtraSP";Font-Size:20pt;}
a {Font-Family:"PSL Kanda ExtraSP";Font-Size:20pt;}
p{Font-Family:"PSL Kanda ExtraSP";Font-Size:20pt;}
h3 {Font-Family:"PSL Kanda ExtraSP";Font-Size:20pt;}
</style>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-wide w3-padding w3-card-2">
    <a href="#home" class="w3-bar-item w3-button"><b>ชื่อเรื่อง</b> </a>
	<a href="#project" class="w3-bar-item w3-button w3-right w3-hide-small">เกี่ยวกับเรา</a>
	<a href="#project" class="w3-bar-item w3-button w3-right w3-hide-small">แผนที่</a>
	<a href="#project" class="w3-bar-item w3-button w3-right">หน้าแรก</a>
    </div>
  </div>
</div>

<!-- Header -->
<header class="w3-display-container w3-center w3-content w3-wide" style="max-width:1500px;" id="home">
   <img class="w3-image" src="g11.jpg" alt="Architecture" width="1500" height="1500">
</header>

<!-- Page content -->
<div class="w3-content w3-padding" style="max-width:1564px">

  <!-- Project Section -->
  <div class="w3-container w3-padding-32" id="projects">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">กิจกรรม</h3>
  </div>

  <div class="w3-row-padding">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container w3-hover-shadow">
        <div class="w3-display-topleft w3-black w3-padding">จุดชมวิวบนเขา</div>
        <img src="g9.jpg" alt="House" style="width:100%">
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container w3-hover-shadow">
        <div class="w3-display-topleft w3-black w3-padding">สระน้ำ</div>
        <img src="g2.jpg" alt="House" style="width:100%">
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container w3-hover-shadow">
        <div class="w3-display-topleft w3-black w3-padding">สวนน้ำ</div>
        <img src="g3.jpg" alt="House" style="width:100%">
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container w3-hover-shadow">
        <div class="w3-display-topleft w3-black w3-padding">กระเช้าลอยฟ้า</div>
        <img src="g4.jpg" alt="House" style="width:100%">
      </div>
    </div>
  </div>

  <div class="w3-row-padding">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container w3-hover-shadow">
        <div class="w3-display-topleft w3-black w3-padding">แหล่งศึกษาเรียนรู้</div>
        <img src="g5.jpg" alt="House" style="width:100%">
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container w3-hover-shadow">
        <div class="w3-display-topleft w3-black w3-padding ">ออกกำลังกาย</div>
        <img src="g6.jpg" alt="House" style="width:100%">
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container w3-hover-shadow">
        <div class="w3-display-topleft w3-black w3-padding">ร้านอาหาร</div>
        <img src="g7.jpg" alt="House" style="width:100%">
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container w3-hover-shadow">
        <div class="w3-display-topleft w3-black w3-padding">ของที่ระลึก</div>
        <img src="g8.jpg" alt="House" style="width:99%">
      </div>
    </div>
  </div>

  <!-- About Section -->
  <div class="w3-container w3-padding-32" id="about">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">ประวัติของสวนสาธารณะหาดใหญ่</h3>
    <p>ค่อยใส่นะ
    </p>
  </div>

  

  <!-- Contact Section -->
  <div class="w3-container w3-padding-32" id="contact">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">แสดงความคิดเห็น</h3>
    <p>ขอบคุณสำหรับความคิดเห็นทุกข้อความนะคะ </p>
    <form action="/action_page.php" target="_blank">
      <input class="w3-input" type="text" placeholder="ชื่อ" required name="Name">
      <input class="w3-input w3-section" type="text" placeholder="Email" required name="Email">
      <input class="w3-input w3-section" type="text" placeholder="แสดงความคิดเห็น" required name="Comment">
      <button class="w3-button w3-black w3-section" type="submit">
        <i class="fa fa-paper-plane"></i> ส่งข้อความ
      </button>
    </form>
  </div>
  
<!-- End page content -->
</div>

<!-- Google Map -->
<div id="googleMap" class="w3-grayscale" style="width:100%;height:450px;"></div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-16">
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>

<!-- Add Google Maps -->
<script>
function myMap()
{
  myCenter=new google.maps.LatLng(41.878114, -87.629798);
  var mapOptions= {
    center:myCenter,
    zoom:12, scrollwheel: false, draggable: false,
    mapTypeId:google.maps.MapTypeId.ROADMAP
  };
  var map=new google.maps.Map(document.getElementById("googleMap"),mapOptions);

  var marker = new google.maps.Marker({
    position: myCenter,
  });
  marker.setMap(map);
}
</script>
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyBu-916DdpKAjTmJNIgngS6HL_kDIKU0aU&callback=myMap"></script>
<!--
To use this code on your website, get a free API key from Google.
Read more at: https://www.w3schools.com/graphics/google_maps_basic.asp
-->

</body>
</html>
