# Rotary Brand Assets

This repository, `rotary-brand-assets`, is a collection of assets for use in projects that need to adhere to the Rotary International's brand guidelines. It includes CSS files containing brand color variables and SVG files with the Rotary text and the Masterbrand logo.

## About Rotary International Brand Elements

Please make sure that your use of these assets complies with [Rotary International's Brand Center guidelines](https://brandcenter.rotary.org/en-us/our-brand/brand-elements). The guidelines provide detailed information on how the brand should be represented in various contexts.

- [Logos and Graphics](https://brandcenter.rotary.org/en-us/our-brand/brand-elements/logos-and-graphics)
- [Voice and Messaging](https://brandcenter.rotary.org/en-us/our-brand/brand-elements/voice-and-messaging)
- [Images and Videos](https://brandcenter.rotary.org/en-us/our-brand/brand-elements/images-and-videos)
- [Colors](https://brandcenter.rotary.org/en-us/our-brand/brand-elements/colors)
- [Typography](https://brandcenter.rotary.org/en-us/our-brand/brand-elements/typography)
- [The Rotary Name](https://brandcenter.rotary.org/en-us/our-brand/brand-elements/the-rotary-name)


## Contents of this repository

1. **CSS File (Brand Colors)**
   - `rotary-brand-colors.css`: This file contains a set of CSS variables representing Rotary International's official color palette. These variables can be incorporated into web projects to ensure consistent use of Rotary's brand colors.

2. **SVG Files**
   - `rotary-text.svg`: An SVG file featuring the stylized text of "Rotary."
   - `rotary-masterbrand-logo.svg`: An SVG file of the Rotary International Masterbrand logo.

## Usage

### CSS Brand Colors

To use the Rotary brand colors in your web project, include the `rotary-brand-colors.css` file in your project. You can then reference the color variables in your CSS files to apply Rotary's official colors to your web elements.

```html
<link rel="stylesheet" href="path/to/rotary-brand-colors.css">
```

In your CSS:

```css
body {
  background-color: var(--rotary-royal-blue);
}
```

### SVG Files

The SVG files can be used directly in your HTML to display the Rotary text and the Masterbrand logo. Ensure that you adhere to Rotary International's guidelines for logo usage and placement.

```html
<img src="path/to/rotary-text.svg" alt="Rotary Text">
<img src="path/to/rotary-masterbrand-logo.svg" alt="Rotary Masterbrand Logo">
```

### Putting it all together

The following is an example useage of the SVG files on a standard html page. Please remember to adhere to the Rotary International guidelines for all usage of these trademarked assets.

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Rotary Club of Club Name | District 9999</title>
    <!-- Rotary International Brand Colors -->
    <link rel="stylesheet" href="css/rotary-colors.css">
    <!-- Rotary Masterbrand Signature and Header -->
    <link rel="stylesheet" href="css/rotary-masterbrand-signature.css">
    <!-- Custom Styles for the new member information form and page -->
    <link rel="stylesheet" href="css/styles.css">
</head>

<body>
    <header>
        <div class="rotary-masterbrand-signature">
            <div class="rotary-text-group">
                <div class="text-above">&nbsp;<!-- District 9999 --></div>
                <div class="rotary-text">
                    <img src="img/Rotary.svg" alt="Rotary International Logo">
                </div>
                <div class="text-below">Club of Club Name</div>
            </div>
            <div class="masterbrand">
                <img src="img/rotary-masterbrand.svg" alt="The Rotary International Masterbrand logo.">
            </div>
        </div>
    </header>
    <main>
        <h1>Welcome to the Rotary Club of Club Name!</h1>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Inventore, voluptatem quibusdam! Ut necessitatibus
            provident reiciendis autem porro eius aut aspernatur expedita, odio iure debitis sunt vero. Totam vero
            repellat pariatur?</p>
    </main>
    <footer>
        <p>&copy; 2024 Rotary Club of Club Name. All Rights Reserved.</p>
        <a href="your-privacy-policy-url">Privacy Policy</a> | <a href="your-terms-url">Terms of Use</a>
    </footer>
</body>
```

## Rotary Brand Colors

> [Rotary’s brand colors](https://brandcenter.rotary.org/en-us/our-brand/brand-elements/colors)[^1] should be used to create a consistent look across all Rotary communications.  Our colors have been carefully chosen to complement one another in most situations and should be used in their pure forms, never altered nor screened. Each color includes formulations for the following uses:
> - Pantone™ colors for print
> - CMYK for 4-color process print
> - Hexadecimal for web
> - RGB for digital

| Color Name        | PMS           | CMYK            | Hex       | RGB            | RGBA                  |
| ----------------- | ------------- | --------------- | --------- | -------------- | --------------------- |
| Rotary Royal Blue | PMS 286C      | C100 M84 Y12 K3 | `#17458f` | R23 G69 B143   | `rgba(23,69,143,1)`   |
| Rotary Gold       | PMS 130C      | C0 M41 Y100 K0  | `#f7a81b` | R247 G168 B27  | `rgba(247,168,27,1)`  |
| Azure             | PMS 2175C     | C100 M56 Y0 K0  | `#0067c8` | R0 G105 B200   | `rgba(0,105,200,1)`   |
| Sky Blue          | PMS 2202C     | C96 M11 Y2 K0   | `#00a2e0` | R0 G162 B224   | `rgba(0,162,224,1)`   |
| Cranberry         | PMS 214C      | C13 M100 Y37 K0 | `#d41367` | R212 G19 B103  | `rgba(212,19,103,1)`  |
| Cardinal          | PMS 485C      | C6 M98 Y100 K1  | `#e02927` | R224 G41 B39   | `rgba(224,41,39,1)`   |
| Turquoise         | PMS 7466C     | C96 M1 Y31 K0   | `#00adbb` | R0 G173 B187   | `rgba(0,173,187,1)`   |
| Orange            | PMS 2018C     | C0 M66 Y100 K0  | `#ff7600` | R255 G118 B0   | `rgba(255,118,0,1)`   |
| Violet            | PMS 2070C     | C53 M100 Y0 K0  | `#901f93` | R144 G31 B147  | `rgba(144,31,147,1)`  |
| Grass             | PMS 355C      | C99 M12 Y100 K2 | `#009739` | R1 G151 B57    | `rgba(1,151,57,1)`    |
| Powder Blue       | PMS 290C      | C26 M6 Y3 K0    | `#b9d9eb` | R185 G217 B235 | `rgba(185,217,235,1)` |
| Moss              | PMS 7537C     | C36 M26 Y36 K0  | `#a7aca2` | R167 G172 B162 | `rgba(167,172,162,1)` |
| Lavender          | PMS 665C      | C21 M25 Y7 K0   | `#c6bcd0` | R198 G188 B208 | `rgba(198,188,208,1)` |
| Taupe             | PMS 7501C     | C16 M19 Y42 K0  | `#d9c89e` | R217 G200 B158 | `rgba(217,200,158,1)` |
| Mist              | PMS 2162C     | C42 M30 Y21 K0  | `#9ba4b4` | R155 G164 B180 | `rgba(155,164,180,1)` |
| Slate             | PMS 2165C     | C66 M44 Y28 K3  | `#657f99` | R101 G127 B153 | `rgba(101,127,153,1)` |
| Charcoal          | Cool Gray 11C | C66 M57 Y52 K29 | `#54565a` | R84 G86 B90    | `rgba(84,86,90,1)`    |
| Pewter            | Cool Gray 8C  | C49 M40 Y38 K4  | `#898a8d` | R137 G138 B141 | `rgba(137,138,141,1)` |
| Smoke             | Cool Gray 5C  | C32 M25 Y26 K0  | `#b1b1b1` | R177 G177 B177 | `rgba(177,177,177,1)` |
| Silver            | Cool Gray 2C  | C18 M14 Y15 K0  | `#d0cfcd` | R208 G207 B205 | `rgba(208,207,205,1)` |
| White             | C0 M0 Y0 K0   |                 | `#ffffff` | R255 G255 B255 | `rgba(255,255,255,1)` |
| Black             | C0 M0 Y0 K100 |                 | `#000000` | R0 G0 B0       | `rgba(0,0,0,1)`       |
| Storm             | Warm Gray 10C | C50 M51 Y54 K17 | `#7a6e66` | R122 G110 B102 | `rgba(122,110,102,1)` |
| Ash               | Warm Gray 7C  | C42 M41 Y45 K5  | `#968b83` | R150 G139 B131 | `rgba(150,139,131,1)` |
| Platinum          | Warm Gray 3C  | C26 M24 Y28 K0  | `#bfb7b0` | R191 G183 B176 | `rgba(191,183,176,1)` |
| Cloud             | Warm Gray 1C  | C15 M14 Y18 K0  | `#d6d1ca` | R214 G209 B202 | `rgba(214,209,202,1)` |

[^1]: [Rotary Brand Central](https://brandcenter.rotary.org/en-us/our-brand/brand-elements/colors)

## Contributing

We welcome contributions to this repository! If you have suggestions for improvements or want to contribute to the ongoing development of these assets, please follow the process below:

1. **Fork the Repository**: Start by forking the repository to your own GitHub account. This creates a personal copy for you to work on.

2. **Clone the Forked Repository**: Clone the repository to your local machine. This will allow you to make changes and test them on your system.

   ```bash
   git clone https://github.com/your-username/rotary-brand-assets.git
   cd rotary-brand-assets
   ```

3. **Create a New Branch**: Before making changes, create a new branch. This keeps your updates organized and separate from the main branch.

   ```bash
   git checkout -b your-new-branch-name
   ```

4. **Make Your Changes**: Implement your changes, improvements, or fixes in your branch. Feel free to update existing files or add new ones as needed.

5. **Commit Your Changes**: Once you're satisfied with your changes, commit them to your branch with a clear and descriptive commit message.

   ```bash
   git commit -m "A brief description of the changes"
   ```

6. **Push to GitHub**: Push your changes to your forked repository on GitHub.

   ```bash
   git push origin your-new-branch-name
   ```

7. **Submit a Pull Request**: Go to the original repository on GitHub. You should see a prompt to submit a pull request from your new branch. Fill in the pull request form with a clear description of your changes and submit it.

8. **Review and Merge**: We will review your pull request. If everything is in order, your changes will be merged into the main project.

We appreciate your efforts to contribute and look forward to collaborating with you!

## License, Ownership, Attribution,and Fair Use

### Brand Assets Ownership

Please note that all Rotary International brand assets, including logos, colors, and other related materials, are owned by Rotary International. Their use should align with the organization's guidelines and policies, as outlined in [Rotary International's Brand Center guidelines](https://brandcenter.rotary.org/en-us).

### Code and Implementation

The code and implementation provided in this repository, including the conversion of brand colors into CSS and SVG assets, have been created by [Member Minder Pro, LLC](https://memberminderpro.com). This work is released as open-source and is available for use under a fair use license with attribution.

### License

This project is licensed under a modified MIT License, which allows for free use, modification, and distribution of this work, provided that any use of the assets or code retains attribution to Member Minder Pro. Additionally, any distribution of modified versions of this work must be under the same or similar license terms.

By using these assets and code, you agree to adhere to the terms of this license, ensuring that Member Minder Pro's contribution to the project is appropriately credited in any derivative works or distributions.

#### How to Attribute

When using assets or code from this repository, please include the following attribution:

"Brand assets and implementation provided by [Member Minder Pro, LLC](https://memberminderpro.com), used under MIT License."

#### Modifications and Sharing

You are free to modify and share the assets and code in this repository, but please ensure that any distributed versions also include proper attribution to [Member Minder Pro, LLC](https://memberminderpro.com), and are released under the same or a similar open-source license.

## About Us

[Member Minder Pro](https://www.memberminderpro.com) is an official [Rotary International Licensee](https://my.rotary.org/en/my-rotary/community-marketplace/club-management-systems-and-website-providers), and is dedicated to providing innovative solutions such as [DACdb](https://www.dacdb.org/) — tailored specifically for organizations within Rotary International. Our focus is on developing user-friendly, efficient, and effective digital tools and resources.

> Built By Rotarians For Rotarians

We believe in the power of community and technology to make a positive impact. Our team is committed to supporting organizations in streamlining their processes and enhancing their digital presence.

**Connect with Us:**
- Visit our website: [Member Minder Pro, LLC.](https://www.memberminderpro.com)
- Follow us on Twitter: [@MemberMinderPro](https://twitter.com/MemberMinderPro)
- Like us on Facebook: [Member Minder Pro on Facebook](https://www.facebook.com/MemberMinderPro)
- Connect with us on LinkedIn: [Member Minder Pro on LinkedIn](https://www.linkedin.com/company/memberminderpro/)

For more information about our services and how we can assist your organization, please visit our website or contact us through our social media channels.
