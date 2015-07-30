## JAVASCRIPT WORDPRESS PATHS
A WordPress plugin to define WordPress paths, like site_url(), as JavaScript variables for easy access within your JavaScripts! It hooks into the ```wp_head()``` action.

## VARIABLES:
JavaScript variables on the left, their PHP equivalent on the right.

### Plugins
```wp_plugins_url = plugins_url()```

### Themes
```wp_get_template_directory_uri = get_template_directory_uri()
wp_get_stylesheet_directory_uri = get_stylesheet_directory_uri()
wp_get_stylesheet_uri = get_stylesheet_uri()
wp_get_theme_root_uri = get_theme_root_uri()
wp_get_theme_root = get_theme_root()
wp_get_theme_roots = get_theme_roots()
wp_get_stylesheet_directory = get_stylesheet_directory()
wp_get_template_directory = get_template_directory()```

### Site Home
```wp_home_url = home_url()```

### WordPress
```wp_admin_url = admin_url()
wp_site_url = site_url()
wp_content_url = content_url()
wp_includes_url = includes_url()
wp_wp_upload_dir_path = wp_upload_dir["path"]
wp_wp_upload_dir_url = wp_upload_dir["url"]
wp_wp_upload_dir_basedir = wp_upload_dir["basedir"]
wp_wp_upload_dir_baseurl = wp_upload_dir["baseurl"]```

### Multisite
```wp_get_admin_url = get_admin_url()
wp_get_home_url = get_home_url()
wp_get_site_url = get_site_url()
wp_network_admin_url = network_admin_url()
wp_network_site_url = network_site_url()
wp_network_home_url = network_home_url()```

*Developed by Stephen Widom - http://stephenwidom.com*