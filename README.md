# csp-lib-web-dev
Customizations and development information for the CSP Library LibGuides site.

## Overriding CSS/JS included by default
LibGuides applies its own CSS and JS files. Some of these can be disabled; others cannot. Certain files can be excluded in the admin. settings:
### Site-wide
*Admin. > Look & Feel > Custom JS/CSS tab*

Below the code box are two checkboxes:
![JS/CSS include options]()

Checking *Do not include Bootstrap JavaScript and CSS includes on public pages.* doesn't actually remove *all* of the CSS and JS files. At a minimum, there are some LG-specific CSS overrides that are included in the header of every page and this checking this box doesn't remove those CSS overrides.

### Group-level
*Admin > Groups > select edit icon next to group > custom JS/CSS Code tab*

Below the code box are two checkboxes:

Checking *Exclude system level JS/CSS code.* only excludes the custom CSS and JS code added at the system level. It doesn't exclude any of the LG provided files. Per Springshare Support, it's not possible to exclude their files at the Group level.


## Frameworks
The website uses the Bootstrap and LandKit frameworks.