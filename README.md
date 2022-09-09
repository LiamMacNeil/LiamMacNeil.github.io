#
# This file contains configuration flags to customize your site
#

# Name of your site (displayed in the header)
name: Liam M. MacNeil

# Short bio or description (displayed in the header)
description: Ecosystem Modelling Group at GEOMAR Helmholtz Zentrum für Ozeanforschung Kiel

# URL of your avatar or profile pic (you could use your GitHub profile pic)
avatar: https://raw.githubusercontent.com/danielgboyce/danielgboyce.github.io/master/images/profpic2.jpg
# Flags below are optional
#

# Includes an icon in the footer for each username you enter
footer-links:
  googlephotos: photos.google.com/u/0/collections
  bitbucket: 
  researchgate: https://www.researchgate.net/profile/Liam-Macneil-2
  googlescholar: https://scholar.google.com/citations?user=1PrROC8AAAAJ&hl=en
  email: lmacneil@geomar.ca
  github: LiamMacNeil/



# Your disqus shortname, entering this will enable commenting on posts
disqus: 

# Enter your Google Analytics web tracking code (e.g. UA-2110908-2) to activate tracking
google_analytics: UA-66516453-1

# Your website URL (e.g. http://barryclark.github.io or http://www.barryclark.co)
# Used for Sitemap.xml and your RSS feed
url: https://github.com/LiamMacNeil/LiamMacNeil.github.io

# If you're hosting your site at a Project repository on GitHub pages 
# (http://yourusername.github.io/repository-name)
# and NOT your User repository (http://yourusername.github.io)
# then add in the baseurl here, like this: "/repository-name"
baseurl: ""

#
# !! You don't need to change any of the configuration flags below !!
#

markdown: kramdown
highlighter: rouge
permalink: /:title/

# The release of Jekyll Now that you're using
version: v1.0.0

# Set the Sass partials directory, as we're using @imports
sass:
  sass_dir: _scss
  style: :expanded # You might prefer to minify using :compressed

# Use the following plug-ins
gems:
  - jemoji # Emoji please!
  - jekyll-sitemap # Create a sitemap using the official Jekyll sitemap gem

# Exclude these files from your production _site
exclude:
    - Gemfile
    - Gemfile.lock
    - LICENSE
    - README.md
Footer

