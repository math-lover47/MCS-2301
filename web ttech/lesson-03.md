<h1>Requirements</h1>
<p style="font-size: 1em;">We want to learn about flexbox layout in html.

So let divide it into steps for better understanding.</p>
<p style="font-size: 1em;">First of all we need to be familiar with stuff like: <i>css and div, class, id.</i></p>
<p style="font-size: 1em;">Then we need to learn about display property<br>
<a href="https://www.w3schools.com/css/css_display_visibility.asp"> source-01 </a><br>
<a href="https://www.w3schools.com/cssref/pr_class_display.php"> source-02 </a><br>
<a href="https://www.geeksforgeeks.org/introduction-to-css-flexbox/"> source-03 </a></p>
<h1>Shortly about CSS display property</h1>
<p style="font-size: 1em;">

The <b>Display property</b> in CSS defines how the components(div, hyperlink, heading, etc) are going to be placed on the web page. As the name suggests, this property is used to define the display of the different parts of a web page.</p>
<ul>
<li><p><b>Block:</b> This property is used as the default property of div. This property places the div one after another vertically. Height and width of the div can be changed using the block property if the width is not mentioned, then div under block property will take up the width of the container.</p></li>

<li><p><b>Inline:</b> This property is the default property of anchor tags. This is used to place the div inline i.e. in a horizontal manner. The inline display property ignores the height and the width set by the user.</p></li>

<li><p><b>Inline-block:</b> This features uses the both properties mentioned above, block and inline. So, this property aligns the div inline but the difference is it can edit the height and the width of block. Basically, this will align the div both in block and inline fashion.</p></li>

<li><p><b>None</b> This property hides the div or the container which use this property. Using it on one of the div it will make working clear.</p></li>

</ul>
If you want to <a href="https://www.w3schools.com/cssref/pr_class_display.php">read about display property</a>

<h1>CSS fonts</h1>
<p style="font-size: 1em;">The CSS font property is used to set the fonts content of HTML element. There are many font property in CSS which are discussed below:</p>
<ul>
<li><p style='font-family: "Courier New", Courier, monospace'><b>font-family:</b> used to set the font type of an HTML element. It holds several font names as a fallback system.`font-family: "Courier New", Courier, monospace;`</p></li>
<li><p style="font-size: 1em;"><b>font-style:</b> used to specify italic text.
This property has three values:</p></li>
<ul>
<li><p style="font-style: normal">normal - The text is shown normally</p></li>
<li><p style="font-style: italic">italic - The text is shown in italics</p></li>
<li><p style="font-style: oblique">oblique - The text is "leaning" (oblique is very similar to italic, but less supported)</p></li>
</ul>
<li><p style="font-size: 1em;"><b>font-weight</b> property specifies the weight of a font:</p></li>
<ul>
<li><p style="font-weight: normal">normal - The text is shown normally</p></li>
<li><p style="font-weight: lighter">lighter - The text is shown in light weight</p></li>
<li><p style="font-weight: bold">bold - The text is shown in bold weight</p></li>
</ul>
<li><p style="font-size: 1em;">The <b>font-variant</b> property specifies whether or not a text should be displayed in a small-caps font. In a small-caps font, all lowercase letters are converted to uppercase letters. However, the converted uppercase letters appears in a smaller font size than the original uppercase letters in the text.</p></li>
<ul>
<li><p style="font-variant: normal">normal - The text is shown normally</p></li>
<li><p style="font-variant: small-caps">small-caps - Like uppercase is Uppercase but lowercase is Lower uppercase</p></li>
</ul>
<li><p style="font-size: 1em;">The <b>font-size</b> property sets the size of the text.</p></li>
</ul>
<h2>Font Sizes</h2>
<p style="font-size: 1em;">If you do not specify a font size, the default size for normal text, like paragraphs, is 16px (16px=1em). </p>
<p style="font-size: 1em;">To allow users to resize(Resize mean zoom) the text (in the browser menu), many developers use <code>em</code> instead of <code>px</code>. </p>
<p style="font-size: 1em;">Since <code>em</code> not work with all browsers the solution that works in all browsers, is to set a default font-size in percent for the <code>body</code> element. </p>
<p style="font-size: 1em;">Responsive Font Size - the text size can be set with a <code>vw</code> unit, which means the "viewport width". That way the text size will follow the size of the browser window(viewport is the browser window size. 1vw = 1% of viewport width. If the viewport is 50cm wide, 1vw is 0.5cm.)</p>
If you want to read about<a href="https://www.w3schools.com/css/css_font.asp"> fonts </a>in html
<h1>Start learning flexbox</h1>
<p style="font-size: 1em;">It is also called a flexible box model. It is basically a layout model that provides an easy and clean way to <b>arrange items within container</b>. Flexbox is different from the <b>block</b> model which is vertically bias and the <b>inline</b> which is horizontally bias. Flexbox was created for <b>small-scales layouts</b> and there’s another standard called grids which is geared more towards <b>larger scale layouts</b>, It works similar to the way to Twitter <b>bootstrap</b> grid system works. <i>Flexbox is responsive and mobile-friendly.</i> To start with flexbox firstly create a <b>flex container</b>. To create a flex container set the display property to <b>flex</b>.</p>
<ul>
<li><p style="font-size: 1em;"><b>flex-direction:</b> used to define the direction of flexible item. The default axis is horizontal in flexbox, so the items flow into a row.<br>(flex directions: row, row-reverse, column, column-reverse)</p></li>

  

