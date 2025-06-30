# LiteRead

**LiteRead** is a modern web-based reading platform built on top of the WordPress content management system (CMS). It is designed to deliver a streamlined, scalable, and SEO-optimized experience for hosting and consuming serialized fiction or text-based content online.

## System Overview

LiteRead combines the reliability and extensibility of WordPress with modern frontend tooling to create a performant and user-focused reading experience.

The backend is fully powered by WordPress, providing a mature ecosystem for managing posts, chapters, users, comments, and media. This ensures compatibility with a wide range of themes, plugins, and integrations.

The frontend layer is enhanced using Tailwind CSS, PostCSS, and Autoprefixer to ensure clean, maintainable, and mobile-responsive design. Additionally, React Helmet Async is used for managing metadata dynamically, contributing to strong SEO performance.

## Features

- Content management using WordPress (chapters, genres, tags, user roles, etc.)
- Clean, mobile-first UI design with Tailwind CSS
- SEO-friendly through React Helmet Async and structured markup
- Sitemap and robots.txt configuration for better indexing
- Support for modern development workflows with `postcss.config.js` and `tailwind.config.js`
- Extendable via WordPress plugins and themes
- Structured for scalability and maintainability

## Technology Stack

- **Backend**: WordPress (PHP)
- **Frontend Styling**: Tailwind CSS, PostCSS, Autoprefixer
- **SEO Tools**: React Helmet Async
- **Environment Requirements**:
  - PHP ≥ 7.4
  - MySQL ≥ 5.5.5 or MariaDB ≥ 10.5
  - Apache with `mod_rewrite` enabled (recommended)
  - HTTPS support

## Installation Guide

1. Extract the contents of this repository into your server’s root directory.
2. Create a new MySQL (or MariaDB) database and user with proper privileges.
3. Navigate to `/wp-admin/install.php` in your web browser.
4. Follow the setup instructions to generate a `wp-config.php` file.
5. Complete the WordPress installation process.
6. Log in to the admin dashboard (`/wp-admin`) to configure your site.
7. Customize design, install plugins, or configure Tailwind settings if needed.
8. Ensure `robots.txt` and `sitemap.xml` are properly indexed by search engines.

## Project Structure

- `index.php` – Entry point to the WordPress application
- `wp-*` – Core WordPress system files
- `package.json` – Node-based dependencies for styling and frontend tooling
- `tailwind.config.js`, `postcss.config.js` – Frontend configuration files
- `sitemap.php`, `robots.txt` – SEO and crawler configuration
- `.htaccess` – URL rewriting and security rules

## Development Notes

If modifying or extending the frontend:

- Run build tools with PostCSS/Tailwind using your preferred task runner.
- Update styles via utility classes rather than traditional CSS.
- Consider integrating React components if you expand dynamic features.

All WordPress core files remain untouched to ensure upgradability. Custom features should be added through child themes or plugins to maintain compatibility with future WordPress versions.

## License

This project is licensed under the GNU General Public License v2 or later. See `license.txt` for details.

---

For additional support or contribution guidelines, please refer to the official [WordPress documentation](https://wordpress.org/documentation/).
