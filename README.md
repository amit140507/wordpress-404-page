# wordpress-404-page
```
<?php
/**
 * The template for displaying 404 pages (not found)
 *
 * @link https://codex.wordpress.org/Creating_an_Error_404_Page
 *
 * @package WordPress
 * @subpackage Twenty_Seventeen
 * @since Twenty Seventeen 1.0
 * @version 1.0
 */

get_header(); ?>

<div class="page-content">
	<div class="container">

			<section class="error-404 not-found">
				<div class="page-content">

					<h1 class="page-title"><?php _e( 'Oops! That page can&rsquo;t be found.', 'twentyseventeen' ); ?></h1>
					<p><?php _e( 'It looks like nothing was found at this location. Maybe try a search?', 'twentyseventeen' ); ?></p>
					<?php get_search_form(); ?>

				</div>
			</section>

	</div>
</div>

<?php
get_footer();
```
