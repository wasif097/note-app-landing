# Automatic App Landing Page
**Create and deploy an iOS app landing page on GitHub Pages in only five minutes.**

Designed for GitHub Pages for super easy set up. 

🔧 Fork this repo

🗝 Enter iOS App ID in `_config.yml`

📲 Upload video preview or screenshot

🎨 Customise site in `_config.yml` (no HTML/CSS)

📝 Write Privacy Policy as markdown in `privacypolicy.md`

🕒 Keep a changelog in `CHANGELOG.md`

✅ Site becomes live at GitHub Pages repository URL, e.g. `https://your-username.github.io/your-repo-name/`.

<img src="https://emilbaehr.com/files/jayson1.png" width="440"> <img src="https://emilbaehr.com/files/slor1.png" width="440">




## Quick Start

### Step 1: Fork this repo.
After forking the repo, your site will be live immediately on your personal Github Pages account, e.g. `https://yourusername.github.io/your-repo-name/`.

*Make sure GitHub Pages is enabled for your repo. It might take some time for the site to propagate entirely.*



### Step 2: Enter iOS App ID in `_config.yml`
Enter your iOS app ID in the `ios_app_id` field and commit your changes. Your site will automatically rebuild with your app icon, name, price and link to App Store.

You can go on with customising almost anything in the `_config.yml` file. 

Things you can customise in `_config.yml`:
- App Name
- App Icon
- App Description
- App Price
- App Store Link
- Play Store Link
- Press Kit Download Link
- Cover Image
- Cover Overlay Color
- Background Color
- Text Colors
- iPhone Device Color
- Your Name / Company Name
- Link to Website
- Social Links and Contact Info
- Feature List (Title, text, icon)



### Step 3: Add screenshot or video

#### Adding a screenshot
Upload a `.png` or `.jpg` of your app to the folder `assets/screenshot/`. The name does not matter. Be sure to delete the placeholder `yourscreenshot.png`.

#### Adding video
Upload your video to the folder `assets/videos/`. To have support for most browsers, you need to upload two files – one for Safari and one for Chrome/Firefox.

Video formats supported by Chrome and Firefox:
- `.webm`
- `.ogg`

Video formats supported by Safari:
- `.mp4`
- `.mov`

#### Resolutions
The videos and screenshots must have one of the following resolutions:
- 828x1792
- 1125x2436
- 1242x2688



### Step 4: Edit (or remove) Privacy Policy and Changelog
Your site automatically includes pages for a Privacy Policy and a Changelog. Change the content of these pages by editing the `privacypolicy.md` and `CHANGELOG.md` files in the `_pages` directory.

In each of the markdown files, you can set the `include_in_header:` value to either `true` or `false`. This determines if the page is included in the top navigation.
By default, only the Changelog is included in the top navigation. The title of the navigation item can also be edited, by editing the `title:` in each markdown file.

If you need to, you can create additional markdown based pages just by creating an `.md` file like the `privacypolicy.md` and `CHANGELOG.md` files in the `_pages` directory.

**Please note:** The Privacy Policy and Changelog provided are written using dummy text, so please adapt each of them for your own app.
You can also choose not to include these pages, by simple deleting the `privacypolicy.md` and `CHANGELOG.md` files.

## Subscribe

<!-- Begin Brevo Form -->
<!-- START - We recommend to place the below code in head tag of your website html  -->
<style>
  @font-face {
    font-display: block;
    font-family: Roboto;
    src: url(https://assets.brevo.com/font/Roboto/Latin/normal/normal/7529907e9eaf8ebb5220c5f9850e3811.woff2) format("woff2"), url(https://assets.brevo.com/font/Roboto/Latin/normal/normal/25c678feafdc175a70922a116c9be3e7.woff) format("woff")
  }

  @font-face {
    font-display: fallback;
    font-family: Roboto;
    font-weight: 600;
    src: url(https://assets.brevo.com/font/Roboto/Latin/medium/normal/6e9caeeafb1f3491be3e32744bc30440.woff2) format("woff2"), url(https://assets.brevo.com/font/Roboto/Latin/medium/normal/71501f0d8d5aa95960f6475d5487d4c2.woff) format("woff")
  }

  @font-face {
    font-display: fallback;
    font-family: Roboto;
    font-weight: 700;
    src: url(https://assets.brevo.com/font/Roboto/Latin/bold/normal/3ef7cf158f310cf752d5ad08cd0e7e60.woff2) format("woff2"), url(https://assets.brevo.com/font/Roboto/Latin/bold/normal/ece3a1d82f18b60bcce0211725c476aa.woff) format("woff")
  }

  #sib-container input:-ms-input-placeholder {
    text-align: left;
    font-family: "Helvetica", sans-serif;
    color: #c0ccda;
  }

  #sib-container input::placeholder {
    text-align: left;
    font-family: "Helvetica", sans-serif;
    color: #c0ccda;
  }

  #sib-container textarea::placeholder {
    text-align: left;
    font-family: "Helvetica", sans-serif;
    color: #c0ccda;
  }
