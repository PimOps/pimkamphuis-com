# Creating pimkamphuis.com

![pimkamphuis.com screenshot](/assets/img/pimkamphuiscom.jpeg?raw=true)

A wise man once told me to "always register your personal domain name as long as it is available." So, I did.

While I had no clear purpose for the domain, I did not want it to show the default domain registrar landing page. As an international graduate student and cloud freak I:

wanted a minimal, good looking and mobile friendly page with my personal details without spending much time on design
did not want to pay a premium for the .com domain registration
did not want to pay anything on webhosting
wanted the website to load fast all over the world (with good GTmetrix and Google PageSpeed Insights scores)
wanted to be able to edit the website easily and quickly from any device with automatic versioning
How did succeed?

## Don't pay a premium for a domain registration

[Cloudflare](https://cloudflare.com/) offers domain name registration at great value. They claim "You pay what we pay — you won’t find better value." and I tend to believe them. At the time of writing, registering a .com domain at Cloudflare sets you back $10 a year.

### Don't pay for webhosting

The awesomeness of Cloudflare doesn't stop at premium-free domain registration. Cloudflare offers a service called [Cloudflare Pages](https://pages.cloudflare.com/), a JAMstack platform for frontend developers to collaborate and deploy websites. And for a simple, single landing page like mine, it's totally [free](https://developers.cloudflare.com/pages/platform/limits/).

## Edit the website easily, anywhere with automatic versioning

By having my [Jeckyll](https://jekyllrb.com/) website repo in GitHub, I can access and edit the code directly using the online file editor. This is a great feature when you are on the go and need to make a quick change. The versioning is automatic and you can always revert back to a previous version if you mess up.

### Codespaces

And it gets even better. GitHub Codespaces allows you to have your development environment directly in the browser. By setting up a devcointainer.json file in the root of your repository, you can define the environment you need to run your code. This is great for when you want to write and test your changes in a cloud envirnonment.

### Deploy website via Cloudflare pages

Cloudflare provides a [simple yet comprehensive guide](https://developers.cloudflare.com/pages/framework-guides/deploy-a-jekyll-site/) to help you deploy your Jekyll site seamlessly. 

`bundle exec jekyll serve --livereload`
