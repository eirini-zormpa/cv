## Eirini Zormpa's pagedown rendered CV

This repo contains the source-code and results of my CV built with the [pagedown package](https://pagedown.rbind.io) and a modified version of the 'resume' template. 

The main files are:

- `zormpa_index.Rmd`: Source template for the cv, contains a variable `PDF_EXPORT` in the header that changes styles for pdf vs html. 
- `css/`: Directory containing the custom CSS files used to tweak the default 'resume' format from pagedown. (From `nstrayer/cv`.)
- `parsing_functions.R`: Functions used to parse and properly format position data. (From `nstrayer/cv`.)
- `strayer_template/`: Original CV and resume documents forked from `nstrayer/cv`.

## Acknowledgments

This CV was built on the one created by [Amy Gill](https://github.com/gillsignals/cv), in turn based on the [pagedown CV template](https://github.com/nstrayer/cv) provided by [Nick Strayer](http://nickstrayer.me).