<li><p style="font-size: 1em;"><b>flex-wrap:</b> used to define the wrap of flex-items. If flex-wrap property set to wrap then browser’s window set the box. If browser window is smaller than elements then elements go down to the next line.<br>(flex wraps: wrap, nowrap, wrap-reverse)</p></li>

  

<li><p style="font-size: 1em;"><b>flex-flow:</b> shorthand property for setting both the <i>flex-direction and flex-wrap</i> properties.<br>

(flex-flow: direction wrap)</p></li>

  

<li><p style="font-size: 1em;"><b>justify-content:</b> used to align the flex items according to the main axis within a flexbox container.<br>

{<br>

flex justifies: <i>center, flex-start, flex-end,</i> <br>

<i>space-around</i> - has equal space on the inside, and then the outside is half of the inside space, <br>

<i>space-evenly</i> - has everything equal (space inside and out), <br>

<i>space-between</i> - puts the first and last child elements sitting flush at the start and end edges of the parent element.<br>

}</p></li>

  

<li><p style="font-size: 1em;"><b>align-items:</b> used to align flex items vertically according to the cross axis.<br>

{<br>

flex align-items: <i>center, flex-start, flex-end,</i><br>

<i>stretch</i> - stretches the flex items to fill the container (this is equal to "normal" which is default<br>

<i>baseline</i> - positions the flex items at the baseline of the container. <a href="https://stackoverflow.com/questions/34606879/whats-the-difference-between-flex-start-and-baseline">Difference with flex-start</a><br>

<i>normal</i> - Items remain sized according to their intrinsic or defined size.(same as stretch) but cannot be changed explicitly

<br>}</p></li>

<li><p style="font-size: 1em;"><b>align-content:</b> used to align the flex lines,<a href="https://stackoverflow.com/questions/27539262/whats-the-difference-between-align-content-and-align-items"> similar </a>to align-items, but instead of aligning flex items, it aligns the flex lines(i.e. only when flex-wrap: wrap is applied).<br><a href="https://www.w3schools.com/css/tryit.asp?filename=trycss3_flexbox_align-content_center">try to change from align-items to align content to see difference</a><br>

{<br>

flex align-contents: <i>center, stretch, flex-start, flex-end,</i><br>

<i>space-between</i> - the space between the flex lines are equal, but the first item is flush with the start edge of the container, and the last item is flush with the end edge of the container<br>

  

<i>space-around</i> the space between the flex lines are equal, but the space before the first item and after the last item is set to half of the space between the flex lines:<br>

  

<i>space-evenly</i> the flex lines are evenly distributed in the flex container, with equal space on top, bottom and between

<br>}</p></li>

</ul>
<h2>CSS properties for flexbox</h2>
<p style="font-size: 1em;">One funny thing here that you can switch main and cross axes<br>(flex-direction: column) then functionalities of justify-content and align-items will change</p>
<p style="font-size: 1em;">Use gap(gap : value) property to add gaps between items inside container(by default is 0)</p>
<p style="font-size: 1em;">Use flex-grow(flex-grow : unitless value) property to allow item to grow if there enough space(if all items have flex-grow: 1 remaining space will distributed equally to all of them(if you set it to 0 it will disappear)</p>
<p style="font-size: 1em;">Use flex-shrink(flex-grow : unitless value) property specifies how the item will shrink relative to the rest of the flexible items inside the same container(if you set it to 0 it won't shrink at all)</p>
<p style="font-size: 1em;">Use flex-basis(flex-basis : value) property specifies the initial length of a flexible item.(override previous)(if you set it to 0 it will shrink to the max)</p>
<p style="font-size: 1em;"> Shorthand to above stuff is flex(flex: flex-grow, flex-shrink, flex-basis) 1 parameter is required others is optional(will set automatically)</p>
<p style="font-size: 1em;">Use align-self(center, flex-start, flex-end, baseline) to override align-item on container(similiar to flex-basis)</p>
<p style="font-size: 1em;">Use order(order : unitless value) to change order(default value is zero)<br>
if you give property order: -1 to last item it will appear first<br>
if you give property order: 1 to first item it will appear last<br>
(don't use it unless absolutely have to, cause it messes with semantics and accessibility of your HTML)
</p>
<p style="font-size: 1em;"><a href="https://www.geeksforgeeks.org/css-flex-property/">Read more about CSS properties</a></p>
<p style="font-size: 1em;">If you want to read about flexboxes<a href="https://www.w3schools.com/css/css3_flexbox_container.asp"> w3school </a>also <a href="https://www.geeksforgeeks.org/introduction-to-css-flexbox/">GFG</a></p>
