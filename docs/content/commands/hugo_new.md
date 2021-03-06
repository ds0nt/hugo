---
date: 2015-05-21T20:03:19+02:00
title: "hugo new"
slug: hugo_new
url: /commands/hugo_new/
---
## hugo new

Create new content for your site

### Synopsis


Create a new content file and automatically set the date and title.
It will guess which kind of file to create based on the path provided.
You can also specify the kind with -k KIND
If archetypes are provided in your theme or site, they will be used.


```
hugo new [path]
```

### Options

```
  -f, --format="toml": frontmatter format
  -h, --help=false: help for new
  -k, --kind="": Content type to create
```

### Options inherited from parent commands

```
  -b, --baseUrl="": hostname (and path) to the root eg. http://spf13.com/
  -D, --buildDrafts=false: include content marked as draft
  -F, --buildFuture=false: include content with publishdate in the future
      --cacheDir="": filesystem path to cache directory. Defaults: $TMPDIR/hugo_cache/
      --config="": config file (default is path/config.yaml|json|toml)
  -d, --destination="": filesystem path to write files to
      --disableRSS=false: Do not build RSS files
      --disableSitemap=false: Do not build Sitemap file
      --editor="": edit new content with this editor, if provided
      --ignoreCache=false: Ignores the cache directory for reading but still writes to it
      --log=false: Enable Logging
      --logFile="": Log File path (if set, logging enabled automatically)
      --pluralizeListTitles=true: Pluralize titles in lists using inflect
  -s, --source="": filesystem path to read files relative from
      --stepAnalysis=false: display memory and timing of different steps of the program
  -t, --theme="": theme to use (located in /themes/THEMENAME/)
      --uglyUrls=false: if true, use /filename.html instead of /filename/
  -v, --verbose=false: verbose output
      --verboseLog=false: verbose logging
```

### SEE ALSO
* [hugo](/commands/hugo/)	 - hugo builds your site
* [hugo new site](/commands/hugo_new_site/)	 - Create a new site (skeleton)
* [hugo new theme](/commands/hugo_new_theme/)	 - Create a new theme

###### Auto generated by spf13/cobra at 2015-05-21 18:03:19.80134962 +0000 UTC
