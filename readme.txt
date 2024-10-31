=== Rapid URL Indexer for WP – Index Websites in Google ===
Contributors: rapidurlindexer
Tags: indexer, index, google, website indexer, seo
Requires at least: 4.7
Tested up to: 6.6.1
Stable tag: 1.1
Requires PHP: 7.2
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.en.html
Text Domain: rapidurlindexer-wp
Domain Path: /languages

Get your URLs indexed on Google quickly and reliably with Rapid URL Indexer. Pay only for successfully indexed URLs or get your credits back.

== Description ==

Rapid URL Indexer for WordPress is a powerful plugin that integrates with the [Rapid URL Indexer](https://rapidurlindexer.com/) indexing service to help you get your website's pages indexed on Google quickly and efficiently. With an industry-leading indexing rate and a unique pay-as-you-go model, you only pay for successfully indexed URLs.

**Important Note**: This plugin relies on the Rapid URL Indexer API, a third-party service, to submit and index your URLs. By using this plugin, you are agreeing to send your website's URLs to the Rapid URL Indexer service for processing.

= Third-Party Service Information =

This plugin uses the Rapid URL Indexer API service to submit and index your URLs. Here are important links related to the service:

* Service Website: [https://rapidurlindexer.com/](https://rapidurlindexer.com/)
* Terms of Service: [https://rapidurlindexer.com/terms-of-service/](https://rapidurlindexer.com/terms-of-service/)
* Privacy Policy: [https://rapidurlindexer.com/privacy-policy/](https://rapidurlindexer.com/privacy-policy/)

Please review these documents before using the plugin to ensure you comply with the service's terms and understand how your data is handled.

= Why Choose Rapid URL Indexer? =

* **High Indexing Rate**: Achieve an average 91% indexing rate for your URLs.
* **Pay-As-You-Go**: No subscriptions, just pay for what you use.
* **100% Credit Auto Refunds**: Get your credits back for unindexed URLs after 14 days.
* **Safe Indexing Methods**: 100% white hat techniques, no spammy links or questionable practices.
* **Detailed Reports**: Access visual charts and CSV downloads for accurate indexing data.
* **No Google Search Console Required**: Submit any URL, whether you have GSC access or not.
* **Competitive Pricing**: On average 10x less expensive than other indexing services.
* **WordPress Integration**: Automatically submit new and updated posts for indexing.

= Key Features =

* Automatic submission of new and updated posts and pages
* Bulk URL submission
* Customizable settings for different post types
* Detailed logs of submitted URLs
* Integration with Rapid URL Indexer API
* Credit balance checking
* Email notifications for project status updates (optional)

= Third-Party Service Information =

This plugin uses the Rapid URL Indexer API service to submit and index your URLs. Here are important links related to the service:

* Service Website: [https://rapidurlindexer.com/](https://rapidurlindexer.com/)
* Terms of Service: [https://rapidurlindexer.com/terms-of-service/](https://rapidurlindexer.com/terms-of-service/)
* Privacy Policy: [https://rapidurlindexer.com/privacy-policy/](https://rapidurlindexer.com/privacy-policy/)

Please review these documents before using the plugin to ensure you comply with the service's terms and understand how your data is handled.

== Use Cases ==

Rapid URL Indexer can help in various scenarios:

1. **Any Websites**: Improve indexing for your own or clients' websites that struggle with Google indexing.
2. **Backlinks**: Get your backlinks crawled and indexed, including tier 1, 2, or 3 links, social profiles, and citations.
3. **Press Releases**: Index press releases that typically have low indexing rates due to duplicate content.
4. **Mass Page Websites**: Index directories and AI or programmatic SEO sites that are challenging to get indexed.
5. **SEO Testing**: Get test pages crawled and indexed faster for quicker results in single variable tests.
6. **Backlink Disavows**: Recrawl and index disavowed links for faster recovery after backlink-related penalties.

Whether you're an SEO professional, website owner, or digital marketer, Rapid URL Indexer can significantly improve your Google indexing rates and overall search visibility.

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/rapidurlindexer-wp` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Use the Settings -> Rapid URL Indexer screen to configure the plugin.
4. Enter your Rapid URL Indexer API key, which can be found on your My Projects page at rapidurlindexer.com.

== Frequently Asked Questions ==

= Is Rapid URL Indexer safe to use? =

Yes, Rapid URL Indexer uses only safe, white hat methods to get your URLs crawled and indexed. There are no spammy links or black hat techniques involved.

= How quickly will my URLs be indexed? =

Your URLs will be crawled by Googlebot almost immediately after submission. The first indexing report is available after 4 days, and the final report is available after 14 days.

= Do you guarantee indexing? =

While we can't guarantee indexing (no one can), we do guarantee that you only pay for indexed URLs. You'll get your credits back for any unindexed URLs after 14 days.

= Can I use this plugin if I don't have access to Google Search Console? =

Absolutely! Rapid URL Indexer does not require access to Google Search Console. You can submit any URL whether you have GSC access or not.

= How does the pricing work? =

Rapid URL Indexer uses a credit system. Each credit allows you to submit one URL for indexing. If the URL is successfully indexed, you keep the credit. If not, you get the credit back after 14 days. Credits start at $0.05 per URL, with discounts for larger purchases.

= Is there an API available for custom integrations? =

Yes, Rapid URL Indexer provides a RESTful API for easy integration with your own applications or services. This WordPress plugin uses the same API.

= What data is sent to the Rapid URL Indexer service? =

This plugin sends the URLs of your posts and pages to the Rapid URL Indexer service for indexing. No personal data is sent other than the URLs themselves. Please review the Rapid URL Indexer Privacy Policy for more information on how they handle data.

== Changelog ==

= 1.1 =
* Fixed fatal error: Removed the call to the non-existent `get_logs` method and added error handling and the `update_logs_count` method in the `log_submission` function
* Improved the logic to correctly handle post status changes for all post types
* Fixed the issue where the plugin was wrongly detecting the publication of a new post as an update
* Fixed bulk URL submission form

= 1.0 =
* Initial release of the Rapid URL Indexer WordPress plugin

== Upgrade Notice ==

= 1.1 =
* Fixed fatal error: Removed the call to the non-existent `get_logs` method and added error handling and the `update_logs_count` method in the `log_submission` function
* Improved the logic to correctly handle post status changes for all post types
* Fixed the issue where the plugin was wrongly detecting the publication of a new post as an update
* Fixed bulk URL submission form

= 1.0 =
This is the first version of the Rapid URL Indexer WordPress plugin. Enjoy fast and reliable Google indexing for your website!
