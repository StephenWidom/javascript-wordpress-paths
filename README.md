## JAVASCRIPT WORDPRESS PATHS
A WordPress plugin to define WordPress paths, like site_url(), as JavaScript variables for easy access within your JavaScripts! It hooks into the ```wp_head()``` action.

## VARIABLES:
JavaScript variables on the left, their PHP equivalent on the right.

### Plugins
```jwp_plugins_url``` = ```plugins_url()```

### Themes
```jwp_get_template_directory_uri``` = ```get_template_directory_uri()```

```jwp_get_stylesheet_directory_uri``` = ```get_stylesheet_directory_uri()```

```jwp_get_stylesheet_uri``` = ```get_stylesheet_uri()```

```jwp_get_theme_root_uri``` = ```get_theme_root_uri()```

```jwp_get_theme_root``` = ```get_theme_root()```

```jwp_get_theme_roots``` = ```get_theme_roots()```

```jwp_get_stylesheet_directory``` = ```get_stylesheet_directory()```

```jwp_get_template_directory``` = ```get_template_directory()```

### Site Home
```jwp_home_url``` = ```home_url()```

### WordPress
```jwp_admin_url``` = ```admin_url()```

```jwp_site_url``` = ```site_url()```

```jwp_content_url``` = ```content_url()```

```jwp_includes_url``` = ```includes_url()```

```jwp_wp_upload_dir_path``` = ```wp_upload_dir["path"]```

```jwp_wp_upload_dir_url``` = ```wp_upload_dir["url"]```

```jwp_wp_upload_dir_basedir``` = ```wp_upload_dir["basedir"]```

```jwp_wp_upload_dir_baseurl``` = ```wp_upload_dir["baseurl"]```

### Multisite
```jwp_get_admin_url``` = ```get_admin_url()```

```jwp_get_home_url``` = ```get_home_url()```

```jwp_get_site_url``` = ```get_site_url()```

```jwp_network_admin_url``` = ```network_admin_url()```

```jwp_network_site_url``` = ```network_site_url()```

```jwp_network_home_url``` = ```network_home_url()```

*Developed by Stephen Widom - http://stephenwidom.com*
