# BVA Bootcamp

## Basic References

- [Slate Docs](https://shopify.github.io/slate/docs/about)
- [Design](https://invis.io/UESZF1LWHMS)

## Module 1 - Navigation

[Design](https://projects.invisionapp.com/d/main/#/console/18021715/373903262/inspect)

### Objectives

Build a global navigation using linklists and a snippet based on the provided design.

### Learning Points

- Snippets
- SVGs as Snippets
- Images in Shopify
- Linklists
- Liquid Loops

### Requirements

- Use a snippet file for the Liquid/HTML of the Navigation
- Add your snippet file to theme.liquid so that it's global
- Use the already created linklist called "Main menu" for the links on the right
- Use a liquid loop to loop over the links within the linklist
- Convert SVG files into snippets and use the snippets within the navigation for the icons on the right

### Helpful Links

- [Includeing Snippets](https://help.shopify.com/en/themes/liquid/tags/theme-tags#include)
- [Linklist Object](https://help.shopify.com/en/themes/liquid/objects/linklist)
- [Link Object](https://help.shopify.com/en/themes/liquid/objects/link)
- [Liquid Loops](https://help.shopify.com/en/themes/liquid/tags/iteration-tags#for)
- [Forloop Object](https://help.shopify.com/en/themes/liquid/objects/for-loops)

## Module 2 - Homepage Hero Section

[Design](https://projects.invisionapp.com/d/main/#/console/18021715/373903262/inspect)

### Objectives

Create the index template with a homepage hero section using Shopify sections

### Learning Points

- Sections
  - What is a section?
  - How does it work, schema? (theme settings)
  - Limitations
- Image Object
- Image Filters

### Helpful Links

- [Index Template](https://help.shopify.com/en/themes/development/templates/index-liquid)
- [Shopify Schema](https://help.shopify.com/en/themes/development/theme-editor/settings-schema)
- [Shopify Sections](https://help.shopify.com/en/themes/development/sections)
- [Image Object](https://help.shopify.com/en/themes/liquid/objects/image)
- [Image Filters](https://help.shopify.com/en/themes/liquid/filters/url-filters)

## Module 3 - Homepage Shop Products Section & Reusable Product Tile

[Design](https://projects.invisionapp.com/d/main/#/console/18021715/373903262/inspect)

### Objectives

Build a product recommendations section that allows the merchant to display 4 products of their choosing. To prevent code duplication use a snippet for the product tile.

### Learning Points

- Blocks in Sections
- Products
- Money Filters

### Requirements

- Use a section with repeatable blocks
- Each block should allow the user to select a product
- Limit the amount of blocks to 4
- Use a liquid loop to iterate over the section blocks
- Use a snippet for displaying the product tile

### Helpful Links

- [Product Object](https://help.shopify.com/en/themes/liquid/objects/product)
- [Money Filters](https://help.shopify.com/en/themes/liquid/filters/money-filters)
- [Image/URL Filters](https://help.shopify.com/en/themes/liquid/filters/url-filters)
- [Shopify Sections](https://help.shopify.com/en/themes/development/sections)
- [Shopify Schema](https://help.shopify.com/en/themes/development/theme-editor/settings-schema)

## Module 4 - Collection Banner

[Design](https://projects.invisionapp.com/d/main/#/console/18021715/373903263/inspect)

### Objectives

Create a collection template that showcases the collection title, description and main image in a banner at the top of the page.

### Learning Points

- Collections
- Featured Image

### Requirements

- Create a banner using the collection image
- Overlay the collection title & description text on top of the banner

### Helpful Links

- [Collection Template](https://help.shopify.com/en/themes/development/templates/collection-liquid)
- [Collection Object](https://help.shopify.com/en/themes/liquid/objects/collection)
- [Image Filters](https://help.shopify.com/en/themes/liquid/filters/url-filters)

## Module 5 - Collection List

[Design](https://projects.invisionapp.com/d/main/#/console/18021715/373903263/inspect)

### Objectives

Create a collection product grid that uses pagination.

### Learning Points

- Collection Products
- Connection between different Shopify objects (collection, product, variant, etc)
- Pagination

### Requirements

- Use a loop to iterate through the collection products
- Re-use the product tile snippet
- Paginate the collection, 8 products per page, 4 products per row
- Use the default pagination filter tag to display additional page links

### Helpful Links

- [Paginate A Collection](https://help.shopify.com/en/themes/customization/collections/show-more-products-on-collection-pages)
- [Paginate Object](https://help.shopify.com/en/themes/liquid/objects/paginate)
- [Pagination Filters](https://help.shopify.com/en/themes/liquid/filters/additional-filters#default_pagination)
- [Collection Template](https://help.shopify.com/en/themes/development/templates/collection-liquid)
- [Collection Object](https://help.shopify.com/en/themes/liquid/objects/collection)

## Module 6 - Product Main Section

[Design](https://projects.invisionapp.com/d/main/#/console/18021715/373903264/inspect)

### Objectives

Create a product template that displays a 50/50 layout with production information and add-to-cart functionality.

### Learning Points

- Deeper Understanding of Products
- Further Liquid Filters
- Product Form
- Add To Cart

### Requirements

- Build a 50/50 template
- Display the product featured image, title, price and description
- Create a variant dropdown using a loop
- Use a product form tag to handle add-to-cart

### Helpful Links

- [Product Template](https://help.shopify.com/en/themes/development/templates/product-liquid)
- [Product Object](https://help.shopify.com/en/themes/liquid/objects/product)
- [Variant Object](https://help.shopify.com/en/themes/liquid/objects/variant)
- [Money Filters](https://help.shopify.com/en/themes/liquid/filters/money-filters)
- [Image/URL Filters](https://help.shopify.com/en/themes/liquid/filters/url-filters)

## Module 7 - Cart Page

[Design](https://projects.invisionapp.com/d/main/#/console/18021715/373903265/inspect)

### Objectives

Build a cart page that displays the products that are in the user’s cart, shows the total price and allows the user to remove any specific product from their cart.

### Learning Points

- Cart
- Line Items

### Requirements

- Use a loop to display the contents or the cart
- Use a snippet to display each line item
- Create a link to remove individual products from the cart
- Use the cart form to submit the cart to checkout

### Helpful Links

- [Cart Object](https://help.shopify.com/en/themes/liquid/objects/cart)
- [Line Item Object](https://help.shopify.com/en/themes/liquid/objects/line_item)

## Going Beyond

- Continue this exercise by building out the more advanced version of this demo theme
- [Advanced Design](https://invis.io/9HSZF1X2YRF)
