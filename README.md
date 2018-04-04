# Media Queries Advanced - Responsive Dashboard

## Context
We are practicing more advanced layouts and using media queries to change the behavior of elements to create interactive components.

## The Assignment
The interactive components we want to modify are:

- The positioning of the navigation menu
  - _mobile_ : on the bottom, icons aligned left
  - _tablet_ : on the left side
  - _desktop_ : on the top, icons aligned right

- The increase in the font size of the title ('Space')
  - _mobile_ : font-size 42px
  - _tablet_ : font-size 56px
  - _desktop_ : font-size

- The positioning of the 'Go There', 'Cancel' buttons
  - _mobile_ : vertical
  - _tablet +_ : horizontal

- The showing of the Search Icon/Text
  - _mobile_ : Show Icon
  - _tablet +_ : Show 'Search' text

- The Option Icon Groups
  - _mobile_ : 2 columns
  - _tablet_ : 3 columns
  - _desktop_ : 6 columns

Do what you have to do to make it work. Note: you will only need to modify the `scss/main.scss` file.

You should also be using the `watch-scss` build to compile your scss to css.

## The mockups

#### Mobile
![mobile](mockups/act-mockup-mobile.png)

#### Tablet
![tablet](mockups/act-mockup-tablet.png)

#### Desktop
![desktop](mockups/act-mockup-desktop.png)


## Setup

```sh
# (1) Go to your ~/muktek/assignments directory
cd ~/muktek/assignments

# (2) Clone this repository + remove the origin
git clone https://github.com/muktek/assignment--responsive-dashboard.git
git remote remove origin

# (3) create your own repo on github
# (4) connect your local with the remote
git remote add origin «....your repo name....»

# (5) start the scss watch task and go to work in `main.scss`
watch-scss

```
