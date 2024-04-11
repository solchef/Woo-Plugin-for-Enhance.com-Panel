# Enhance Integration with WooCommerce
![Logo](/images/white_enhance.svg "Enhance Logo")  <img src="/images/woo.png" alt="Woo Logo" width="32" height="32">

Enhance Integration to WooCommerce subscriptions

## Features

- **Domain Validation**: Ensures that requests are coming from allowed domains, enhancing security against unauthorized access.
- **Plan Mapping**: Ensures that each product is connected with the desired Plans from Enhance.com
- **User Check**: Conducts checks if users exists, if not creates one with his Organization
- **Create Subscription**: If subscription is **completed** according to WooCommerce Subscription hooks then the corresponding plan will be attached with domain and account on enhance.com panel
- **Suspend Subscription**: If subscription is **suspended** according to WooCommerce Subscription hooks then the corresponding plan will be set as Suspended on enhance.com panel
- **Cancel Subscription**: If subscription is **canceled** according to WooCommerce Subscription hooks then the corresponding plan will be deleted on enhance.com panel
- **SSO Login**: If Admin wishes he can insert the shortcode **[fetch_sso_link]** to any area he wishes.


## Installation

1. Download the plugin .
2. Navigate to your WordPress dashboard, go to Plugins > Add New > Upload Plugin.
3. Choose the downloaded plugin file, then click "Install Now".
4. Once the installation is complete, activate the plugin through the 'Plugins' menu in WordPress.

## Usage

After activation, Enhance Integration by Vortex works only with WooCommerce Subscriptions plugin and after you set up your **Keys** on Enhance Panel

## Requirements

- WordPress 5.0 or higher.
- PHP 7.2 or higher.

## Contributing

We welcome contributions! If you'd like to contribute, please fork the repository and submit a pull request.

1. **Fork it!**
2. **Create your feature branch:** `git checkout -b my-new-feature`
3. **Commit your changes:** `git commit -am 'Add some feature'`
4. **Push to the branch:** `git push origin my-new-feature`
5. **Submit a pull request.**

## Support

If you encounter any issues or have any questions about using the plugin, please raise issue..

## License

This plugin is licensed under the GPL-2.0-or-later.

---

Developed with ❤ by WebVotex
