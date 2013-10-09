srka-magento-review-stars
=========================

Simple Prototype JS review stars plugin to replace default Magento ratings table.

This is a small (less than 1.5KB of JS) and simple Prototype JS plugin to replace the default Magento ratings table. It does not have any configuration options or advanced functionality. You just plug it in and it should do the job. 


Installation
---------------
  * Add srka.review.stars.min.js (or srka.review.stars.js) and srka.review.stars.css files to the product page.
  * Open app/design/frontend/[YOUR_PACKAGE]/[YOUR_THEME]/template/review/form.phtml and add the following code just below the #review-form closing tag.
`````
<script type="text/javascript">
	//<![CDATA[
	var reviewStars = new SrkaReviewStars('product-review-table');
	//]]>
</script>
`````
  * Test it and enjoy.
