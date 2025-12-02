# HRB WebSDK Debugger – Privacy Policy

Last updated: 2025-12-02

## Single Purpose

This extension provides a Chrome DevTools panel to capture, decode, and visualize Adobe Experience Platform Web SDK (Alloy) network requests for debugging implementations.

## Data Collection and Usage

- We do not collect, transmit, sell, or share personal data.
- Decoded network payloads are displayed locally within DevTools for the active tab/session.
- Payloads are not persisted, exported, or transmitted off-device by the extension.
- Only non-personal user preferences (e.g., panel filters and view settings) may be stored via Chrome storage APIs.

## Permissions and Justifications

- Host permissions (<all_urls>): Needed to observe AEP Web SDK requests on sites where the SDK runs. The extension does not read or modify page content.
- webRequest: Used to capture and decode outbound Alloy requests for debugging only.
- webNavigation: Used to scope captured requests to the correct tab and reset views on navigation.
- Storage: Used to save non-personal preferences for the DevTools panel.
- Remote code: Not used. The extension does not execute remote scripts or use eval-like APIs.

## Data Retention

- No network payloads are retained by the extension. Preferences are retained until the user clears extension data or uninstalls the extension.

## Security

- All logic runs from the packaged extension. No external script execution.
- Decoded data remains local to the user’s browser.

## Contact

For privacy questions or requests, contact the maintainer via the account email listed in the Chrome Web Store.
