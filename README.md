# RT_10_Tonenchuk
<!DOCTYPE html>
<html>
<head>
<script src="http://code.jquery.com/jquery-latest.js"></script>

<script>
$(document).ready(function () {
   $("button").click(function () {
      var i=1;
      do{
    $(".p2").fadeToggle();
      i++;
   if(i%2==0){
   $(".p1").fadeToggle();}
   }
   while(i<2000)
   $(".p1").hide();
 });
});
</script>

</head>
<body>
<p class="p1"style="display:none">1</p>
<p class="p2" style="display:none">2</p>
<p class="p1"style="display:none">1</p>
<p class="p2" style="display:none">2</p>
<p class="p1"style="display:none">1</p>
<p class="p2" style="display:none">2</p>
<p class="p1"style="display:none">1</p>
<p class="p2" style="display:none">2</p>
<p class="p1"style="display:none">1</p>
<p class="p2" style="display:none">2</p>
<p class="p1"style="display:none">1</p>
<p class="p2" style="display:none">2</p>
</body>
<br><br><button>Появление четных и исчезновение нечетных</button>
</html
