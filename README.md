# Statamic XML Sitemap #
A series of files that can be used to generate an XML sitemap for sites running [Statamic](http://statamic.com/) - a flat file CMS.

Please feel free to use / re-distribute as you wish.

## Installation ##
Simply copy the files into the relevant directories in your Statamic site structure. Easy!

## Usage ##
### Included URL's ###
By default the sitemap will include URL's for your homepage, all pages from your web root and entries inside a `/blog/` content directory. You can control what URL's are included by editing the `/_themes/your-theme/templates/sitemap.html` file.

### Priority ###
By default your homepage will have a priority of 1.0, and all other pages and entries will have a priority of 0.7. You can override the homepage priority in the `/_themes/your-theme/templates/sitemap.html` file. To override the priority of pages and entries, simple add a YAML property named `sitemap_priority'` to your content files.

### Viewing ###
You can view your sitemap at http://www.yoursite.com/sitemap.xml.

## Example ##
My [personal website](http://georgebuckingham.com/) and blog generates a sitemap using these files. You can view it here: [http://georgebuckingham.com/sitemap.xml](http://georgebuckingham.com/sitemap.xml).