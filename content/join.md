---
title: Join
---

🧊 Club is a very cool webring, and you can be part of it if you like.

## What a webring is

If you're in the webring, your website is listed on this website. You'll also
have a little set of buttons on your website like this:

⬅️🧊➡️

These will let visitors to your website click between sites in the webring,
hopefully discovering other cool websites and leading cool folks to discover
your cool website in turn.

## Rules

We do have some rules about what kind of sites we would like to be in the
webring:

- Any form of hate is, obviously, not allowed.
- It must be a personal website that you own and is for you, not a company or
something.
- You must display the buttons on your website, otherwise you'll break the
chain!
- We don't want any content that is pro-crypto, generative AI, web3, etc. The
point of the personal web is to get away from this stuff.
- We reserve the right to remove any dead links from the webring.
- We strongly prefer blogs to be part of the webring, ideally ones updated
somewhat regularly, but we're prepared to bend this rule if your site is really
cool.

## How to join

Create an [issue](https://github.com/JoelOtter/cool-club/issues) in our GitHub
repo (or a PR if you're feeling brave). The info we need looks like this:

```yaml
---
# Your name or website name
name: Joel Auterson
# The next number in the chain (we can give you this)
weight: 2 
# Your website
site: https://joelotter.com 
# An image. This can be a relative URL if hosted on your
# site, or an absolute URL for one from elsewhere.
image: /img/profile.jpg 
# (Optional) The RSS feed on your website, if you have one.
feed: /posts/index.xml
---

A description of your site, in a few sentences.

```

The file should be `yourname.md`, e.g. `joel.md` or `pat.md`.

To be added, you also need to add the buttons to your website:

```html
<p>
  <a href="https://join-the-cool.club/members/yourname?prev" style="text-decoration: none">⬅️</a>
  <a href="https://join-the-cool.club/members/yourname" style="text-decoration: none">🧊</a>
  <a href="https://join-the-cool.club/members/yourname?next" style="text-decoration: none">➡️</a>
</p>
```

And you're done. Welcome to 🧊 Club!
