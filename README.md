# Affordable Furniture Covers Website

This is a responsive website for Affordable Furniture Covers, showcasing their products and services with a contact form that sends emails to Affordablepatiofurniturecovers@gmail.com.

## Features

- Responsive design that works on mobile, tablet, and desktop
- Product gallery showcasing various furniture covers
- Contact form that sends emails to Affordablepatiofurniturecovers@gmail.com
- Google Maps integration for location
- Modern, clean design with intuitive navigation

## Contact Form Implementation

The contact form uses the standard HTML `mailto` attribute to send emails directly to Affordablepatiofurniturecovers@gmail.com. When a user submits the form:

1. Their default email client (like Outlook, Gmail, etc.) will open
2. The email will be pre-filled with the information they entered in the form
3. The user needs to manually click "Send" in their email client

This approach doesn't require any external services or account creation, but it does require the user to have a configured email client on their device.

## How It Works

When a visitor fills out and submits the contact form:
1. The form data is collected
2. The user's default email client opens with a pre-filled email to Affordablepatiofurniturecovers@gmail.com
3. The visitor must manually click "Send" in their email client
4. The form resets after submission

## Limitations

This approach has some limitations:
- Requires users to have a configured email client
- Users must manually click "Send" in their email client
- May not work on all devices or browsers
- Some users may have email clients that block or filter these emails

## Alternative Solutions

For a more reliable solution, consider:
1. Using a service like EmailJS (requires account creation)
2. Setting up a backend server to handle form submissions
3. Using a form service like Formspree or Netlify Forms

## Customization

You can customize the website by modifying:
- `index.html` - For content changes
- `style.css` - For styling changes
- Images in the root folder - For visual updates

## Files Included

- `index.html` - Main website file with all content
- `style.css` - Styling for the website
- `README.md` - This file with setup instructions
- Various image files - Product photos and assets

## Support

For any issues or questions about the website:
1. Check that all EmailJS credentials are correctly entered
2. Verify that your EmailJS account is properly configured
3. Ensure you have an active internet connection
4. Check the browser console for any error messages

For further assistance with EmailJS, refer to the official documentation at [https://www.emailjs.com/docs/](https://www.emailjs.com/docs/)