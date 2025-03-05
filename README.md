# Awesome Self-Hosted Marketing Software [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome **free as in freedom** (libre/open source) and **self-hosted** marketing software.

> **"Free as in freedom"** means the software respects the user's freedom, as defined by the Free Software Foundation.  This generally implies the software is licensed under an OSI-approved license like GPL, MIT, Apache, etc.
>
> **"Self-hosted"** means you can install and run the software on your own servers or infrastructure, giving you control over your data and operations.

This list aims to be a comprehensive resource for marketers, businesses, and individuals seeking to leverage the power of open source and self-hosting for their marketing activities. It covers a range of marketing disciplines, from CRM and email marketing to analytics and social media management.

**Table of Contents**

- [Customer Relationship Management (CRM)](#customer-relationship-management-crm)
- [Email Marketing & Automation](#email-marketing--automation)
- [Web Analytics & Tracking](#web-analytics--tracking)
- [Social Media Marketing & Management](#social-media-marketing--management)
- [Content Management Systems (CMS) - Marketing Focused](#content-management-systems-cms---marketing-focused)
- [Landing Page Builders](#landing-page-builders)
- [Forms & Surveys](#forms--surveys)
- [SEO (Search Engine Optimization) Tools](#seo-search-engine-optimization-tools)
- [Marketing Automation Building Blocks / Frameworks](#marketing-automation-building-blocks--frameworks)
- [E-commerce (Marketing Aspects)](#e-commerce-marketing-aspects)
- [Other Marketing Related Tools](#other-marketing-related-tools)
- [Important Considerations](#important-considerations)
- [Contributing](#contributing)
- [License](#license)

---

## Customer Relationship Management (CRM)

* **EspoCRM** - Web-based CRM with a focus on sales, marketing, and customer support. Offers sales automation, email marketing, and workflow management.
    * **License:** [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)
    * **Website:** [https://www.espocrm.com/](https://www.espocrm.com/)
    * **Source Code:** [GitHub (link on website)](https://www.espocrm.com/)
    * **Notes:** Mature and feature-rich CRM, often compared to commercial solutions. Active community and development.
* **Monica CRM** - Personal CRM to manage relationships with friends, family, and acquaintances. Adaptable for very small businesses or personal marketing.
    * **License:** [AGPLv3](https://www.gnu.org/licenses/agpl-3.0.en.html)
    * **Website:** [https://www.monicahq.com/](https://www.monicahq.com/)
    * **Source Code:** [GitHub](https://github.com/monicahq/monica)
    * **Notes:** Simpler and more user-friendly than enterprise-level CRMs. Good for individuals or very small teams.
* **Odoo (Community Edition)** - Comprehensive suite of business applications, including a strong CRM module. Offers a wide range of modules beyond CRM (ERP, eCommerce, etc.).
    * **License:** [LGPLv3](https://www.gnu.org/licenses/lgpl-3.0.en.html)
    * **Website:** [https://www.odoo.com/page/download](https://www.odoo.com/page/download)
    * **Source Code:** [GitHub (link on website)](https://www.odoo.com/page/download)
    * **Notes:** Very versatile and modular. Community Edition is feature-rich, but some advanced marketing features are in the Enterprise version.
* **SuiteCRM** - Fork of SugarCRM Community Edition. Robust CRM platform with extensive features for sales, marketing, and service. Highly customizable and extensible.
    * **License:** [AGPLv3](https://www.gnu.org/licenses/agpl-3.0.en.html)
    * **Website:** [https://suitecrm.com/](https://suitecrm.com/)
    * **Source Code:** [GitHub (link on website)](https://suitecrm.com/)
    * **Notes:** One of the most well-known open-source CRMs. Large community, many integrations, and a strong ecosystem of extensions.
* **vTiger CRM (Open Source Edition)** - Popular CRM offering sales, marketing, and support features. Has both open-source and commercial versions. Focuses on ease of use and flexibility.
    * **License:** [AGPLv3](https://www.gnu.org/licenses/agpl-3.0.en.html)
    * **Website:** [https://www.vtiger.com/open-source/](https://www.vtiger.com/open-source/)
    * **Source Code:** [GitHub (link on website)](https://www.vtiger.com/open-source/)
    * **Notes:** Long-standing CRM with a good track record. Be sure to download the *Open Source Edition*.
* **CiviCRM** - CRM specifically designed for non-profit and civic sector organizations. Strong focus on membership management, fundraising, event management, and advocacy.
    * **License:** [AGPLv3](https://www.gnu.org/licenses/agpl-3.0.en.html)
    * **Website:** [https://civicrm.org/](https://civicrm.org/)
    * **Source Code:** [GitHub (link on website)](https://civicrm.org/)
    * **Notes:** Excellent choice for non-profits and organizations with specific needs in those sectors. Integrates well with CMS like Drupal and WordPress.

## Email Marketing & Automation

* **Listmonk** - High-performance, self-hosted newsletter and mailing list manager. Focuses on speed, efficiency, and deliverability.
    * **License:** [AGPLv3](https://www.gnu.org/licenses/agpl-3.0.en.html)
    * **Website:** [https://listmonk.app/](https://listmonk.app/)
    * **Source Code:** [GitHub](https://github.com/listmonk/listmonk)
    * **Notes:** Excellent choice for sending large volumes of emails reliably. More focused on newsletters and transactional emails than complex marketing automation.
* **Mailtrain** - Self-hosted newsletter application built on top of Nodemailer and MySQL. Inspired by Mailchimp and Sendy.
    * **License:** [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)
    * **Website:** [https://mailtrain.org/](https://mailtrain.org/)
    * **Source Code:** [GitHub](https://github.com/mailtrain-org/mailtrain)
    * **Notes:** Good option for those familiar with Node.js and MySQL. Offers decent features for newsletter management.
* **Mautic** - Powerful marketing automation platform. Features email marketing, landing page builder, campaign automation, lead tracking, social media integration, and more. A true open-source alternative to commercial marketing automation platforms.
    * **License:** [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)
    * **Website:** [https://www.mautic.org/](https://www.mautic.org/)
    * **Source Code:** [GitHub](https://github.com/mautic/mautic)
    * **Notes:** Highly regarded as the leading open-source marketing automation solution. Requires more technical setup than simpler tools but offers immense power.
* **OpenEMM** - Open Email Marketing Manager. A mature email marketing platform with features like segmentation, A/B testing, and campaign management.
    * **License:** [AGPLv3](https://www.gnu.org/licenses/agpl-3.0.en.html)
    * **Website:** [https://openemm.com/](https://openemm.com/)
    * **Source Code:** [Source code details on website](https://openemm.com/)
    * **Notes:** One of the older open-source email marketing solutions. Feature-rich but might have a steeper learning curve compared to newer tools.

## Web Analytics & Tracking

* **Countly (Community Edition)** - Open-source product analytics platform. Focuses on mobile and web analytics, with features like user segmentation, funnels, and retention analysis.
    * **License:** [AGPLv3](https://www.gnu.org/licenses/agpl-3.0.en.html)
    * **Website:** [https://count.ly/](https://count.ly/)
    * **Source Code:** [GitHub (link on website)](https://count.ly/)
    * **Notes:** Strong in product analytics and mobile app tracking. Community Edition is open-source, but some features are in the Enterprise version.
* **GoAccess** - Real-time web log analyzer and interactive viewer. Analyzes web server access logs (like Apache or Nginx) and provides detailed statistics in a terminal or browser.
    * **License:** [GPLv2](https://www.gnu.org/licenses/gpl-2.0.en.html)
    * **Website:** [http://goaccess.io/](http://goaccess.io/)
    * **Source Code:** [GitHub](https://github.com/allinurl/goaccess)
    * **Notes:** Fast and efficient for analyzing server logs directly. More technical but provides very detailed insights from raw server data.
* **Matomo (formerly Piwik)** - Leading open-source web analytics platform. A powerful alternative to Google Analytics, with a strong focus on privacy and data ownership. Offers comprehensive website and app analytics, heatmaps, session recording, and more.
    * **License:** [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)
    * **Website:** [https://matomo.org/](https://matomo.org/)
    * **Source Code:** [GitHub](https://github.com/matomo-org/matomo)
    * **Notes:** Highly recommended for privacy-conscious users and organizations. Feature-rich and actively developed. Has a marketplace for plugins to extend functionality.
* **Plausible Analytics** - Lightweight and privacy-focused web analytics. A simpler alternative to Google Analytics and Matomo, focusing on essential metrics and ease of use.
    * **License:** [AGPLv3](https://www.gnu.org/licenses/agpl-3.0.en.html)
    * **Website:** [https://plausible.io/](https://plausible.io/)
    * **Source Code:** [GitHub](https://github.com/plausible/analytics)
    * **Notes:** Excellent choice for those who want simple, privacy-friendly analytics without the complexity of larger platforms. The self-hosted version is open-source (Community Edition).

## Social Media Marketing & Management

* **Nostr (Protocol & Clients)** - Decentralized social media protocol. While not software itself, various Nostr clients are open-source and can be self-hosted. Offers a different approach to social media presence and community engagement.
    * **License:** Varies by client (often MIT or similar)
    * **Website:** [https://nostr.com/](https://nostr.com/)
    * **Source Code:** [Clients are often found on GitHub](https://nostr.com/)
    * **Notes:** Emerging and evolving decentralized social media space. Requires understanding of the Nostr protocol and client options.
* **Socialhome** - Decentralized social networking platform that can be self-hosted. Can be used to build and manage a community and presence for marketing purposes.
    * **License:** [AGPLv3](https://www.gnu.org/licenses/agpl-3.0.en.html)
    * **Website:** [https://socialhome.network/](https://socialhome.network/)
    * **Source Code:** [GitHub](https://github.com/jaywink/socialhome)
    * **Notes:** More of a social network platform than a social media *management* tool. Can be used for community building and content sharing.

## Content Management Systems (CMS) - Marketing Focused

* **Drupal (with Marketing Modules)** - Powerful CMS, known for its flexibility and scalability. Can be transformed into a marketing platform with modules for SEO, content marketing, and marketing automation integrations.
    * **License:** [GPLv2](https://www.gnu.org/licenses/gpl-2.0.en.html)
    * **Website:** [https://www.drupal.org/](https://www.drupal.org/)
    * **Source Code:** [GitHub](https://github.com/drupal/drupal)
    * **Notes:** More developer-focused than WordPress but highly customizable. Strong for complex websites and content structures.
* **Grav CMS** - Modern flat-file CMS (no database required). Fast, flexible, and easy to use. Can be extended for marketing purposes with plugins and themes.
    * **License:** [MIT License](https://opensource.org/licenses/MIT)
    * **Website:** [https://getgrav.org/](https://getgrav.org/)
    * **Source Code:** [GitHub](https://github.com/getgrav/grav)
    * **Notes:** Good for simpler websites and marketing sites where database complexity is not needed.
* **Joomla! (with Marketing Extensions)** - Established CMS. Offers a balance between user-friendliness and flexibility. Has extensions for SEO, content marketing, and other marketing needs.
    * **License:** [GPLv2](https://www.gnu.org/licenses/gpl-2.0.en.html)
    * **Website:** [https://www.joomla.org/](https://www.joomla.org/)
    * **Source Code:** [GitHub](https://github.com/joomla/joomla-cms)
    * **Notes:** A solid CMS choice with a long history.
* **WordPress (with Marketing Plugins)** - The most popular CMS in the world. While general-purpose, WordPress becomes a powerful marketing platform with the vast ecosystem of plugins for SEO, content marketing, email opt-ins, landing pages, etc.
    * **License:** [GPLv2](https://www.gnu.org/licenses/gpl-2.0.en.html)
    * **Website:** [https://wordpress.org/](https://wordpress.org/)
    * **Source Code:** [GitHub](https://github.com/WordPress/WordPress)
    * **Notes:** Extremely flexible and widely supported. Choose marketing-focused themes and plugins to enhance its marketing capabilities.

## Landing Page Builders

* **GrapesJS (as a component)** - Open-source, multi-purpose, web page builder framework. Can be used to build landing page builders or integrate into other marketing applications. It's a component, not a standalone application.
    * **License:** [BSD-3-Clause](https://opensource.org/licenses/BSD-3-Clause)
    * **Website:** [https://grapesjs.com/](https://grapesjs.com/)
    * **Source Code:** [GitHub](https://github.com/GrapesJS/grapesjs)
    * **Notes:** Highly flexible and customizable framework for building visual editors. Requires development effort to create a complete landing page builder application.
* **Unlayer (Self-Hosted Version)** - Drag-and-drop email and landing page builder. Offers a self-hosted version that you can integrate into your own applications. *Needs license clarification for full "free as in freedom" status.*
    * **License:** Potentially source-available/commercial license for self-hosted version. *Verify license details.*
    * **Website:** [https://unlayer.com/](https://unlayer.com/)
    * **Source Code:** [Self-hosted details on website](https://unlayer.com/)
    * **Notes:** Focuses on visual design and ease of use for creating landing pages and emails. *License needs further investigation for "free as in freedom" definition.*

## Forms & Surveys

* **Fider** - Open-source customer feedback platform. Allows users to submit and vote on feature requests and ideas. Useful for gathering customer insights and prioritizing development.
    * **License:** [MIT License](https://opensource.org/licenses/MIT)
    * **Website:** [https://fider.io/](https://fider.io/)
    * **Source Code:** [GitHub](https://github.com/getfider/fider)
    * **Notes:** Focuses on product feedback and feature voting. Good for product-led marketing and customer engagement.
* **LimeSurvey** - Powerful open-source survey tool. Offers a wide range of question types, survey logic, branching, and reporting features. Excellent for market research, customer feedback, and data collection.
    * **License:** [GPLv2](https://www.gnu.org/licenses/gpl-2.0.en.html)
    * **Website:** [https://www.limesurvey.org/](https://www.limesurvey.org/)
    * **Source Code:** [GitHub](https://github.com/LimeSurvey/LimeSurvey)
    * **Notes:** Mature and feature-rich survey platform. Can handle complex surveys and data analysis.
* **OhMyForm** - Open-source form builder. Simple and easy to use for creating various types of forms (contact forms, surveys, etc.).
    * **License:** [MIT License](https://opensource.org/licenses/MIT)
    * **Website:** [https://ohmyform.com/](https://ohmyform.com/)
    * **Source Code:** [GitHub](https://github.com/ohmyform/ohmyform)
    * **Notes:** Lightweight and straightforward form builder.

## SEO (Search Engine Optimization) Tools

* **SeoPanel** - Free control panel for SEO. Offers various SEO tools like keyword research, rank tracking, website audit, and backlink analysis. *Be cautious about security and updates as project activity may vary.*
    * **License:** [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)
    * **Website:** [http://www.seopanel.org/](http://www.seopanel.org/)
    * **Source Code:** [Source code available on website](http://www.seopanel.org/)
    * **Notes:** Provides a range of SEO features in a single self-hosted package. *Needs careful security review and assessment of project activity.*
* **Web Crawlers/Scrapers (Build Your Own)** - Utilize open-source web crawling and scraping libraries in Python (Scrapy, Beautiful Soup), Node.js (Cheerio, Puppeteer), etc. to build custom SEO research tools.
    * **License:** Libraries are typically MIT, Apache, or similar.
    * **Notes:** Not pre-built software, but the building blocks are open-source. For advanced users who need highly customized SEO data gathering.

## Marketing Automation Building Blocks / Frameworks

* **Activepieces** - No-code business automation platform. Allows you to create workflows and automations, including marketing-related tasks.
    * **License:** [MIT License](https://opensource.org/licenses/MIT)
    * **Website:** [https://www.activepieces.com/](https://www.activepieces.com/)
    * **Source Code:** [GitHub](https://github.com/activepieces/activepieces)
    * **Notes:** Focuses on no-code automation, making it more accessible to non-developers.
* **n8n** - Open-source workflow automation platform. Can be used to build custom marketing automation workflows by connecting various services and APIs.
    * **License:** [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
    * **Website:** [https://n8n.io/](https://n8n.io/)
    * **Source Code:** [GitHub](https://github.com/n8n-io/n8n)
    * **Notes:** Extremely powerful for creating complex automations across different marketing tools and systems. Requires technical skills to design and implement workflows.

## E-commerce (Marketing Aspects)

* **OpenCart** - Free open-source e-commerce platform. Offers a good balance of features and ease of use. Has extensions for marketing and SEO.
    * **License:** [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)
    * **Website:** [https://www.opencart.com/](https://www.opencart.com/)
    * **Source Code:** [GitHub](https://github.com/opencart/opencart)
    * **Notes:** Another well-established e-commerce platform with a solid community.
* **PrestaShop** - Open-source e-commerce platform with strong marketing features built-in (SEO, promotions, email marketing integrations, etc.).
    * **License:** [OSL-3.0](https://opensource.org/licenses/OSL-3.0)
    * **Website:** [https://www.prestashop.com/](https://www.prestashop.com/)
    * **Source Code:** [GitHub](https://github.com/PrestaShop/PrestaShop)
    * **Notes:** Popular e-commerce platform with a large community and marketplace of modules.
* **Sylius** - Open-source e-commerce platform built on Symfony. Highly flexible and customizable for complex e-commerce needs. Offers marketing features and integrations.
    * **License:** [MIT License](https://opensource.org/licenses/MIT)
    * **Website:** [https://sylius.com/](https://sylius.com/)
    * **Source Code:** [GitHub](https://github.com/Sylius/Sylius)
    * **Notes:** More developer-focused and designed for building sophisticated e-commerce experiences.

## Other Marketing Related Tools

* **Koko Analytics** (WordPress Plugin) - Privacy-friendly and lightweight analytics plugin for WordPress. Simple and GDPR compliant.
    * **License:** [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)
    * **Website:** [https://kokoanalytics.com/](https://kokoanalytics.com/)
    * **Source Code:** [WordPress Plugin Directory](https://kokoanalytics.com/)
    * **Notes:** Extremely simple analytics for WordPress, focused on basic page views and referrer tracking.
* **Open Web Analytics (OWA)** - Open-source web analytics framework. Can be used to track website usage and behavior. More of a framework than a full application.
    * **License:** [GPLv2](https://www.gnu.org/licenses/gpl-2.0.en.html)
    * **Website:** [http://www.openwebanalytics.net/](http://www.openwebanalytics.net/)
    * **Source Code:** [SourceForge link on website](http://www.openwebanalytics.net/)
    * **Notes:** Older project, might require more technical setup and maintenance.

---

## Important Considerations

When choosing and using self-hosted marketing software, keep the following in mind:

* **Technical Skills:** Self-hosting requires technical skills to set up, configure, and maintain servers, databases, and software.
* **Server Infrastructure:** You'll need to provide your own server infrastructure (VPS, dedicated server, cloud server).
* **Maintenance & Updates:** You are responsible for software updates, security patches, and ongoing maintenance.
* **Scalability:** Consider the scalability of the software and your server infrastructure as your marketing needs grow.
* **Community & Support:** Active communities and good documentation are crucial for self-hosted software.
* **Security:** Security is your responsibility. Keep software updated, configure firewalls, and follow security best practices.

## Contributing

Contributions are welcome! If you know of other awesome free/open-source self-hosted marketing software that should be on this list, please submit a pull request.

**To contribute:**

1. Fork this repository.
2. Add your software to the appropriate category in the `README.md` file, following the existing format. Please ensure:
    * The software is truly **free as in freedom** (open-source with an OSI-approved license).
    * The software is designed for **self-hosting**.
    * Provide a concise and informative description.
    * Include links to the official website and source code repository (if applicable).
3. Submit a pull request with your changes.

Please ensure your submissions are relevant, high-quality, and properly formatted.  Duplicate entries or software that doesn't meet the criteria may be rejected.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, jaimepaezv has waived all copyright and related or neighboring rights to this work.

---
*This list is a community effort and is provided for informational purposes only. We are not endorsing or guaranteeing the suitability, quality, or security of any of the listed software. Always do your own research and testing before implementing any of these tools for your marketing activities.*