</style>
<link rel="stylesheet" href="https://sibforms.com/forms/end-form/build/sib-styles.css">
<!--  END - We recommend to place the above code in head tag of your website html -->

<!-- START - We recommend to place the below code where you want the form in your website html  -->
<div class="sib-form" style="text-align: center;
         background-color: #EFF2F7;                                 ">
  <div id="sib-form-container" class="sib-form-container">
    <div id="error-message" class="sib-form-message-panel" style="font-size:16px; text-align:left; font-family:&quot;Helvetica&quot;, sans-serif; color:#661d1d; background-color:#ffeded; border-radius:3px; border-color:#ff4949;max-width:540px;">
      <div class="sib-form-message-panel__text sib-form-message-panel__text--center">
        <svg viewBox="0 0 512 512" class="sib-icon sib-notification__icon">
          <path d="M256 40c118.621 0 216 96.075 216 216 0 119.291-96.61 216-216 216-119.244 0-216-96.562-216-216 0-119.203 96.602-216 216-216m0-32C119.043 8 8 119.083 8 256c0 136.997 111.043 248 248 248s248-111.003 248-248C504 119.083 392.957 8 256 8zm-11.49 120h22.979c6.823 0 12.274 5.682 11.99 12.5l-7 168c-.268 6.428-5.556 11.5-11.99 11.5h-8.979c-6.433 0-11.722-5.073-11.99-11.5l-7-168c-.283-6.818 5.167-12.5 11.99-12.5zM256 340c-15.464 0-28 12.536-28 28s12.536 28 28 28 28-12.536 28-28-12.536-28-28-28z" />
        </svg>
        <span class="sib-form-message-panel__inner-text">
                          Your subscription could not be saved. Please try again.
                      </span>
      </div>
    </div>
    <div></div>
    <div id="success-message" class="sib-form-message-panel" style="font-size:16px; text-align:left; font-family:&quot;Helvetica&quot;, sans-serif; color:#085229; background-color:#e7faf0; border-radius:3px; border-color:#13ce66;max-width:540px;">
      <div class="sib-form-message-panel__text sib-form-message-panel__text--center">
        <svg viewBox="0 0 512 512" class="sib-icon sib-notification__icon">
          <path d="M256 8C119.033 8 8 119.033 8 256s111.033 248 248 248 248-111.033 248-248S392.967 8 256 8zm0 464c-118.664 0-216-96.055-216-216 0-118.663 96.055-216 216-216 118.664 0 216 96.055 216 216 0 118.663-96.055 216-216 216zm141.63-274.961L217.15 376.071c-4.705 4.667-12.303 4.637-16.97-.068l-85.878-86.572c-4.667-4.705-4.637-12.303.068-16.97l8.52-8.451c4.705-4.667 12.303-4.637 16.97.068l68.976 69.533 163.441-162.13c4.705-4.667 12.303-4.637 16.97.068l8.451 8.52c4.668 4.705 4.637 12.303-.068 16.97z" />
        </svg>
        <span class="sib-form-message-panel__inner-text">
                          Your subscription has been successful.
                      </span>
      </div>
    </div>
    <div></div>
    <div id="sib-container" class="sib-container--large sib-container--vertical" style="text-align:center; background-color:rgba(255,255,255,1); max-width:540px; border-radius:3px; border-width:1px; border-color:#C0CCD9; border-style:solid; direction:ltr">
      <form id="sib-form" method="POST" action="https://ea6fe5a5.sibforms.com/serve/MUIFAPdOgS0jtS0pjYNDPckTjsAzbVgDPgNZv_0_sJk5d3lsOVTwnILHv6_ajps0lCnk7EVbdxkqXZVEIkR8q5o1COfASKdQkST7VFDsRS7rJ3ywM6qhdRDG4Ko6sfWR_PBmc82cMmt5Aw1k6-XZAJexTD8wY1la5Ss_BOYpWFlIp9y4oNlrpCUKLFFSDvyy4-JH-3luuMtfZh8v" data-type="subscription">
        <div style="padding: 8px 0;">
          <div class="sib-form-block" style="font-size:32px; text-align:left; font-weight:700; font-family:&quot;Helvetica&quot;, sans-serif; color:#3C4858; background-color:transparent; text-align:left">
            <p>Newsletter</p>
          </div>
        </div>
        <div style="padding: 8px 0;">
          <div class="sib-form-block" style="font-size:16px; text-align:left; font-family:&quot;Helvetica&quot;, sans-serif; color:#3C4858; background-color:transparent; text-align:left">
            <div class="sib-text-form-block">
              <p>Subscribe to our newsletter and stay updated.</p>
            </div>
          </div>
        </div>
        <div style="padding: 8px 0;">
          <div class="sib-input sib-form-block">
            <div class="form__entry entry_block">
              <div class="form__label-row ">
                <label class="entry__label" style="font-weight: 700; text-align:left; font-size:16px; text-align:left; font-weight:700; font-family:&quot;Helvetica&quot;, sans-serif; color:#3c4858;" for="EMAIL" data-required="*">Enter your email address to subscribe</label>

                <div class="entry__field">
                  <input class="input " type="text" id="EMAIL" name="EMAIL" autocomplete="off" placeholder="EMAIL" data-required="true" required />
                </div>
              </div>

              <label class="entry__error entry__error--primary" style="font-size:16px; text-align:left; font-family:&quot;Helvetica&quot;, sans-serif; color:#661d1d; background-color:#ffeded; border-radius:3px; border-color:#ff4949;">
              </label>
              <label class="entry__specification" style="font-size:12px; text-align:left; font-family:&quot;Helvetica&quot;, sans-serif; color:#8390A4; text-align:left">
                Provide your email address to subscribe. For e.g abc@xyz.com
              </label>
            </div>
          </div>
        </div>
        <div style="padding: 8px 0;">
          <div class="sib-form-block" style="text-align: left">
            <button class="sib-form-block__button sib-form-block__button-with-loader" style="font-size:16px; text-align:left; font-weight:700; font-family:&quot;Helvetica&quot;, sans-serif; color:#FFFFFF; background-color:#3E4857; border-radius:3px; border-width:0px;" form="sib-form" type="submit">
              <svg class="icon clickable__icon progress-indicator__icon sib-hide-loader-icon" viewBox="0 0 512 512">
                <path d="M460.116 373.846l-20.823-12.022c-5.541-3.199-7.54-10.159-4.663-15.874 30.137-59.886 28.343-131.652-5.386-189.946-33.641-58.394-94.896-95.833-161.827-99.676C261.028 55.961 256 50.751 256 44.352V20.309c0-6.904 5.808-12.337 12.703-11.982 83.556 4.306 160.163 50.864 202.11 123.677 42.063 72.696 44.079 162.316 6.031 236.832-3.14 6.148-10.75 8.461-16.728 5.01z" />
              </svg>
              SUBSCRIBE
            </button>
          </div>
        </div>

        <input type="text" name="email_address_check" value="" class="input--hidden">
        <input type="hidden" name="locale" value="en">
      </form>
    </div>
  </div>
