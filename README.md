## Hi Friends

I build web sites for [Murmur Creative](https://github.com/murmurcreative), a branding, packaging, and web agency (and a certified B-corp), 
and I [help out users](https://discourse.roots.io/) of the Roots stack as part of the [Roots team](https://github.com/roots) (and occasionally contribute code). I like writing code and documentation.

When I'm not doing those things, I enjoy 

- 📷 [amateur photography](https://photos.alwaysblank.org) 
- ☕ [coffee](https://www.nossacoffee.com/)
- 🐕 hanging out with my dogs

### Things I've Built

Perhaps you'll find some of them useful!
Perhaps not.
But here they are anyway.

- **[11in](https://github.com/11in)** - The core item here is [elfin](Elfin) which is a sort of starter kit for [11ty](https://11ty.dev) that I built to make my life easier.
    Also in that organization are some related packages that add or modify various bits of functionality.
    Useful stuff if you're into static sites, or want to get into static sites.
- **plumbing** - These are several different tiny packages I made to help with small tasks in WordPress that I kept "solving".
    - [normalize-links](https://github.com/alwaysblank/plumbing-normalize-links) - Makes it a bit easier to use and interact with the arrays returns by ACF's "link" field type.
    - [templates](https://github.com/alwaysblank/plumbing-templates) - Allows you to set specific directories for custom templates for pages (and custom post types) in WordPress. 
    - [responsive-images](https://github.com/alwaysblank/plumbing-responsive-images) - Wrapper for handling generating responsive images when using WordPress.
    - [acf](https://github.com/alwaysblank/plumbing-acf) - Slim interface over ACF's `get_field()` that mostly just adds the ability to get several fields at once--and the ability to provide defaults and run callbacks on those fields individually.
- **[brief](https://github.com/alwaysblank/brief)** - Useful for handling collections of data where you need to gracefully handle non-existence of individual items.
    More useful than an array, less useful (but also lighter) than Laravel Collections.
