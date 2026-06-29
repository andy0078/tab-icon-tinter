# tab-icon-tinter
Add a color mask to any tab's favicon. Choose from 5 presets or enter a custom hex value — change tab icon colors in one click.
Privacy Policy for Tab Icon Tinter

Last updated: June 2026

1. Overview

Tab Icon Tinter ("the Extension") is a Chrome browser extension that applies a color mask to the favicon (tab icon) of web pages. This Privacy Policy explains what data the Extension accesses, how it is used, and how it is stored.

2. Data We Do Not Collect

The Extension does not collect, transmit, sell, or share any personal data. Specifically:

- We do not collect your name, email address, or any identifying information.
- We do not track which websites you visit.
- We do not log any browsing history.
- We do not send any data to external servers or third parties.
- We do not use analytics, advertising SDKs, or tracking scripts.

3. Data Stored Locally

The Extension uses chrome.storage.local to save your color preferences (selected color and mask strength) on a per-tab basis. This data:

- Is stored only on your local device.
- Is never transmitted outside your browser.
- Contains no personal information — only a hex color value and an opacity number.
- Is automatically cleared when you reset the color or close the tab.

4. Permissions Used

The Extension requests the following Chrome permissions:

- activeTab: Required to access the favicon URL of the currently active tab and inject the favicon-tinting script.
- scripting: Required to execute JavaScript on the page in order to replace the favicon with a Canvas-generated tinted version.
- storage: Required to persist your color selection so it is remembered when you reopen the extension popup.

These permissions are used solely to provide the core functionality of the Extension. No data obtained through these permissions is stored remotely or shared with any party.

5. Third-Party Services

The Extension does not integrate with, communicate with, or depend on any third-party services, APIs, or servers.

6. Children's Privacy

The Extension is not directed at children under the age of 13 and does not knowingly collect any information from children.

7. Changes to This Policy

If we make material changes to this Privacy Policy, we will update the "Last updated" date above. Continued use of the Extension after changes constitutes acceptance of the updated policy.

8. Contact

If you have any questions about this Privacy Policy, please contact us by opening an issue on the extension's GitHub repository or via the support email listed on the Chrome Web Store listing.
