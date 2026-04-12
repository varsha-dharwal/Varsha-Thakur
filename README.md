# Shopify Developer Test Submission

## Candidate
Varsha Dharwal

## Test Summary
This submission implements the requested Shopify page as two custom sections built from scratch:

- Custom Banner
- Custom Product Grid with Modal

No ready-made Dawn sections/components were used for the required implementation.

## Implemented Features

### 1. Custom Banner
- Editable content via Shopify customizer
- Desktop and mobile layouts
- Mobile hamburger / close interaction
- Button hover animation
- Custom styling built from scratch

### 2. Custom Product Grid
- 6 selectable product blocks
- Products selected dynamically through the Shopify customizer
- Responsive layout for desktop and mobile
- Hover interaction on product cards
- `+` hotspot opens the product modal

### 3. Product Modal
- Opens only from the `+` icon
- Displays:
  - product image
  - product title
  - product price
  - product description
  - dynamic variant options

### 4. Variant Selection
- Color shown first
- Size shown second
- Variant selection rendered dynamically from Shopify product data
- Custom size dropdown built with vanilla JavaScript

### 5. Add to Cart
- Implemented with Shopify AJAX Cart API
- Adds the exact selected variant
- Includes validation and console logs for debugging

### 6. Special Rule
When a product variant with:
- Color = Black
- Size = Medium

is added to cart, the product **Soft Winter Jacket** is also automatically added to the cart.

### 7. Cart UX
- Improved post-add-to-cart behavior
- Added cart handling fallback
- Prevented gift-guide sections from interfering with cart UX

## Tech Stack
- Shopify Liquid
- Vanilla JavaScript
- Custom CSS


## Git Workflow
- Working branch: `development`
- Submission flow: `development` → `main`

## Repository
[GitHub Repository](https://github.com/varsha-dharwal/Varsha-Thakur)

## Store Preview
Store URL: `https://varsha-48-teststore.myshopify.com`

## Notes
- Built according to the provided instructions
- Responsive behavior implemented
- Custom sections created from scratch

  ##Timestamp Credential
  dharwalvarsha1999@gmail.com
  p-Varsha@123CV&

## Thank You
Thank you for reviewing my submission.
