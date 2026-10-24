# Pet Health Blog

This is a pet health blog I put together about 2 years ago while I was doing my A/Ls. It's a static site — plain HTML and CSS, nothing fancy. I built it as a side project to learn web development basics, and it ended up covering the stuff I actually care about when it comes to keeping pets healthy: nutrition, general health tips, mental wellbeing, and a way for people to get in touch.

Looking back at it now, there's definitely stuff I'd do differently, but it was a solid learning experience and I'm still kinda proud of how it turned out.

## What's in here

- **Home Page** — Landing page with a hero, a quick intro, and previews of the latest posts
- **Pet Health Tips** — Fleas & ticks, vaccinations, parasite control, exercise, oral hygiene, grooming
- **Pet Nutrition** — The basics (protein, fat, carbs, vitamins) plus a breakdown of food options (kibble, canned, raw, homemade)
- **Mental Health** — The power of pets, emotional support animals, pet-assisted therapy, and dealing with pet loss
- **Contact Us** — A bit about me, my contact details, and a form to send a message

There's also a "follow along" section on every page with links to social media, and a contact/question form on a couple of the pages.

## Folder layout
pet-health-blog/
├── html/
│ ├── Home Page.html
│ ├── Pet Health.html
│ ├── Pet Nutrition.html
│ ├── PetMentalHealth.html
│ └── ContactUs.html
├── css/
│ ├── HomePage.css
│ ├── Pet Health.css
│ ├── Pet Nutrition.css
│ ├── PetMentalHealth.css
│ └── ContactUs.css
├── images/
│ ├── logo.png
│ ├── (all the article images)
│ └── 19.mp4
└── README.md



## Running it

No build step, no dependencies. Just open `html/Home Page.html` in your browser.

If you want to be a bit more proper about it (recommended because of the relative paths), spin up a local server:

Python
python -m http.server 8000

# Or just use VS Code's Live Server extension


Then go to http://localhost:8000/html/Home%20Page.html.

Built with
HTML5

CSS3

A single embedded .mp4 for the nutrition section

That's it. No frameworks, no JavaScript. I kept it simple because I was still getting comfortable with the basics back then.

About the images
The images are pulled from various pet-related sites — I've left credit links in the credit attributes on the <img> tags. If you're going to redistribute this, double-check the licensing on those or swap them out for your own. I'm not the owner of most of them.
