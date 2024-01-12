# Milestone Project :one:

---

## :world_map: Strategy

---

### Project Goals

This is my milestone one project for the
[Code Institute's](http://www.codeinstitute.net) _'Level 5 Diploma in Web
Application Development'_. The goal is to demonstrate my ability to utilise HTML
and CSS, including CSS frameworks, to create a small, responsive, well-designed
and well-implemented website for a business, fictional or otherwise. For this
assignment I have chosen to create the webpage for my mother-in-law's dog
breeding business, 'Jenamins'.

#### User Goals

- Easy to find contact and location information
- Lots of pictures of cute puppies
- Gain insight into the running of the business, levels of professionalism,
  approachability and other factors relating to the decision to buy a puppy

#### Site Operator Goals

- Connect with more potential dog owners looking to purchase a puppy
- Promote the business more broadly
- A place to direct people looking for information
- Provide a way of potential customers to register their interest
- Show the customer what makes this company special
- Promote the family run and professional nature of the business
- Provide customers with information on currently available puppies and upcoming
  litters

#### Developer Goals

- Develop a site that satisfies the distinction requirements of the Code
  Institute
- Develop a site that satisfies the Goals of the Users and Operator as
  determined by the User Stories and Goals
- Use plain HTML, CSS and frameworks such as Bootstap to create a technically
  interesting and aestetically appealing site
- Use frameworks where necessary so as to not reinvent the wheel
- Create a responsive website that looks appealing on a variety of screensizes
  and devices
- Build a performant and efficient site, benchmarked used tools such as
  lighthouse, that is viewable on all modern browsers and devices

---

## :earth_africa: Scope

---

### User Experience

#### Target Audience

- Adults 18 and up
- Customers looking to buy a new puppy
- People interested in breeding their dogs
- People looking for pictures of cute puppies!

#### User Requirements and Expectations

- Easy navigation, plenty of breadcrumbs, back-to-the-top links/widgets and
  other quality of life features
- Accessible for colourblind, visually impared, and other users with
  accessibility needs
- All functionality presented works as expected and as intended
- Quick and easy access to contact details and location
- Plenty of images and a friendly aethetic presentation -Simple to use with
  logical flow and clear and straightforward navigation

#### User Stories

##### - First Time User

1. As a first time user I want to know who this company is
2. As a first time visitor I want to know what breeds of dogs Jenamin works with
3. As a first time user I want a smooth experience with easy access to the most
   important information (contact and location details)
4. As a first time user I want to see many pictures of puppies
5. As a first time user I want to not be frustrated with the layout or design of
   the site
6. As a first time user I would like to be easily able to contact the business
   with questions

##### - Returning User

1. As a returning user I would like to see new/different pictures
2. As a returning user I would like easy access to the Upcoming Litters page as
   I am looking for one in particular
3. As a returning user I would like to be able to find the business on social
   media
4. As a returning user I would like easy access to the contact and location
   details
5. As a returning customer I would like easy access to the various official
   information, registration numbers etc.

##### - Site Owner

1. As the site owner I would like to connect with potential customers and other
   breeders more easily and more cheaply
2. As the site owner I want to be able to easily see when a potential customer
   has contacted me through the website
3. As the site owner I would like the site to be well optimised for SEO in order
   to increase visibility
4. As the site owner I want potential customers to be able to contact/find us
   easily
5. As the site owner I want to make sure customers are never lost on my website

#### Identified tasks/needs the website should fulfil

| Task/Need                               | Importance: \*/5 |
| --------------------------------------- | ---------------- |
| Browsing pictures                       | 4                |
| Accessing contact details               | 5                |
| Discovering location                    | 5                |
| Finding out more about the company      | 3                |
| Gaining more information about the dogs | 4                |
| Information on upcoming litters         | 5                |
| Finding on Social sites                 | 3                |
| Ability to contact through website      | 3                |
| Easy navigation                         | 5                |
| Finding registration info               | 5                |

#### Accessibility

Accessibility needs should be considered and aria tags, semantic HTML tags, and
alt tags for images should all be clear descriptive and follow the w3
conventions.

Color palletes will be assessed for color-blind friendliness, and adjusted if
neccessary.

The structure of each page should be logical and allow keyboard navigation and
be screen-reader friendly

Site should contain a sitemap to aid with accessibility

---

## :bricks: Structure

---

The site needs to be structured in an intuitive and straight-forward way.
Constantly visible, consistent, navigation links; links back to the top of the
page for long pages, and other quality of life navigation features are
important. Site will be using a tree-style Information Architecture with links
back and forward available to the user at all times via the floating nav element
and/or the footer as well as a sitemap and breadcrumb trail indicating the users
current position on the site.

Links and navigation should be clear and unambiguous, interactive to highlight
them visually, and well-labelled to help with accessibility.

The website should consist of the following pages:

- **Landing page** - with a large hero image, some introductory content, nav bar
  and footer with social links and contact details. The nav bar and footer
  elements will be consistent and accessible across all pages of the site.

- **About Us** - A page detailing the staff and dogs involved,the story of the
  company and the owners, why and how it was started, credentials and other
  pertinent information.

- **Upcoming Litters** - A page to announce the latest news and for returning
  vistors to get updates.

- **Testimonials** - A page for customer testimonials, of which there are many,
  so smart presentation will be important. Combine this with the previously
  mooted gallery page.

- **Contact Us** - A page dedicated to contact and location information
  including a map and containg a styled webform to contact the business.

- **404 Page not found** - for mistypes/broken links

- **Privacy Policy** - link in footer and on contact page

The site should also make use of a 404 page that redirects the user back the
landing page, and a favicon to allow users to easily recognise the site amongst
bookmark lists.

Pages should be responsive and designed well for the three most common screen
sizes of phone, tablet, and desktop:

- 360x640px
- 768x1024px
- 1280x720px

Each page should consist of the same nav bar and footer, ensuring a consistent
User Experience.

The **Nav Bar** should contain the following elements:

1. Links to all five of the main pages
2. Logo, which also acts as a home link, as per convention
3. a fixed div above the main nav, in a solid colour displaying the main contact
   details of the business
4. Menu links should collapse into a burger on small breakpoints
5. Nav should either be sticky to the top of the viewport or spawn a 'return to
   top' link when not visible
6. Breadcrumbs beneath main nav indicating current position on site (eg: _Home >
   Contact Us_ )

The **Footer** should contain the following elements:

1. Copyright information
2. Social Links
3. Link to Privacy Policy
4. Link to Contact Us page
5. Map and address

---

## :skull_and_crossbones: Skeleton

---

### Wireframes

#### Navbar

- Mobile <br /> ![mobile navbar wireframe](docs/wireframes/mobile/header.png)
- Tablet <br />
  ![tablet navbar wireframe](docs/wireframes/tablet/tablet_header.png)
- Desktop <br />
  ![desktop navbar wireframe](docs/wireframes/desktop/desktop_header.png)

#### Footer

- Mobile <br />
  ![mobile footer wireframe](docs/wireframes/mobile/mobile_footer.png)
- Tablet <br />
  ![tablet footer wireframe](docs/wireframes/tablet/tablet_footer.png)
- Desktop <br />
  ![desktop footer wireframe](docs/wireframes/desktop/desktop_footer.png)

#### Landing Page

- Mobile <br />
  ![mobile landing page wireframe](docs/wireframes/mobile/mobile_landing_page.png)
- Tablet <br />
  ![tablet landing page wireframe](docs/wireframes/tablet/tablet_landing_page.png)
- Desktop <br />
  ![desktop landing page wireframe](docs/wireframes/desktop/desktop_landing_page.png)

#### About Us

- Mobile <br />
  ![Mobile About Us wireframe](docs/wireframes/mobile/mobile_about_us.png)

- Tablet <br/>
  ![tablet About Us wireframe](docs/wireframes/tablet/tablet_about_us.png)

- Desktop <br />
  ![Desktop About Us wireframe](docs/wireframes/desktop/desktop_about_us.png)

#### Testimonials

- Mobile <br />
  ![mobile Testimonials wireframe](docs/wireframes/mobile/mobile_gallery.png)

- Tablet <br/>
  ![tablet Testimonials wireframe](docs/wireframes/tablet/tablet_testimonials.png)

- Desktop
  ![desktop Testimonials wireframe](docs/wireframes/desktop/desktop_testimonials.png)

#### Upcoming Litters

- Mobile <br />
  ![mobile Upcoming Litters wireframe](docs/wireframes/mobile/upcoming_litters.png)

- Tablet <br/>
  ![tablet Upcoming Litters wireframe](docs/wireframes/tablet/tablet_upcoming_litters.png)

- Desktop
  ![desktop Upcoming Litters wireframe](docs/wireframes/desktop/desktop_upcoming_litters.png)

#### Contact Us

- Mobile <br />
  ![mobile Contact Us wireframe](docs/wireframes/mobile/mobile_contact_us.png)

- Tablet <br/>
  ![tablet Contact Us wireframe](docs/wireframes/tablet/tablet_contact_us.png)

- Desktop
  ![desktop Contact Us wireframe](docs/wireframes/desktop/desktop_contact_us.png)

---

## :art: Surface

---

### Design

#### Typography

Typography that emphasises the friendly and personable nature of the business. A
sans serif with rounded caps would be good for headers, following into a sans
serif for body text.

potential options for headers include:

- [Lato](https://fonts.google.com/specimen/Lato?preview.text=Who%20Are%20We%3F&preview.size=78&stroke=Sans+Serif)
- [Nunito](https://fonts.google.com/specimen/Nunito?preview.text=Who%20Are%20We%3F&preview.size=78&stroke=Sans+Serif)
- [Rubik](https://fonts.google.com/specimen/Rubik?preview.text=Who%20Are%20We%3F&preview.size=78&stroke=Sans+Serif)
- [Quicksand](https://fonts.google.com/specimen/Quicksand?preview.text=Jenamins%20-%20Dog%20Breeder&preview.size=78&stroke=Sans+Serif)
- [Dosis](https://fonts.google.com/specimen/Dosis?preview.text=Jenamins%20-%20Dog%20Breeder&preview.size=78&stroke=Sans+Serif)

potential options for body text include:

- [Work Sans](https://fonts.google.com/specimen/Work+Sans?preview.text=Hello%20Worldsdsd&preview.size=30&stroke=Sans+Serif&sort=popularity)
- [Open Sans](https://fonts.google.com/specimen/Open+Sans?preview.text=Hello%20Worldsdsd&preview.size=30&stroke=Sans+Serif&sort=popularity)
- [PT Sans](https://fonts.google.com/specimen/PT+Sans?preview.text=Hello%20Worldsdsd&preview.size=30&stroke=Sans+Serif&sort=popularity)
- [Cabin](https://fonts.google.com/specimen/Cabin?preview.text=Hello%20Worldsdsd&preview.size=30&stroke=Sans+Serif&sort=popularity)
- [Assistant](https://fonts.google.com/specimen/Assistant?preview.text=Hello%20Worldsdsd&preview.size=30&stroke=Sans+Serif&sort=popularity)

#### Colour Palettes

Site owner has requested that a ma jor component of the colour pallete be a
lilac/purple. I explored a number of palettes centered around this colour:

##### Lighter Colour Palettes

- **Colour Palette 1**
  ![light palette 1](/docs/images/colour_palettes/light2.png)

- **Colour Palette 2**
  ![light palette 2](/docs/images/colour_palettes/light3.png)
- **Colour Palette 3**
  ![light palette 3](/docs/images/colour_palettes/light4.png)

##### Midtone Colour Palettes

- **Colour Palette 1**
  ![midtone palette 1](/docs/images/colour_palettes/midrange.png)
- **Colour Palette 2**
  ![midtone palette 2](/docs/images/colour_palettes/midrange2.png)

##### Darker Colour Palettes

- **Colour Palette 1** ![dark palette 1](/docs/images/colour_palettes/dark.png)
- **Colour Palette 2** ![dark palette 2](/docs/images/colour_palettes/dark2.png)

#### Layout

### Technologies and Tools used

### Languages

- **CSS3**
- **HTML5**

### Tools

- **[Tilix](https://gnunn1.github.io/tilix-web/)**
- **[git](https://git-scm.com/)**
- **[VSCode for linux](https://code.visualstudio.com/)**
- **[GitHub](https://www.github.com)**
- **Chrome Dev Tools**
- **[Google Fonts](https://fonts.google.com/)**
- **[Pencil](https://pencil.evolus.vn/)**
- **[Coolors](https://coolors.co/)**

---

## :microscope: Testing

---

- Functional testing
- User Stories Testing
- Bug fixes
- HTML/CSS Validators
- WAVE
- Lighthouse
- Devices

---

## :loudspeaker: Deployment

---

---

## :heart: Credits and Acknowlegements

---
