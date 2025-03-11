# Contact Form withCSS variables, and Hosting on Github.io

Today we are going to make and style a contact form. We will then sprinkle in some CSS variables to change the "theme" easily, and wire it up with FormSpree. There are a lot of free contact form submission services, I just chose this one because it was quick and FREE.

- Make a quick form and create the base styles.
- Add some quick style variations with [CSS variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)
- Wire up the form action to [FormSpree](https://formspree.io/). You will have to sign up for an account and configure a form. Once we do this, keep that tab open!
- Copy our code over to a new repo and deploy using [Github Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

      /* Apply different IDs for Different Color Themes */
      #green {
        --c-bg: #a7f3d0;
        --c-text: #065f46;
        --c-bg-btn: #059669;
        --c-btn-hover: #065f46;
        --c-btn-text: #ecfdf5;
      }

      #blue {
        --c-bg: #1e3a8a;
        --c-text: #dbeafe;
        --c-bg-btn: #3b82f6;
        --c-btn-hover: #1d4ed8;
        --c-btn-text: #eff6ff;
      }
