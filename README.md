# sneakers
   <!DOCTYPE html>
    <html>
    <head>
        <link rel="stylesheet" type="text/css" href="finalcss.css">
        <title>Sneaker Talk</title>
        <script type="text/javascript">
            var slideimages = new Array()
            slideimages[0] = new Image()
            slideimages[0].src = "jordan%20logo%20banner.jpg"
            slideimages[1] = new Image()
            slideimages[1].src = "yeezylogo.jpg"
            slideimages[2] = new Image()
            slideimages[2].src = "puma-banner.jpg"
            slideimages[3] = new Image()
            slideimages[3].src = "justdoit.jpg"
        </script>
        <script>
function validateForm() {
    var x = document.forms["myForm"]["email"].value;
    var atpos = x.indexOf("@");
    var dotpos = x.lastIndexOf(".");
    if (atpos<1 || dotpos<atpos+2 || dotpos+2>=x.length) {
        alert("Not a valid e-mail address");
        return false;
    }
}
</script>
        <script>

window.onscroll = function() {scrollFunction()};

function scrollFunction() {
    if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
        document.getElementById("myBtn").style.display = "block";
    } else {
        document.getElementById("myBtn").style.display = "none";
    }
}


function topFunction() {
    document.body.scrollTop = 0;
    document.documentElement.scrollTop = 0;
}
</script>
        

    </head>
    <body>
        <button onclick="topFunction()" id="myBtn" title="Go to top">Top</button>


            <div id="wrapper">
                <div id="header">
                    <div id="logo">
                        <h1>SneakerTalk.com</h1>
                    </div>
                    <div id="menu">
                        <ul>
                            <li class="first current_page_item"><a href="finalpresentationmain.html">Homepage</a></li>
                            <li><a href="Nike.html">Nike</a></li>
                            <li><a href="Lebron.html">Lebron</a></li>
                            <li><a href="Adidas.html">Adidas</a></li>
                            
                            <li class="last"><a href="Jordan.html">Jordan</a></li>
                        </ul>

                    </div>
                </div>


        </div>

        <div id="body">


        <img src="jordan%20logo%20banner.jpg" id="slide" />
        <script type="text/javascript">
            var step = 0
            function slideit() {
                if (!document.images)
                    return
                document.getElementById('slide').src = slideimages[step].src
                if (step < 3)
                    step++
                else
                    step = 0
                setTimeout("slideit()", 2000)
            }
            slideit()
        </script>


        </div>

        <div id="pages">
            <div id="content">
                 <div class="box">
                     <h1>Welcome to SneakerTalk the home of all Sneaker news!</h1>
                         <p>
                            This website is all about sneakers! Here we break down the history of sneakers as well as the iconic sneakers that sneakerheads love to collect. 
                        </p>
                        </div>
                 <div id="col1" class="box">
                    <h3>History of Sneakers</h3>
                     <ul class="section-list">
                         <li class="first">
                         <img class="alignleft" src="history%20of%20sneaker.jpg" width="60" height="60" alt="" /> <span>The Converse was the first sneaker used for basketball. The Converse was the foundation to the modern sneaker</span></li>
                        <li class="last">
                        <img class="alignleft" src="firstshoe2.jpg" width="60" height="60" alt="" /> <span>Keds manufactured in the early 1900's were the first sneaker ever made.</span></li>
                         </ul>
                        </div>
                <div id="col2" class="box">
                     <p>The craze of collecting sneakers is relatively new. Sneakers, hip-hop, and basketball are intertwined; basketball sneakers are by far the most popular kind of sneakers. Kids came out in droves to buy the sneakers that their favorite NBA players are playing in during games. Michael Jordan's iconic commercials featuring him taking off from the freethrow line are often the memories that people recall when asked when was the first time they wanted sneakers.  </p>
                     <img class="aligntop" src="jumpman-air-jordan-photo-shoot-card.jpg" width="195" height="100" alt="" />
                     <p> Check Out Upcoming Sneaker Releases this month!!</p>
                     <iframe src="https://calendar.google.com/calendar/embed?src=tyronegrant96%40gmail.com&ctz=America/New_York" style="border: 0" width="400" height="500" frameborder="0" scrolling="no"></iframe>
                     

                         
                        </div>

                    </div>
                    <div id="sidebar2">
                        <div class="box">
                            <h3>Some of the Iconic sneaker brands</h3>
                            <p>
                                Some of the most successful brands, have exclusive sneakers that sneakerheads go crazy for. Nike by far is the most successful and popular spawning Jordan and Lebrons which are both highly osught after and billion dollar ventures. Other brands that that sneakerheads love are Adidas, which sell yeezys. Yeezys have all the hype in this point in time .
                            </p>
                            

                            <dl class="list">
                                <dt class="first"><a href="https://www.nike.com">Jordan</a></dt>
                                <dd>-Jordan, the most profitable athlete brand. It has generated billions of dollars for Nike while also being the staple in reselling.</dd>
                                <dt><a href="https://www.nike.com">Nike</a></dt>
                                <dd>-Nike the king of sneakers. No list is complete without this brand. A few of others on this list was spawned from the Nike brand.</dd>
                                <dt><a href="https://www.nike.com">Lebron</a></dt>
                                <dd>-Lebron is the current king of sneakers being the only active athlete on this list.Lebron has also generated billions of dollars in sales with his philantropy and business mind unrivaled. </dd>
                                <dt class="last"><a href="https://www.adidas.com">Adidas</a></dt>
                                <dd>-Adidas is constantly second place in the battle of the brands. Adidas has been a staple in peoples closets for years</dd>

                            </dl>
                        </div>
                        <div class="box">
                            <h3>The Culture</h3>
                            <p> Sneaker collecting has turned into a growing culture. Not only do people collect sneakers, but they also collect clothes such as Bape , Supreme and G-Star. Superstar basketball players and rappers like Dj Khaled, Joe Johnson and The Game have sneaker and clothes collections worth hundreds of thousands of dollars. People line up sometimes 2 or 3 days in advance for sneaker release. Sneakers like Yeezys and OG Jordans have resold for $10,000. The hype has gotten so frantic that people have died over sneaker releases. </p>
                            <form name="myForm" action="/action_page_post.php" onsubmit="return validateForm();" method="post">
                            More Sneaker news? Add email: <input type="text" name="email">
                            <input type="submit" value="Submit">
                            </form>
                            <a href= "abc@gmail.com">Send Inquires to my Email!</a>
                            <table id="table" width="420" height="315" alt="">
                              <tr>
                               <th><img src="the-game-sneakers.jpg" width="200" height="115"/></th>
                               <th><img src="dj%20khaled.jpg" width="200" height="115"/></th>
                              </tr>
                              <tr>
                               <td><img src="gmxexujlsk5qojqeuxwi.jpg" width="200" height="115"/></td>
                               <td><img src="joejo_original.png" width="200" height="115" /></td>
                             </tr>
                            </table>
                        </div>
                    </div>
                    <div id="sidebar1">
                        <div class="box">
                            <h3>Sneakerhead</h3>
                            <p>
                                <iframe width="420" height="315"
    src="https://www.youtube.com/embed/9hxGht9kpgQ">
    </iframe> 
                            </p>
                        </div>

                    </div>

                </div>

            <br class="clearfix" />
        <div id="bottom">
                 SneakerTalk | Designed by Tyrone Grant
            </div>
    </body>
    </html>
