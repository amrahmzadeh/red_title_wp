![Logo](image.png)

# Red Title Addon for WordPress

**Plugin Name:** Red Title Addon for WordPress  
**Version:** 1.1  
**Author:** Amrah Movsumzade  

---

## Description

Red Title Addon allows you to add custom red text next to your post or page titles in WordPress. This makes your titles more eye-catching and noticeable.  

- Add red text easily using the meta box in the post/page editor.  
- Supports titles on archive pages, homepage, and single post pages.  
- Fully compatible with modern WordPress themes and block-based layouts.  

---

## Features

- Admin meta box for adding red text to posts and pages.  
- PHP-based dynamic title modification for frontend display.  
- CSS ensures consistent styling across all titles.  
- Compatible with Gutenberg and classic editor themes.  
- Works on homepage, archives, categories, search results, and single pages.  

---

## Installation

1. Upload the `red-title-addon` folder to the `/wp-content/plugins/` directory.  
2. Go to **Plugins > Installed Plugins** in the WordPress admin panel.  
3. Activate **Red Title Addon**.  

---

## Usage

1. Open a post or page in the WordPress admin panel.  
2. Locate the **Red Title Text** meta box.  
3. Enter the text you want to appear next to the title.  
4. Save or publish the post/page.  
5. The red text will automatically appear next to the title on the frontend.  

> Note: The plugin automatically supports themes using `entry-title title` or standard heading classes.

---

## Customization

- Modify the CSS in the `add_css()` function to adjust color, font, size, spacing, or other styles.  
- For AJAX-loaded or dynamically rendered titles, additional JS can be added to ensure the red text appears.  

---

## Changelog

**1.1**  
- Added support for pages in addition to posts.  
- Improved compatibility with block-based themes.  
- Enhanced CSS styling for better visibility.  

**1.0**  
- Initial release.  
- Adds custom red text next to post titles using a meta box.  


