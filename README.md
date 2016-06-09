<h1><a name="#top">TEMPLATESTRAP</a></h1>

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
	<li>
		<a href="#colors">Color Helpers</a>
		<ul>
			<li><a href="#colors-background">Background Coloring</a></li>
			<li><a href="#colors-text">Text Coloring</a></li>
			<li>
				<a href="#colors-border">Border Coloring</a>
				<ul>
					<li><a href="#colors-border-top">Top Border Coloring</a></li>
					<li><a href="#colors-border-left">Left Border Coloring</a></li>
					<li><a href="#colors-border-bottom">Border Bottom Coloring</a></li>
					<li><a href="#colors-border-right">Right Border Coloring</a></li>
				</ul>
			</li>
	</li>
	<!-- <li><a href="#helpers">Helper Classes</a></li> -->
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

	<p><a href="#top">Back to Top</a></p>
</p>

<hr style="opacity:0.3" /> 

<h3><a name="positioning">Basic Positioning</a></h3>
<p>
	<p>
		TS provides a bunch of classes to position any HTML element within thr screen space. The typical TS screen is divided into 20 sections, or columns, and 20 bars, or rows, each taking up 5% of the screen space. 
	</p>

	<p>
		TS sections and bars work in tandem with the <code>.portrait</code> and <code>.landscape</code> classes to provide great flexibility and exclusivity to design UI for each of those orientations.
	</p>

	<p>
		<strong>
			All elements on which TS classes need to reflect should have the <code>.ts</code> class attached to them. Every TS element in the HTML is identified by this class.
		</strong>
	</p>

	<p><a href="#top">Back to Top</a></p>
</p>

<hr style="opacity:0.3" />

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

	<p>
		<h5><a name="#orientation-landscape">Landscape Positioning</a></h5>
		<p>
			Landscape positioning uses the 'l' key in positioning classes. Below are a list of classes used in landscape positioning.
		</p>
		<ul>
			<li>Width Landscape (wl):<br />'wl' followed by a number [0..20]<br />Example: <code>.wl0, .wl10, .wl15</code><br /><br /></li>
			<li>Height Landscape (hl):<br />'hl' followed by a number [0..20]<br />Example: <code>.hl0, .hl10, .hl15</code><br /><br /></li>
			<li>Top Landscape (tl):<br />'tl' followed by a number [0..20]<br />Example: <code>.tl0, .tl10, .tl15</code><br /><br /></li>
			<li>Left Landscape (ll):<br />'ll' followed by a number [0..20]<br />Example: <code>.ll0, .ll10, .ll15</code><br /><br /></li>
			<li>Bottom Landscape (bl):<br />'bl' followed by a number [0..20]<br />Example: <code>.bl0, .bl10, .bl15</code><br /><br /></li>
			<li>Right Landscape (rl):<br />'rl' followed by a number [0..20]<br />Example: <code>.rl0, .rl10, .rl15</code><br /><br /></li>
		</ul>
	</p>

	<p><a href="#top">Back to Top</a></p>

</p>

<hr style="opacity:0.3" />

