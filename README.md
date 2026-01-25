# HostMeNow.org Blesta Domain Reseller Module

## About
The HostMeNow.org Blesta Registrar Plugin integrates the Domain API directly into your Blesta installation, allowing resellers to automate domain registration, transfers, renewals, and management. To use this module, a HostMeNow.org Domain Reseller account is required.

You can gain access to the Domain API by signing up for a [Domain Reseller account](https://hostmenow.org/domain-reseller.html) or contact our support team:

- **Email:** support@hostmenow.org
- **Live Chat:** Visit [HostMeNow.org](https://hostmenow.org) and chat with our support team

## API Features
The module offers a wide range of domain management features:
* DNS Modifications (A, AAAA, CNAME, MX, TXT)
* Email Forwarding
* Private Registrations (ID Protection)
* Contact Information Management
* Enable/Disable Registrar Lock
* Retrieve Domain Auth Code (EPP)
* Domain and URL Forwarding
* Register, Transfer, and Renew Domains
* Manage and Delete Domains
* Modify and Retrieve Nameservers
* Modify ID Protection
* Check Domain Synchronization Status
* Domain Availability Checks
* Access Available TLDs and Pricing
* Automatic TLD Pricing Import

For more detailed documentation, visit the HostMeNow.org [Domain API Guide](https://github.com/hostmenowltd/HostMeNow-Domains-Blesta).

## Installation
Follow these steps to install the HostMeNow.org Blesta Registrar Plugin:

1. Download the plugin from [this link](https://github.com/hostmenowltd/HostMeNow-Domains-Blesta).
2. Upload the `hostmenow_domains` directory to your Blesta installation in `/installpath/components/modules/`.
3. In Blesta, go to **Settings** > **Company** > **Modules** > **Available** and click "Install" on the `HostMeNow Domain Reseller` module.
4. Click **Add Account** and enter your API credentials:
   - **API Endpoint:** `https://hostmenow.org/backstage/modules/addons/domain_reseller/api.php`
   - **API Key:** Enter your API key from the HostMeNow Domain Reseller Area at [https://hostmenow.org/backstage/](https://hostmenow.org/backstage/)
   - **Enable Logging:** Check this option for debugging (optional)
5. Configure domain packages in **Packages** > **Browse** and assign them to use the HostMeNow Domain Reseller module.
6. Ensure your account has a payment method or sufficient credit balance to cover domain registrations and renewals processed through the module.

## Requirements
- Blesta 5.0 or higher
- PHP 7.4 or higher
- cURL extension enabled

## API Documentation
For detailed API documentation and custom integrations, see the main [API Documentation](../README.md).

## Support
For any issues or questions, please reach out by [submitting a support ticket](https://hostmenow.org/backstage/submitticket.php).

## Reporting Issues
If you encounter any bugs or need assistance, please report them via the [HostMeNow.org Helpdesk](https://hostmenow.org/backstage/submitticket.php).

## License
This plugin is open-source software and is licensed under the [MIT License](http://opensource.org/licenses/MIT).

---

**Version:** 1.1.0
**Last Updated:** January 2026
