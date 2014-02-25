/** Customize Genesis Footer */
remove_action( 'genesis_footer', 'genesis_do_footer' );
add_action( 'genesis_footer', 'blogvkp_footer' );
function blogvkp_footer() {
    ?>
    <p>&copy; Copyright 2014 <a href="http://zarchiwebdesign.com">Zarchi Web Design</a> | Los Angeles Website Design | SEO | Online Marketing | Training </p>
    <?php
}
