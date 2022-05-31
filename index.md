<html>
    
<head>
        <title>new tab</title>
        <link rel="stylesheet" href="new.css">

    </head>
    <body>
      <div class="clock-box">

        

        <div id="clockbox"></div>

        <script type="text/javascript">
        function GetClock(){
        var d=new Date();
        var nhour=d.getHours(),nmin=d.getMinutes(),nsec=d.getSeconds();
        if(nmin<=9) nmin="0"+nmin;
        if(nsec<=9) nsec="0"+nsec;
        
        var clocktext=""+nhour+":"+nmin+":"+nsec+"";
        document.getElementById('clockbox').innerHTML=clocktext;
        }
        
        GetClock();
        setInterval(GetClock,1000);
        </script>
        

        <div id="datebox"></div>

<script type="text/javascript">
var tday=["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday"];
var tmonth=["January","February","March","April","May","June","July","August","September","October","November","December"];

function GetClock(){
var d=new Date();
var nday=d.getDay(),nmonth=d.getMonth(),ndate=d.getDate(),nyear=d.getFullYear();

var clocktext=""+tday[nday]+", "+tmonth[nmonth]+" "+ndate+", "+nyear+"";
document.getElementById('datebox').innerHTML=clocktext;
}

GetClock();
setInterval(GetClock,1000);
</script>



      </div>
     
      <img src="night-train.gif" alt="anime girl">


        <nav>
            <ul>
              <li><a href="https://www.youtube.com/">Youtube</a></li>
              <li><a href="https://www.twitch.tv/">Twitch</a></li>
              <li><a href="https://www.nexusmods.com/">Nexus Mods</a></li>          
             </ul>
        
            <ul>
              <li><a href="https://www.4chan.org/">4chan</a></li>
              <li><a href="https://boards.4channel.org/w/">Anime Papes</a></li>
              <li><a href="https://boards.4channel.org/vg/">Bideo Games</a></li>
              <li><a href="https://boards.4channel.org/g/">COMPUTER</a></li>
              <li><a href="https://boards.4chan.org/wg/">All Papes</a></li>
            </ul>
        
            <ul>
              <li><a href="https://1337x.to/home/">1337</a></li>
              <li><a href="https://thepiratebay.org/">The Pirate Bay</a></li>
              <li><a href="https://www.skidrowreloaded.com/">Skidrow</a></li>
              <li><a href="https://www.amazon.com/">Amazon</a></li>
              <li><a href="https://www.ebay.com/">Ebay</a></li>
            </ul>

            <ul>
              <li><a href="https://nyaa.si/">Nyaa</a></li>
              <li><a href="https://netflix.com/">Netflix</a></li>
              <li><a href="https://www.amazon.com/Amazon-Video/b?ie=UTF8&node=2858778011">Prime Video</a></li>
              <li><a href="https://goodsites.tech/">/g/'s Good Sites</a></li>
              <li><a href="https://alpha.wallhaven.cc/">Wall Haven</a></li>
            </ul>

            

          </nav>
          <form autocomplete="off" action="https://google.com/" method="GET" target="_blank">
            <input autofocus
                   name="q"
                   type="search"
                   placeholder=""
                    tabindex="1">
          </form>
    </body>

</html>
![night-train](https://user-images.githubusercontent.com/77655181/171078475-49c18ece-dbde-4535-8fac-59822899c4da.gif)
