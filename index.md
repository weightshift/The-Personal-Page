<!-- swap out for a logo -->
<div id="monogram">
	<img src="monogram.png" />
</div>

<!-- swap out for information about yourself -->
<div id="about">
	<p>Naz Hamid is the founder and principal of <a href="http://weightshift.com">Weightshift</a>, a design studio in San Francisco and Chicago. Aside from client work, projects include the community-oriented site <a href="http://interhoods.org">Interhoods</a> and mobile web application, <a href="http://sitby.us">SitBy.Us</a>. The two projects codenamed <em>Suplex</em> and <em>Sleeperhold</em> are aiming to be launched in 2011.</p>
	<p>He writes about design and tangential topics at <a href="http://weightshift.com/memo">Memo</a>, writes in 140 characters at <a href="http://twitter.com/weightshift">Twitter</a>, posts photos to <a href="http://flickr.com/absenter"/>Flickr</a>, creates 400x300px works-in-progress on <a href="http://dribbble.com/weightshift">Dribbble</a>, sometimes makes moving pictures on <a href="http://vimeo.com/weightshift">Vimeo</a>, records items of interest at <a href="http://svpply.com/weightshift">Svpply</a>, listens to all his music on <a href="http://www.rdio.com/people/weightshift/">Rdio</a> and answers the occasional question on <a href="http://www.quora.com/Naz-Hamid">Quora</a>. He also makes music as <a href="http://murdersandmysteries.com">Murders & Mysteries</a> and released an album in 2010.</p>
	<p>A <a href="http://en.wikipedia.org/wiki/Third_culture_kid">third-culture kid</a>, Naz has lived on three continents and in three countries. He currently lives in San Francisco, California, a place where he feels comfortable in his own skin.</p> 
</div>

<!--include jquery & backstretch-->
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
<script type="text/javascript" src="jquery.backstretch.min.js"></script>
<script type="text/javascript">
$(function(){
     $(window).resize(function(){
         if($(this).width() >= 767){
             $.backstretch("nh_bg.jpg", {speed: 150});//insert image for wallpaper by changing path of "nh_bg.jpg" to whatever the path to your picture is.
         }
      })
      .resize();//trigger resize on page load
});
</script>