<h3><a name="#colors">Color Helpers</a></h3>
<p>
	<p>
		TS not only provides positioning, but also provides a bunch of color classes to help in coloring of background, text and border of all <code>.ts</code> elements.
	</p>
	<p>
		The complete list of colors will be added here soon. In the mean while, you can check out the color reference at <a href="http://materializecss.com/color.html">Materialize CSS colors</a> page. The classes here are similar, barring a few minor changes.
	</p>

	<h5><a name="#colors-background">Background Coloring</a></h5>
	<p>
		Background coloring is very simple using TS coloring classes. For adding any color onto an element that can be colored, just add the color name to the TS element.
		<br />
		Example:  To achieve a background color of teal, your TS element will look something like so --
		<br />
		<code>< p class="teal" >This is a teal background-colored paragraph.< /p ></code>
		<br />
		And, to lighten or darken or accentuate the shade, you can add relevant <code>.lighten</code>, <code>.darken</code> or <code>.accent</code> classes to it, like so --
		<br />
		<code>< p class="teal lighten2" >This is a teal background-colored paragraph lightened by 2 shades.< /p ></code>  
	</p>

	<h5><a name="#colors-text">Text Coloring</a></h5>
	<p>
		Text coloring is just as simple using TS coloring classes. For adding any text color onto an element that can have a colored text, just add the color name followed by '-text' to the TS element.
		<br />
		Example:  To achieve a text color of teal, your TS element will look something like so --
		<br />
		<code>< p class="teal-text" >This is a teal text-colored paragraph.< /p ></code>
		<br />
		And, to lighten or darken or accentuate the shade, you can add relevant <code>.text-lighten</code>, <code>.text-darken</code> or <code>.text-accent</code> classes to it, like so --
		<br />
		<code>< p class="teal-text text-lighten2" >This is a teal text-colored paragraph lightened by 2 shades.< /p ></code>  
	</p>

	<h5><a name="#colors-border">Border Coloring</a></h5>
	<p>
		Border coloring is simple but a little more extensive using TS coloring classes. For adding any border color onto an element that can have a colored border, just add the color name followed by '-border' to the TS element. Border colors only reflect on elements with a <code>border-style: solid | dotted | dashed</code> or a <code>border-weight: px | em | rem</code> styling present.
		<br />
		Example:  To achieve a border color of teal, your TS element will look something like so --
		<br />
		<code>< p class="teal-border" >This is a teal border-colored paragraph.< /p ></code>
		<br />
		And, to lighten or darken or accentuate the shade, you can add relevant <code>.border-lighten</code>, <code>.border-darken</code> or <code>.border-accent</code> classes to it, like so --
		<br />
		<code>< p class="teal-border border-lighten2" >This is a teal border-colored paragraph lightened by 2 shades.< /p ></code>  
	</p>

	<p>
		TS allows specifying border colors individually.
	</p>

	<h6><a name="#colors-border-top">Top Border Coloring</a></h6>
	<p>
		The top border coloring classes only set the top border color.
		<br />
		Example:  To achieve a top border color of teal, your TS element will look something like so --
		<br />
		<code>< p class="teal-border-t" style="border-width:5px; border-style:solid;" >This is a teal top-border-colored paragraph.< /p ></code>
		<br />
		And, to lighten or darken or accentuate the shade, you can add relevant <code>.border-t-lighten</code>, <code>.border-t-darken</code> or <code>.border-t-accent</code> classes to it, like so --
		<br />
		<code>< p class="teal-border-t border-t-lighten2" >This is a teal border-top-colored paragraph lightened by 2 shades.< /p ></code>
	</p>

	<h6><a name="#colors-border-left">Left Border Coloring</a></h6>
	<p>
		The left border coloring classes only set the left border color.
		<br />
		Example:  To achieve a left border color of teal, your TS element will look something like so --
		<br />
		<code>< p class="teal-border-l" style="border-width:5px; border-style:solid;" >This is a teal left-border-colored paragraph.< /p ></code>
		<br />
		And, to lighten or darken or accentuate the shade, you can add relevant <code>.border-l-lighten</code>, <code>.border-l-darken</code> or <code>.border-l-accent</code> classes to it, like so --
		<br />
		<code>< p class="teal-border-l border-l-lighten2" >This is a teal border-left-colored paragraph lightened by 2 shades.< /p ></code>
	</p>

	<h6><a name="#colors-border-bottom">Bottom Border Coloring</a></h6>
	<p>
		The bottom border coloring classes only set the bottom border color.
		<br />
		Example:  To achieve a bottom border color of teal, your TS element will look something like so --
		<br />
		<code>< p class="teal-border-b" style="border-width:5px; border-style:solid;" >This is a teal bottom-border-colored paragraph.< /p ></code>
		<br />
		And, to lighten or darken or accentuate the shade, you can add relevant <code>.border-b-lighten</code>, <code>.border-b-darken</code> or <code>.border-b-accent</code> classes to it, like so --
		<br />
		<code>< p class="teal-border-b border-b-lighten2" >This is a teal border-bottom-colored paragraph lightened by 2 shades.< /p ></code>
	</p>

	<h6><a name="#colors-border-right">Top Border Coloring</a></h6>
	<p>
		The right border coloring classes only set the right border color.
		<br />
		Example:  To achieve a right border color of teal, your TS element will look something like so --
		<br />
		<code>< p class="teal-border-r" style="border-width:5px; border-style:solid;" >This is a teal right-border-colored paragraph.< /p ></code>
		<br />
		And, to lighten or darken or accentuate the shade, you can add relevant <code>.border-r-lighten</code>, <code>.border-r-darken</code> or <code>.border-r-accent</code> classes to it, like so --
		<br />
		<code>< p class="teal-border-r border-r-lighten2" >This is a teal border-right-colored paragraph lightened by 2 shades.< /p ></code>
	</p>

	<p><a href="#top">Back to Top</a></p>

</p>
