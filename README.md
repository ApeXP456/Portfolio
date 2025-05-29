# Contact Form Website
[![Netlify Status](https://api.netlify.com/api/v1/badges/28c7c174-a657-441e-a137-fd53d85ca7e5/deploy-status)](https://app.netlify.com/projects/jarodcunningham/deploys)

Visit the Website here:
https://jarodcunningham.netlify.app/

This is a sleek, dark-themed contact form website built with HTML, CSS, and integrated with [FormSubmit](https://formsubmit.co) for backend-free form submissions. The site includes a styled submission form, a custom thank-you page, and responsive layout optimized for deployment (e.g., Netlify).

## 🚀 Features

- Fully responsive design
- Dark theme UI
- Styled input fields with hover and focus states
- No backend required — powered by [FormSubmit](https://formsubmit.co)
- Redirects to a custom thank-you page after form submission
- Organized structure ready for deployment

## 🧱 Built With

- **HTML5** — Semantic structure
- **CSS3** — Custom styling with CSS variables
- **JS** - Sidebar, testimonials modal, custom select filtering, form validation, and page navigation.
- **FormSubmit** — Email form backend without server code

## 📂 Project Structure
├── index.html # Main webpage with the contact form  
├── thank-you.html # Confirmation page after submission  
├── /assets  
│ └── /css  
│ └── style.css # Custom theme and form styling

│ └──images # Folder of favicons, pdf's and other images

## 🔧 How It Works

1. User fills out the contact form.
2. FormSubmit processes and sends the submission to the configured email.
3. On success, user is redirected to `thank-you.html`.

> **Note:** FormSubmit requires your email to be verified via a confirmation link the first time you receive submissions.

## 🛠️ Configuration

To use your own email:
1. Replace the email in the form’s `action` attribute:

```html
<form action="https://formsubmit.co/your-email@example.com" method="POST">
```

## 💡 Deployment

This site is Netlify-ready. 

## 📬 Contact

Created by **[Jarod Cunningham]**  
Feel free to reach out!