</div>
<!-- END - We recommend to place the below code where you want the form in your website html  -->

<!-- START - We recommend to place the below code in footer or bottom of your website html  -->
<script>
  window.REQUIRED_CODE_ERROR_MESSAGE = 'Please choose a country code';
  window.LOCALE = 'en';
  window.EMAIL_INVALID_MESSAGE = window.SMS_INVALID_MESSAGE = "The information provided is invalid. Please review the field format and try again.";

  window.REQUIRED_ERROR_MESSAGE = "This field cannot be left blank. ";

  window.GENERIC_INVALID_MESSAGE = "The information provided is invalid. Please review the field format and try again.";




  window.translation = {
    common: {
      selectedList: '{quantity} list selected',
      selectedLists: '{quantity} lists selected'
    }
  };

  var AUTOHIDE = Boolean(0);
</script>
<script defer src="https://sibforms.com/forms/end-form/build/main.js"></script>


<!-- END - We recommend to place the above code in footer or bottom of your website html  -->
<!-- End Brevo Form -->


## Feedback
If you have feedback regarding bugs or improvements, open an issue, @ me on Twitter or write me an email. You can find my contact info on my website.

I'd love to see the sites you create using this little tool.

## Credits
- [Jekyll](https://github.com/jekyll/jekyll)
- [FontAwesome](https://fontawesome.github.io/Font-Awesome/)

## Donations
[Donations are welcome](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=S8ZZT3JXJPN92&currency_code=USD&source=url)

## Author
[Emil Baehr](https://emilbaehr.com/)

## License
[MIT License](LICENSE)
