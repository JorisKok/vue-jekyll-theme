# Jekyll VueJS theme


Free hosting with github pages, and VueJS for the nice single page feeling. Based on based on Type-on-strap theme.

### How it works

Create vue pages in `/vue/pages`. There are 3 types of pre-made components `<PageWithVideos>`, `<PageWithTags>` and `<PageWithRecentVideos>`. 
Look at the other pages to see how to build them and what data to parse. 

### Installation

##### Required: `npm`, `jekyll`

Install the node modules if you haven't

    npm install

To make sure the latest js file is compiled via js

    npm run build

To serve locally

    Jekyll serve

If you want to edit any vue template, best to test them with

    cp ./_site/index.html index.html 
    npm run dev

Note: `jekyll serve` generates it's own index.html into `/_site/index.html`, and uses `/pages/home.md`. 
You can then this index.html to test quickly with `npm run dev` if you want to make changes to the vue files.

### Editing this theme

1. Update the routes.js for new page routes
1. Add the page in pages (look at the existing ones to see how)
1. 

