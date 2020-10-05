# Rivers of North America
---

<iframe width="560" height="315" style="float:left; margin-right:30px; margin-bottom:20px" src="https://www.youtube.com/embed/u56yE70svqI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

My current project at UA's Cartographic Research is working on the maps for the upcoming edition of [*Rivers of North America*](https://www.amazon.com/Rivers-North-America-Arthur-Benke/dp/0120882531), a massive reference book that provides in-depth examinations of river systems across North America. There are approximately two hundred maps to make for the book, and since each map covers individual watersheds that vary significantly in all aspects from size to topographic character, from the outset it became clear to me that this project would require that I make deliberate choices to ensure that the mapmaking process could be streamlined as much as possible.

Given the geographic scope of this job, coming across all of the data needed to make maps spanning from Ellesmere Island to Central America was no easy task. All told, the maps as a whole call for data on rivers and streams; lakes and other bodies of water; elevation; major urban settlements; dams; and even the [physiographic divisions of North America](../na_physioregions). The majority of maps are produced using vector data from the [Global Map initiative](https://globalmaps.github.io/) and [GMTED2010](https://www.usgs.gov/land-resources/eros/coastal-changes-and-impacts/gmted2010?qt-science_support_page_related_con=0#qt-science_support_page_related_con) raster elevation data, since these data sources are relatively seamless across national boundaries and are flexible enough to accomodate the mapping of most watersheds featured in the book (though some smaller watersheds must be mapped using even larger scale data). Watershed data, meanwhile, was largely acquired from national and state/provincial repositories in which the watersheds can be found, although for many cases (particularly in the Canadian Arctic and in Central America), it was necessary to manually delineate the watershed boundaries where no reliable data otherwise existed, which was done in QGIS using the hydrological tools found in the excellent (and free!) [Whitebox Tools](https://jblindsay.github.io/ghrg/WhiteboxTools/index.html). Furthermore, in order to maintain consistency among all of the maps, each linear stream network dataset was modified to take on the rank scale system utilized by the [Natural Earth global rivers dataset](https://www.naturalearthdata.com/downloads/10m-physical-vectors/10m-rivers-lake-centerlines/), so that a consistent stream hierarchy could be established across all maps relatively quickly and effortlessly.

Each map is made using QGIS, Adobe Photoshop and Illustrator (including Avenza MAPublisher), Pyramid Shader, and Natural Scene Designer. The video at the top of this page showcases my talk at NACIS 2019's Practical Cartography Day, in which I broke down some of the steps that go into making the maps. As of January 13, 2020, almost all of the rivers to be mapped in Canada have been completed. A sample of these maps can be found below—there are many more yet to be made, and I look forward to finishing out this exciting and rewarding project in the months to come.

<div class="feature_multi">
	<div class="entry">
		<a href="../../img/RoNA_Ohio.jpg"><img class="thumb" src="../../img/RoNA_Ohio.jpg" alt=""></a>
		<div class="thumb_label">
			<div class="label_text"><a href="../../img/RoNA_Ohio.jpg">Ohio River Overview Map</a></div>
		</div>
	</div>
	<div class="entry">
		<a href="../../img/RoNA_Arkansas.jpg"><img class="thumb" src="../../img/RoNA_Arkansas.jpg" alt=""></a>
		<div class="thumb_label">
			<div class="label_text"><a href="../../img/RoNA_Arkansas.jpg">Arkansas River Headwaters</a></div>
		</div>
	</div>
	<div class="entry">
		<a href="../../img/RoNA_Churchill.jpg"><img class="thumb" src="../../img/RoNA_Churchill.jpg" alt=""></a>
		<div class="thumb_label">
			<div class="label_text"><a href="img/RoNA_Churchill.jpg">Churchill River (Labrador)</a></div>
		</div>
	</div>
	<div class="entry">
		<a href="../../img/RoNA_Lacantún.jpg"><img class="thumb" src="../../img/RoNA_Lacantún.jpg" alt=""></a>
		<div class="thumb_label">
			<div class="label_text"><a href="../../img/RoNA_Lacantún.jpg">Río Lacantún</a></div>
		</div>
	</div>
	<div class="entry">
		<a href="../../img/RoNA_Kazan.jpg"><img class="thumb" src="../../img/RoNA_Kazan.jpg" alt=""></a>
		<div class="thumb_label">
			<div class="label_text"><a href="../../img/RoNA_Kazan.jpg">Kazan River</a></div>
		</div>
	</div>
	<div class="entry">
		<a href="../../img/RoNA_Wolf.jpg"><img class="thumb" src="../../img/RoNA_Wolf.jpg" alt=""></a>
		<div class="thumb_label">
			<div class="label_text"><a href="../../img/RoNA_Wolf.jpg">Wolf River</a></div>
		</div>
	</div>
	<div class="entry">
		<a href="../../img/RoNA_Spokane.jpg"><img class="thumb" src="../../img/RoNA_Spokane.jpg" alt=""></a>
		<div class="thumb_label">
			<div class="label_text"><a href="../../img/RoNA_Spokane.jpg">Spokane River</a></div>
		</div>
	</div>
	<div class="entry">
		<a href="../../img/RoNA_Santee-Cooper.jpg"><img class="thumb" src="../../img/RoNA_Santee-Cooper.jpg" alt=""></a>
		<div class="thumb_label">
			<div class="label_text"><a href="../../img/RoNA_Santee-Cooper.jpg">Santee-Cooper River Complex</a></div>
		</div>
	</div>
</div>