# Privacy Policy — Form Recovery

**Last updated:** [add date when you publish]

Form Recovery is a Chrome/Brave extension that auto-saves form data you type into web pages so it can be restored if you accidentally close a tab, refresh, or your browser/PC crashes.

## What data is collected

Form Recovery saves the values you type into visible text fields, textareas, dropdowns, and editable content on web pages, along with the page URL and a timestamp. Password fields and hidden fields are explicitly excluded and are never saved.

## How your data is stored

All saved data is stored **locally on your device** using the browser's built-in `chrome.storage.local` API. Saved entries are automatically deleted after 30 days.

## What is NOT done with your data

- Nothing is sent to any external server.
- Nothing is sold or shared with any third party.
- The extension does not use analytics or tracking of any kind.

## Permissions used and why

| Permission | Why it's needed |
|---|---|
| `storage` | Save and retrieve your form data locally on your device. |
| `activeTab` / `tabs` | Identify the current browser tab so saved data can be restored into the correct page. |
| `contextMenus` | Adds the "Recover Form Data" right-click menu option. |
| `alarms` | Runs a daily cleanup to delete saves older than 30 days. |
| `host_permissions: <all_urls>` | The extension needs to read form fields on whichever site you're filling out, since that can't be predicted in advance. |

## Your data, your control

You can delete saved data for any page at any time using the "Clear Saves" button on the recovery page. Uninstalling the extension removes all locally stored data.

## Changes to this policy

If this policy changes, the "Last updated" date above will be revised.

## Contact

Questions about this policy or the extension can be sent to: **[your contact email]**
