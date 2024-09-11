# HostMeNow.org Blesta Domain Registrar Plugin

## About
The HostMeNow.org Blesta Registrar Plugin integrates the Domain API directly into your Blesta installation, allowing resellers to automate domain registration, transfers, renewals, and management. To use this module, a HostMeNow.org Domain Reseller account is required.

You can gain access to the Domain API by signing up for a [Domain Reseller account](https://hostmenow.org/domain-reseller.html).

## API Features
The module offers a wide range of domain management features:
* DNS Modifications (A, AAAA, CNAME, MX, TXT)
* Email Forwarding
* Private Registrations 
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
* Access Available TLDs and Account Credits
* API Version Information

For more detailed documentation, visit the HostMeNow.org [Domain API Guide](https://github.com/hostmenowltd/HostMeNow-Domains-Blesta).

## Installation
Follow these steps to install the HostMeNow.org Blesta Registrar Plugin:

1. Download the plugin from [this link](https://github.com/hostmenowltd/HostMeNow-Domains-Blesta).
2. Upload the `hostmenow` directory to your Blesta installation in `/installpath/components/modules/`.
3. In Blesta, go to **Settings** > **Company** > **Modules** > **Available** and click "Install" on the `HostMeNow` module.
4. Enter your API credentials (username and API secret) found in your [HostMeNow.org Dashboard](https://hostmenow.org/backstage/login.php).
5. Ensure your account has a payment method or sufficient credit balance to cover domain registrations and renewals processed through the module.

## Support
For any issues or questions, please reach out by [submitting a support ticket](https://hostmenow.org/backstage/submitticket.php).

## Reporting Issues
If you encounter any bugs or need assistance, please report them via the [HostMeNow.org Helpdesk](https://hostmenow.org/backstage/submitticket.php).

## License
This plugin is open-source software and is licensed under the [MIT License](http://opensource.org/licenses/MIT).
