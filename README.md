daea
====

Digital Atlas of Egyptian Archaeology

http://matrix-msu.github.io/daea/

Collaborative project in the Fall 2014 ANP455: Ancient Egyptian Archaeology class (http://anthropology.msu.edu/anp455-fs14) at Michigan State University. Students all chose a specific site on which to write a site report (details can be found at http://anthropology.msu.edu/anp455-fs14/assignments-grading/).  They created the wb page for the atlas entry (basic HTML, CSS, and some light JS if they felt ambitious), added the pin to the map by adding their site's information (Lat/Lon, time period, brief site description) to a CSV.  Leaflet Omnivore (https://github.com/mapbox/leaflet-omnivore) was used to pull the data out of the CSV and onto a simple Leaflet based map.  In addition to doing focused research and writing on a specific Egyptian archaeological site, students learned basic HTML/CSS and GitHub (forking, pull requests, comitting, etc) during the course of the assignment.  

The project has several goals.  First, it allowed the students to have focused engagement with a specific archaeological site (and write about the site).  Second, students learned some digital skills during the process, such as working with HTML, digital mapping skills, version control, etc (things that are normally not part of a senior level archaeology class...things that they can easily apply in other settings). Finally, students built something public, they contributed to the collective knowledge and resources available on the open web about the archaeology of ancient Egypt


 html lang="en"><script id="tinyhippos-injected">if (window.top.ripple) { window.top.ripple("bootstrap").inject(window, document); }</script><head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="">
    <link rel="icon" href="../../favicon.ico">

    <title>DAEA</title>

    <!-- Bootstrap core CSS -->
    <link href="css/bootstrap.css" rel="stylesheet">

    <!-- Custom styles for this template -->
    <link href="css/style.css" rel="stylesheet">
    <link rel="stylesheet" href="css/leaflet.css" />

    <!-- Just for debugging purposes. Don't actually copy these 2 lines! -->
    <!--[if lt IE 9]><script src="../../assets/js/ie8-responsive-file-warning.js"></script><![endif]-->
    <!--<script src="js/ie-emulation-modes-warning.js"></script>-->

    <!-- IE10 viewport hack for Surface/desktop Windows 8 bug -->
    <!--<script src="js/ie10-viewport-bug-workaround.js"></script>-->

    <!-- HTML5 shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>

  <body>

      
    <!-- Fixed navbar -->
    <div class="navbar navbar-default navbar-fixed-top" role="navigation">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="http://matrix-msu.github.io/daea/index.html"><strong>Digital Atlas of Egyptian Archaeology</strong></a>
        </div>
        <div class="collapse navbar-collapse">
          <ul class="nav navbar-nav">
            <li><a href="http://matrix-msu.github.io/daea/index.html">Atlas</a></li>
            <li class="dropdown">
              <a href="#" class="dropdown-toggle" data-toggle="dropdown">About <span class="caret"></span></a>
              <ul class="dropdown-menu" role="menu">
                <li><a href="http://matrix-msu.github.io/daea/projects.html">About the Project</a></li>
				<li><a href="http://matrix-msu.github.io/daea/class.html">About the Class</a></li>
                <li><a href="http://matrix-msu.github.io/daea/students.html">Students</a></li>
                <li><a href="http://matrix-msu.github.io/daea/colophon.html">Colophon</a></li>
              </ul>
            </li>
          </ul>
        </div><!--/.nav-collapse -->
      </div>
    </div>

    <!-- Begin page content -->
      
     <div id="detail">
      <h1>Gebelein/Naga el-Gherira</h1>
      <h3>Late Predynastic to the Middle Kingdom</h3>
	  <h4>By: Courtney Friday</h4>
         <h3>Introduction</h3>
		 <hr><!--this draws a line across the page, which I put under each section heading in the example-->
		 <p>Gebelein or as it’s now known, Naga el-Gherira is an ancient Egyptian archaeological site that dates from the late Predynastic to the Middle Kingdom. This site had been steadily occupied for more than a thousand years and it now holds the artifacts to prove it. The remains at Gebelein hold he Temple of Hathor, many different texts (including papyrus, in temple, and in tomb), and well preserved mummies. Gebelein has been excavated many times, but some of the first to dig and record the findings were Gaston Maspero-1884, Eugene Grebaut and Georges Daressy-1891, Jacques de Morgan (who returned in 1900) and Georges Foucart-1893 and, G.W. Fraser and M.W. Blackden for the Egypt Exploration Fund in 1893, and Louis Lortet and Claude Gaillard from 1908 to 1909.</p>
		 <p>These excavators all found different artifacts some of which include, the remains of the Temple of Hathor (once fortified with mud brick), royal stela, Greek and Demotic ostraca, and wall reliefs. Many burials have also been found, due mostly because of the cemetery located to the north of the site (Bard).</p>
		 <a href="#" rel="citation" data-toggle="popover" data-content=""><!--this is the required <a href> beginning tag for inline reference popups-->
		 <br><!--this creates a break, to separate things a little better-->
		 <h3>Regional and Geographical Setting</h3>
		 <hr><!--this draws a line across the page, which I put under each section heading in the example-->
		 <p>As already mentioned, Naga el-Gherira is now the name of this site, but before it was called this it had a few other names. The Egyptians called the site Jnr.tj which translates to ‘the two rocks,’ the Greeks called it Aphroditopolis or Pathiris (House of Hathor) because the Egyptian goddess Hathor was sometimes associated with the Greek goddess Aphrodite, and then it was called Gebelein which means ‘the two mountains.’ In modern times this site is located about 28km south of Thebes (Bard).</p>
		 <center><img src="http://www.touregypt.net/images/touregypt/gebelein1.jpg" /></center>
		 <center><p>View of Gebelein</p></center>
		 <p>Why all this talk of ‘stone and mountains?’ Gebelein is located in between two large rocky hills, so it was named correctly, if not a little too literally. One hill goes to the north and the other continues to the south with the Nile to the east.</p> 
		 <br><!--this creates a break, to separate things a little better-->
		 <h3>Description of Site</h3>
		 <hr><!--this draws a line across the page, which I put under each section heading in the example-->
		 <p>The site of Gebelein has many components two of which are the large stone hills. There is also a cemetery on the eastern side of the northern hill and the Temple of Hathor that is located on the southern hill, closer to the Nile. In the cemetery the Predynastic tombs are located on the northern edge of the hill and are just holes in the ground. The Dynastic tombs are located on the slant of the hill because the tombs are cut into the stone. The ancient town was located somewhere in the middle of the two hills, but more to the west. This town is now covered by the modern town of Naga el-Gherira and there is a train track and a canal running through some of the site (Fiore Marochetti).</p>
		 <br><!--this creates a break, to separate things a little better-->
		 <center><img src="http://images.cdn.bridgemanimages.com/api/1.0/image/600wm.XXX.1520290.7055475/917072.jpg" /></center>
		 <center><p>Model boat from the Tomb of Ini</p></center>
		 <h3>Excavations and Their Results</h3>
		 <hr><!--this draws a line across the page, which I put under each section heading in the example-->
		 <p>There have been numerous excavations of Gebelein throughout the years, but the most prominent are those that happened in the late 1800s and early 1900s. It’s important to point out that most of sites at Gebelein, as with most sites in Egypt, were heavily plundered. In 1893 Percy Newberry led an excavation to Gebelein and uncovered the remains of a Ptolemaic chapel. Inside they found pieces of a black basalt statue and limestone blocks that had inscriptions from many different time periods (Fiore Marochetti).</p>
		 <p>An Italian team of excavators, that included Ernestro Schiaparelli and then his successor Giulio Farina, went to Gebelein from 1910 to 1937 (but not continuously). These teams were one of the first to excavate the remains of the Temple of Hathor, probably the most important find at this site. This included uncovering a mudbrick wall that contained many cartouches of Menkhepere – a High Priest. From this wall they could find many wall reliefs dating to the 11th dynasty. At this site they found a royal stela that dates to the 2nd-3rd dynasties and they found stelae that came from the New Kingdom. There were also about 400 Demotic and Greek ostraca found, and other text written on papyrus and skins in either Greek or Coptic. (Bard).</p>
		 <p>Schiaparelli’s group also excavated the northern hill at Gebelein, where they found some interesting artifacts. Among these finds were many tombs from many different dynasties and the 4th dynasty tomb of Perim along with his funerary equipment and his coffin that was heavily decorated. Also found was the funerary equipment of Iti’s (pharaoh during the First Intermediate Period) wife, Neferu. At the end of Farina’s dig his group found painted linens whose themes matched those on some vases (many of which have boat motifs that are very popular in Ancient Egypt) and five papyri from the Old Kingdom. These papyri provided priceless administrative information; these were found in a box placed near a decorated coffin. (Fiore Marochetti).</p>
		 <center><img src="http://www.touregypt.net/images/touregypt/gebelein2.jpg" /></center>
		 <center><p>Painted linen from Naqada II</p></center>
		 <p>In the cemetery at Gebelein there have been many interesting finds including the tombs of Iti and Ini. Iti was an ‘overseer of desert expeditions’ from the 6th dynasty and Ini was a nomarch from the 10th dynasty. Neither were pharaohs or in the royal family but both were found buried along with many rich funeral goods. In another tomb from the 11th dynasty there were many paintings that depicted rituals and everyday life. The style that these were painted in reminds us of the First Intermediate Period which is interesting. These tombs, both Predynastic and Dynastic were excavated most heavily by Schiaparelli’s group and Gaston Maspero’s group who was there before the former group. Along with the tombs the two groups also found intricately painted and inscribed sarcophagi, stone tools, black-topped red ware, figurines, and small wooden ship models (Fiore Marochetti).</p> 
		 <p>Probably one of the most famous and important expeditions to this site happened in the 1890s. Sir Wallis Budge, from the British Museum, went to Egypt to bring back artifacts for the museum. He and his team ended up finding (or some sources say ‘buying’) six Predynastic mummies. One of these mummies has come to be known as ‘Gebelein Man’ and he has resided in the British Museum for more than 100 years. This mummy is extraordinary because he is preserved extremely well – he looks kind of like jerky which is gross but great for preservation. Gebelein Man also still had some hair on his head, red, and all his internal organs, including his brain, still intact. In 2012 Gebelein Man was CT-scanned and it was found that he most likely died between 18 and 21 and that he was murdered due to a stab wound in the back (Gebelein Man). The other mummies, one woman, three men, and one with an undeclared sex, were found just like Gebelein Man was – in the fetal position on their left sides with their heads to the south so they’re facing the west which is the Land of the Dead. All of them were found in separate, shallow graves and each was found with some grave goods like pots. A few of the mummies were covered with reed matting and animal skins, but not all. These mummies were important finds because they gave more insight into the mummification process. Not all the mummies were mummified in the same way due to the financial status of the dead person’s family (Jeremiah).</p>
		 <p>After the 1930s Gebelein wasn’t excavated much and not a lot more was found. In the 1990s a group from Turin and a group from the University of Rome went back to excavate Gebelein (Fiore Marochetti). They dug on the southern hill and found another saff-tomb and remains of Pathyris, a town that once was a military camp after a large revolt in Upper Egypt (Vandorpe).</p>
		 <center><img src="http://es.sott.net/image/s6/122088/full/Gebelein1.jpg" /></center>
		 <center><p>Famous Gebelein Man</p></center>
		 <br><!--this creates a break, to separate things a little better-->
		 <h3>Conclusion</h3>
		 <hr><!--this draws a line across the page, which I put under each section heading in the example-->
		 <p>Throughout its many years of occupation Gebelein has been a royal estate, a garrison settlement, a place for the recruitment of mercenaries, and a military post. It’s been used over the years for so many different things and because of that it’s a site full of information. Gebelein may not be the most talked about or excavated site in Egypt – and especially not the world – but it’s still a really important archaeological site. Each of the artifacts and the building remains help us to figure out what actually happened in Ancient Egypt. Gebelein is a really great site for information because it was occupied (is still occupied) for thousands of years and Gebelein was occupied during the Predynastic which is important because not a lot is truly known (there are a lot of theories though) about that time period. For now we just have to hope that the citizens of Naga el-Gherira don’t expand their land father into the site. Hopefully they’ll respect the land as a sacred, historical, and archaeological site and hopefully, in the near future there will be another excavation team in Gebelein, there’s more to be discovered.</p>
		 <br><!--this creates a break, to separate things a little better-->
		 <h4>References</h4>
		 <p>"Gebelein Man." British Museum. N.p., 2014. Web. 16 Nov. 2014.</p>	
		 <p>Bard, Kathryn A. "Gebelein." Encyclopedia of the Archaeology of Ancient Egypt. New York City: Routledge, 1999. 338-40. Print.</p>	
         <p>Fiore Marochetti, Elisa. "Gebelein." UCLA Encyclopedia of Egyptology. 2013. 5-20. Print.</p>	
         <p>Jeremiah, Ken. Eternal Remains: World Mummification and the Beliefs that make it Necessary. Sarasota: First Edition Design Publishing, 2014. 108-10. Print.</p>
		 <p>Vandorpe, K. "Bibliography on Pathyris (Gebelein)." N.p.: n.p., 2012. 1. Web. 17 Nov. 2014. <http://www.trismegistos.org/arch/bibliography_pathyris.pdf>.</p>
		 <p><b>Images</b></p>
		 <p>Figures 1 and 3 - http://www.touregypt.net/featurestories/gebelein.htm</p>
		 <p>Figure 2 - http://www.bridgemanimages.com/en-GB/asset/917072//model-of-boat-from-tomb-of-ini-gebelein-egyptian-civilization-first-intermediate-period-10th-dynasty?context={%22sourceUrl%22%3A%22http%3A\%2F\%2Fwww.bridgemanimages.com\%2Fen-GB\%2Fsearch\%2Fassets\%2F%25start%25\%2F%25limit%25\%2F%257B%2522filter%2522%3A%257B%2522filter_bw%2522%3Anull%2C%2522filter_colour%2522%3Anull%2C%2522filter_creator_id%2522%3Anull%2C%2522filter_footage%2522%3Anull%2C%2522filter_group%2522%3Anull%2C%2522filter_horizontal%2522%3Anull%2C%2522filter_image%2522%3Anull%2C%2522filter_illustration%2522%3Anull%2C%2522filter_location_id%2522%3Anull%2C%2522filter_object%2522%3Anull%2C%2522filter_orientation%2522%3Anull%2C%2522filter_photograph%2522%3Anull%2C%2522filter_square%2522%3Anull%2C%2522filter_supplier_prefix%2522%3Anull%2C%2522filter_text%2522%3A%2522kw%3A%255C%2522first%2520intermediate%255C%2522%2522%2C%2522filter_text_within_new%2522%3Anull%2C%2522filter_text_within_queue%2522%3Anull%2C%2522filter_vertical%2522%3Anull%2C%2522filter_web_category_id%2522%3Anull%2C%2522filter_asset_title%2522%3Anull%2C%2522filter_asset_med%2522%3Anull%2C%2522filter_creator_name%2522%3Anull%2C%2522filter_asset_location%2522%3Anull%2C%2522filter_year%2522%3Anull%2C%2522filter_year_to%2522%3Anull%2C%2522filter_century%2522%3Anull%2C%2522filter_century_to%2522%3Anull%2C%2522filter_year_adbc%2522%3Anull%2C%2522filter_year_to_adbc%2522%3Anull%2C%2522filter_century_adbc%2522%3Anull%2C%2522filter_century_to_adbc%2522%3Anull%2C%2522filter_lightbox_id%2522%3Anull%2C%2522original_filter_text%2522%3A%2522kw%3A%255C%2522first%2520intermediate%255C%2522%2522%2C%2522filter_searchoption_id%2522%3A%25222%2522%257D%2C%2522include_withdrawn%2522%3Afalse%2C%2522on_web_only%2522%3Afalse%2C%2522query_clause%2522%3A%2522%2522%2C%2522sort_order%2522%3A%2522best_relevance%2522%257D\%2Flist%22%2C%22number%22%3A14%2C%22max%22%3A30%2C%22min%22%3A1%2C%22hash%22%3A%22911552abaa6992010fb444b17c1d1839%22}</p>
		 <p>Figure 4 - http://es.sott.net/image/s6/122088/full/Gebelein1.jpg</p>
		 
		
		 
		 
		 
		 
		 
		 
		 
		 
		 
		 
	</div>
     
       <br>
         <br>

    <div class="footer2">
      <div class="container">
        <!--<p class="text-muted">Place sticky footer content here.</p>-->
      </div>
    </div>


    <!-- Bootstrap core JavaScript
    ================================================== -->
    <!-- Placed at the end of the document so the pages load faster -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script src="leaflet-omnivore-master/leaflet-omnivore.js"></script>
    <script src="js/leaflet.js"></script>
	<script type="text/javascript">
		$(document).ready(function(){
			$("a[rel=citation]").popover({
				placement : 'top'
			}).click(function (p) {
				p.preventDefault();
				var $self = $(this);
				setTimeout(function () {
					$self.popover('hide');
				}, 4000);
			});
		});
	</script>
	</body></html>
