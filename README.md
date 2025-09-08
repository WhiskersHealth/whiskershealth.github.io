# Whiskers Health Organisation Website

## Customizing Social Sharing Preview

To update the sharing preview (shown on Facebook, Twitter/X, LinkedIn, WhatsApp, Messages, etc.), edit the meta tags in the `<head>` section of `index.html`:

- **Title**: Change `og:title` and `twitter:title`.
- **Description**: Change `description`, `og:description`, and `twitter:description`.
- **Image**: Change `og:image` and `twitter:image` (recommended size: 1200x630px).
- **URL**: Change `og:url` if your site URL changes.
- **Twitter Handle**: Change `twitter:site` to your Twitter/X handle.
- **Site Name**: Change `og:site_name`.

Preview changes using Facebook Sharing Debugger or Twitter Card Validator.

---

## Updating Cats for Adoption

1. Open `index.html` and scroll to the "Cats for Adoption" section.
2. Each cat is represented by a card (HTML block) with their name, image, and details.
3. To add a new cat:
   - Copy an existing card block and paste it below the others.
   - Update the image URL, name, and details.
4. To remove a cat:
   - Delete the corresponding card block.
5. To update a cat's info:
   - Edit the name, image, or details in their card block.

For advanced updates, images are stored in `assets/images/`. Upload new images there and update the image URL in the card.

---

For further help, contact the site maintainer or refer to the comments in `index.html`.
