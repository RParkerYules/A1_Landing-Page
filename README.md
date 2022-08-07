# A1_Landing-Page

The following changes have been implemented in HTML & CSS:

1. The 'seo' letters in the word Horiseon are a light grey, whereas the other letters are white. 

This was controlled in CSS by setting the color to #d9dcd6.

In the HTML the inline element 'span' was controlled by CSS class="seo"

The HTML class="seo" was changed to style="color" and the class="seo" was deleted from the CSS. 

2. In CSS, the 'search-engine-optimisation', 'online-reputation-management' and 'social-media-marketing' classes all had identical parameters. 

The class 'search-engine-optimisation' was re-named to 'content' and the other two were deleted.

Then 'class=content' was added in HTML replacing 'class=search-engine-optimisation', 'class=online-reputation-management' and 'class=social-media-marketing'

3. '.benefit-lead', '.benefit-brand' and '.benefit-cost' also had duplication of margin-bottom & color. 

These were all changed to 'benefit-new'

The same changes were implemented for 'h3' & 'img'

4. '.search-engine-optimisation img', 'online-reputation-management img' & 'social-media-marketing img' were all condensed into 'content-class img'

5. '.search-engine-optimisation h2', 'online-reputation-management h2' & 'social-media-marketing h2' were all condensed into 'content-class h2'

6. When 'Search Engine Optimisation' was clicked in the header nothing happened. When 'Online Reputation Management' & 'Social Media Marketing' were clicked the hyperlink went to the relevant container(s). 

Added class="content-class" in HTML line 29 after id="search-engine-optimization"

These are all the changes that have been implemented. 





