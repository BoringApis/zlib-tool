# Privacy Policy for Zlib Tool

Effective date: August 18, 2026

Zlib Tool is a Chrome extension for encoding and decoding Base64 zlib data.
This policy explains how the extension handles information.

## Information processed

Zlib Tool processes the text, binary data, and metadata that you deliberately
enter into the extension popup or move between its Encode and Decode views.
When you enable **Live decode visible content in all tabs**, it also examines
Base64-shaped strings in rendered visible, non-editable text across supported
browser tabs. This includes tabs that are already open, tabs opened later, and
new content rendered while the feature remains enabled. This content may
include personal or sensitive information.

All encoding and decoding takes place locally on your device. The developer
does not receive or have access to the content you process.

## Information collected

Zlib Tool does not collect personal information, browsing history, website
content, authentication information, location data, financial information, or
extension usage data. Visible page text used by live decoding is processed
locally and is not collected by the developer.

The extension does not use analytics, advertising, telemetry, crash reporting,
remote logging, tracking technologies, or external servers. It makes no network
requests.

## Storage and retention

Inputs, live-page candidates, original page text needed for restoration, and
decoded results exist only in temporary browser memory. Zlib Tool does not
store them in Chrome storage, local storage, synchronized storage, cookies,
files, or a remote database. Per-page state is discarded when the toggle is
turned off, the page navigates, or the tab closes.

## Clipboard access

Zlib Tool does not read from the clipboard. It writes a generated result to the
clipboard only when you select **Copy result**.

## Chrome permissions and website access

Zlib Tool includes the `scripting` permission and declares optional all-sites
host access so it can run the live decoder across browser tabs. Chrome requests
the optional site access only after you enable the footer toggle. While enabled,
the extension registers its packaged decoder for supported existing and future
tabs, temporarily replaces rendered zlib/Base64 text with highlighted decoded
values, and watches for new visible content. Turning the toggle off restores
original text, unregisters the decoder, and asks Chrome to remove the optional
site permission. It does not edit form fields or the website's underlying stored
data and cannot run on restricted Chrome pages.

## Sharing and sale of information

Because the extension does not collect or transmit information, the developer
does not sell, rent, share, or disclose user information to third parties.

## Limited Use

Zlib Tool's use of information received through Chrome APIs adheres to the
Chrome Web Store User Data Policy, including the Limited Use requirements. The
extension uses page content only to provide its user-facing local decoding
feature. It does not transfer the content, use it for advertising, or make it
available for human review.

## Third-party services

Zlib Tool does not integrate with third-party services. Your installation and
use of the Chrome Web Store and Google Chrome remain subject to Google's own
terms and privacy practices.

## Children's privacy

Zlib Tool does not knowingly collect information from children or from any
other users.

## Changes to this policy

If Zlib Tool's data practices change, this policy and the applicable Chrome Web
Store privacy disclosures will be updated before the changed behavior is
released. The effective date above will also be revised.

## Contact

For privacy questions, open an issue in the public GitHub repository that hosts
this policy.
