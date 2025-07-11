# zoisroupas.dev

A terminal based portfolio theme forked from [CodeNerve](https://github.com/CodeNerve/CodeNerve.github.io) and adjusted to my needs.

## Customization

Just [clone](https://github.com/roupasz/roupasz.github.io.git) or [download](https://github.com/roupasz/roupasz.github.io/archive/master.zip) this project


[download this project](https://github.com/bencentra/centrarium/archive/master.zip) and add all the files to your project. Add your blog posts to the `posts/` directory, and create your pages with the proper Jekyll front matter (see `posts.html` for an example).

You can customize 

## Configuring a custom domain for your GitHub Pages site

GitHub Pages supports using custom domains, or changing the root of your site's URL from the default, like zroupas.github.io, to any domain you own.

You can find detailed information in [Github's Offical docs][custom-domain] but in a nutshell, you have to point your root domain (example.com, not : www.example.com, blog.example.com, etc) to the IP addresses of GitHub Pages site via your DNS hosting provider's panel.

This involves setting A records in your DNS configuration pointing to GitHub’s IPs for apex domains:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```
And optionally adding a CNAME record for www.example.com pointing to your GitHub Pages site.