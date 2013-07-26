---
layout: default
title: 'wp blog create'
---

`wp blog create` - Create a blog in a multisite install.

### OPTIONS

	--slug=<slug>
			Path for the new blog. Subdomain on subdomain installs, directory on subdirectory installs.

	--title=<title&gt;
			Title of the new blog. Default: prettified slug.

	--email=<email>
			Email for Admin user. User will be created if none exists. Assignement to Super Admin if not included.

	--site_id=<site-id>
			Site (network) to associate new blog with. Defaults to current site (typically 1).

	--private
			If set, the new blog will be non-public (not indexed)

	--porcelain
			If set, only the blog id will be output on success.

