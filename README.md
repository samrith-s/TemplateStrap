<h1>TEMPLATESTRAP</h1>

<p>
	A set of basic CSS3 classes to help with positioning for landscape and portrait screens. Additional color classes help you create truly brilliant and yet simplistic UI while easing out a host of stuff. With a lot of shorthands for the majority of the classes, it eases out having to write really long class-names. For people familiar with the syntax, make the code absolutely readable, by a combination of initials and shortnames.
	<br /><br />
	Colors inspired by <a href="http://materializecss.com/color.html" target="_blank">Materialize CSS</a>.
</p>

<h4>Table of Contents</h4>
<ul>
	<li><a href="#start">Getting Started</a></li>
	<li><a href="#positioning">Basic Positioning</a></li>
	<li>
		<a href="#orientation">Orientation-specific Positioning</a>
		<ul>
			<li><a href="#orientation-portrait">Portrait Positioning</a></li>
			<li><a href="#orientation-landscape">Landscape Positioning</a></li>
		</ul>
	</li>
	<li><a href="#colors">Color Helpers</a></li>
	<li><a href="#helpers">Helper Classes</a></li>
</ul>

<hr style="opacity:0.3" />

<h3><a name="start">Getting Started</a></h3>
<p>
	To get started off with TemplateStrap, simple link the CSS file.

	<p>
		Production URL:<br />
		<code>https://cdn.rawgit.com/samrith-s/TemplateStrap/master/main/templatestrap.css</code>
	</p>

	<p>
		Development URL:<br />
		<code>https://rawgit.com/samrith-s/TemplateStrap/master/main/templatestrap.css</code>
	</p>
	
	<p>
		After you link up the CSS file, you need to add this nifty little code snippet that'll automatically add <code>.portrait</code> or <code>.landscape</code> class to the body tag. This script is essential for automatic switching of classes depending on the screen orientation.
	</p>

	<p>
		<code>
			window.addEventListener("resize", function() {
			if(this.innerWidth < this.innerHeight) this.document.body.className="portrait";
			else this.document.body.className="landscape";
			});
		</code>
	</p>

	<p>
		AAAAND, you're done! You can now use the classes contained within to create your own views for both orientations exclusively. Please feel free to raise issues on the <a href="https://github.com/samrith-s/TemplateStrap/issues" target="_blank">issues section</a> of this repository.
	</p>
</p>

<h3><a name="positioning">Basic Positioning</a></h3>
<p>
	<p>
		TS provides a bunch of classes to position any HTML element within thr screen space. The typical TS screen is divided into 20 sections, or columns, and 20 bars, or rows, each taking up 5% of the screen space. 
	</p>

	<p>
		TS sections and bars work in tandem with the <code>.portrait</code> and <code>.landscape</code> classes to provide great flexibility and exclusivity to design UI for each of those orientations.
	</p>
</p>

<h3><a name="orientation">Orientation-specific Positioning</a></h3>
<p>
	<p>
		TS relies heavily on orientation. The main function of this CSS framework is to make it pain-free to create specific differences in UI for landscape and portrait screens.
	</p>

	<p>
		<h5><a name="#orientation-portrait">Portrait Positioning</a></h5>

		<p>
			Portrait positioning uses the 'p' key in positioning classes. Below are a list of classes used in portrait positioning.
		</p>
		<ul>
			<li>Width Portrait (wp):<br />'wp' followed by a number [0..20]<br />Example: <code>.wp0, .wp10, .wp15</code><br /><br /></li>
			<li>Height Portrait (hp):<br />'hp' followed by a number [0..20]<br />Example: <code>.hp0, .hp10, .hp15</code><br /><br /></li>
			<li>Top Portrait (tp):<br />'tp' followed by a number [0..20]<br />Example: <code>.tp0, .tp10, .tp15</code><br /><br /></li>
			<li>Left Portrait (lp):<br />'lp' followed by a number [0..20]<br />Example: <code>.lp0, .lp10, .lp15</code><br /><br /></li>
			<li>Bottom Portrait (bp):<br />'bp' followed by a number [0..20]<br />Example: <code>.bp0, .bp10, .bp15</code><br /><br /></li>
			<li>Right Portrait (rp):<br />'rp' followed by a number [0..20]<br />Example: <code>.rp0, .rp10, .rp15</code><br /><br /></li>
		</ul>
	</p>
</p>

