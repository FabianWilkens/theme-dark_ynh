# Yunohost Dark Theme
## theme-dark_ynh

### Yunohost Admin
##### Installation:
- Copy `admin/dist/css/style_custom.css` into `/usr/share/yunohost/admin/dist/css/`
- Add `<link rel="stylesheet" media="screen" href="dist/css/style_custom.css">` to `/usr/share/yunohost/admin/index.html` between `<head>`and `</head>`

### Yunohost User Portal
##### Installation:
- Copy `ssowat/theme-dark_ynh` into `/usr/share/ssowat/portal/assets/themes/`
- Edit `/etc/ssowat/conf.json.persistent`
- Change `"theme": "default"` to `"theme": "theme-dark_ynh"`

More informations:
 You can follow the instructions explained here: [https://yunohost.org/#/theming](https://yunohost.org/#/theming)
