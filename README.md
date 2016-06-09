<h1>TEMPLATE STRAP</h1>

<p>
	A set of basic CSS3 classes to help with positioning for landscape and portrait screens. Additional color classes help you create truly brilliant and yet simplistic UI while easing out a host of stuff. With a lot of shorthands for the majority of the classes, it eases out having to write really long class-names. For people familiar with the syntax, make the code absolutely readable, by a combination of initials and shortnames.
	<br /><br />
	Colors inspired by <a href="http://materializecss.com/color.html" target="_blank">Materialize CSS</a>.
</p>

<h4>Table of Contents</h4>
<ul>
	<li><a href="#start">Getting Started</a></li>
	<li><a href="#positioning">Basic Positioning</a></li>
	<li><a href="#orientation">Orientation-specific Positioning</a></li>
	<li><a href="#colors">Color Helpers</a></li>
	<li><a href="#helpers">Helper Classes</a></li>
</ul>

<h5><a name="start">Getting Started</a></h5>
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
	
	After you link up the CSS file, you need to add this nifty little code snippet that'll automatically add <code>.portrait</code> or <code>.landscape</code> class to the body tag. <br />
	<b>Note: This script is essential for automatic switching of classes depending on the screen orientation.</b>

	<p>
		<code>
			window.addEventListener("resize", function() {
				if(this.innerWidth<this.innerHeight) this.document.body.className="portrait";
				else this.document.body.className="landscape";
			});
		</code>
	</p>
</p>

