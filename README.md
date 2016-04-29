# UI-DataScience.github.io

Website for Data Science at the University of Illinois

http://ui-datascience.github.io/

# Adding Content

There are currently 4 types of supported 'posts':

* News
* Projects
* Data
* Papers

All of these posts go in the `_posts` directory of the GitHub repository for this site. It is necessary to get the YAML correct in order for the post to show up correctly and in the correct portion of the site. It's also necessary to get the naming convention of the post correct: `YYYY-MM-DD-{name}.markdown`. Check out the `_posts` directory for examples.

### News

Shows up in the [News](http://ui-datascience.github.io/news) section of the site. Example YAML:

```
---
layout: post
title:  "Hello World!"
date:   2016-02-28 22:01:00 -0600
categories: post
---
```

### Projects

Shows up in the [Ongoing Projects](http://ui-datascience.github.io/projects) section of the site. Example YAML:

```
---
layout: post
title:  "News Article Geocoding"
date:   2016-03-19 15:15:00 -0600
categories: project
---
```

### Data

Shows up in the [Data](http://ui-datascience.github.io/data) section of the site. Example YAML: 

```
---
layout: post
title: "SDSS DR7 Galaxy Correlation Function Data"
date: 2013-12-16
categories: data
summary: "We have released our SDSS DR7 two-point galaxy angular correlation function measurements and corresponding covariance matrices."
---
```

### Papers

Shows up in the [Papers](http://ui-datascience.github.io/papers/) section of the site. Example YAML:

```
---
layout: post
title: "The SDSS DR7 Galaxy Angular Power Spectrum: Volume-Limits and Galaxy Morphology"
date: 2013-02-01
categories: papers
summary: "We calculate the SDSS DR7 galaxy angular power spectrum."
authors: "Brett Hayes, Robert J. Brunner"
---
```
# Known Issues

### Broken Links

### Other Issues

### Future Work
* Fix UNDER CONSTRUCTION sections

# Changing the Theme

* Go get a theme from [Bootswatch](https://bootswatch.com/)
* Put it in the `css` directory
* Edit the line in `_includes/custom_head.html` below to find the new file (not the one that calls `syntax.css`

`<link rel="stylesheet" href="{{ "/css/spacelab.css" | prepend: site.baseurl }}">`

