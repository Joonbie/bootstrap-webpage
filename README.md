# Coding with bootstrap

This is a solution to the Weekend Challenge that was given by my mentor in my bootcamp

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

So, here's the challenge statement. Create the following responsive Homepage using the readily available bootstrap samples - and to include the following specifications:

- navigation bar with links: e.g. home about, products, contact
- banner section with a call-to-action button "Start Now"
- newsletter section for users to subscribe to your newsletter (before submitting, the input should be validated to accept an email address only)

### Screenshot

![](./assets/img/desktop%20view.png)

### Links

- Solution URL: [Github Repo](https://github.com/Joonbie/bootstrap-webpage)
- Live Site URL: [Github Pages](https://joonbie.github.io/bootstrap-webpage/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow
- [Bootstrap](https://getbootstrap.com) - Bootstrap Library

### What I learned

This was the first time that I had to work with Bootstrap. It was really challening trying to get the hang of things.

The most challenging part for me was to get the "Hero Section" to align properly.

I got stuck on the cta buttons due to it spanning the whole width of the webpage when I had the div outside of the col-md-5 div.

After lots of trial and error I was finally able to figure it out and nested the div inside of it and it worked like a charm.

Below is the hero section that im proud of 😁

```html
<!-- Start of hero -->
<section class="hero">
  <div class="container">
    <div class="row">
      <!-- Hero text area -->
      <div class="col-md-5">
        <div class="hero-title fw-bold">Paw Buddies</div>
        <p class="mt-3 text-secondary">
          Come and shop our wide variety of Pet Accessories, Toys and Pet food
        </p>

        <!-- Call to action -->
        <div class="cta mt-5 d-flex">
          <a href="#" class="btn btn-primary border-0 shadow-none me-3"
            >Shop Now</a
          >
          <a href="#" class="btn btn-secondary btn-light shadow-none"
            >Explore Products</a
          >
        </div>
      </div>

      <!-- Hero image section -->
      <div class="col-md-5">
        <img
          src="assets/img/Pompom.png"
          alt="hero img"
          class="hero-image mx-auto w-100"
        />
      </div>
    </div>
  </div>
</section>
```

### Continued development

I will take on more side projects using bootstrap when i have the time over the weekend as I can see the potential usage for it.

### Useful resources

- [Bootstrap Documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/) - This helped me for referring to the vast array of things that bootstrap can do.

## Author

- Website - [Github Repo](https://github.com/Joonbie)

## Acknowledgments

I would like to give special thanks to my Mentor Martin for giving me some insights when I was facing some diffulties on this challenge.
