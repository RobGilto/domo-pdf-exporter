# Privacy Policy - Domo Dashboard PDF Exporter

**Last Updated:** December 11, 2025

**Extension ID:** fmbifmggajdhnoiogdhplcjffbnmadhc

## Overview

The Domo Dashboard PDF Exporter is a browser extension designed to help users export Domo App Studio dashboards to PDF format using high-quality full-page screenshots. This extension is committed to protecting your privacy and operates with complete transparency.

## Our Privacy Commitment

**We do not collect, transmit, or store any personal information.** All data processing happens locally on your device, and no information ever leaves your browser.

## What Data Does the Extension Access?

The extension accesses the following data solely for the purpose of generating PDF exports:

### Website Content
- **Dashboard Screenshots**: Visual captures of your Domo App Studio dashboards, including charts, graphs, text, and images
- **Dashboard Metadata**: Dashboard titles, dropdown selector values, and page identifiers used for PDF file naming
- **API Responses**: Temporary capture of dashboard data during the export process

### Important Clarifications
- ✅ All data is processed **locally** in your browser
- ✅ **No data is transmitted** to external servers
- ✅ **No data is shared** with third parties
- ✅ **No personal information** is collected
- ✅ **No tracking or analytics** are used

## How Is Data Used?

Data accessed by the extension is used exclusively for:

1. **Capturing Screenshots**: Taking multiple viewport screenshots while scrolling to create a full-page capture
2. **Generating PDFs**: Stitching screenshots together and creating a PDF document using the bundled jsPDF library
3. **File Naming**: Extracting dashboard titles and filter values to create descriptive PDF filenames

## Data Storage

### Temporary Local Storage
The extension uses browser local storage (`chrome.storage.local`) to temporarily store:
- Dashboard metadata during the PDF generation process
- API responses needed for the export

### Data Retention
- All stored data is **temporary** and exists only during the PDF export process
- Data is automatically cleared after the PDF is generated
- No data persists between browser sessions
- No data is synchronized across devices

## Permissions Explained

The extension requires the following permissions to function:

### activeTab
- **Purpose**: Access the current Domo dashboard tab when you click the extension icon
- **Usage**: Only activates when you explicitly click the extension icon to initiate PDF export

### scripting
- **Purpose**: Inject screenshot capture scripts and the jsPDF library into Domo pages
- **Usage**: Required to programmatically scroll the page, capture multiple screenshots, and generate the PDF

### storage
- **Purpose**: Temporarily store dashboard metadata during the PDF export process
- **Usage**: Local storage only; no data is transmitted externally

### host_permissions (https://*.domo.com/*)
- **Purpose**: Access Domo App Studio dashboards
- **Usage**: The extension only works on Domo domains and cannot access any other websites
- **Scope**: Limited exclusively to `*.domo.com` URLs

## Third-Party Services

This extension does **NOT** use any third-party services, including:
- ❌ No analytics or tracking services
- ❌ No external APIs or servers
- ❌ No advertising networks
- ❌ No data collection services

### Bundled Libraries
The extension includes the jsPDF library (bundled in the extension package) for PDF generation. This library runs entirely locally and does not communicate with external servers.

## Data Sharing and Transfer

We do **NOT**:
- Sell or transfer user data to third parties
- Use or transfer user data for purposes unrelated to the extension's single purpose (PDF export)
- Use or transfer user data to determine creditworthiness or for lending purposes
- Transmit any data outside of your local browser environment

## User Control

You have complete control over the extension:
- The extension only activates when you click the extension icon
- You can uninstall the extension at any time through Chrome's extension settings
- Uninstalling the extension removes all associated data

## Security

The extension follows security best practices:
- All code is included in the extension package (no remote code execution)
- Scripts are only injected into Domo domains
- All processing happens locally in your browser
- No network requests are made to external servers

## Children's Privacy

This extension does not knowingly collect or process data from children under the age of 13. The extension is intended for business users of the Domo platform.

## Changes to This Privacy Policy

We may update this privacy policy from time to time to reflect changes in the extension or legal requirements. When we make changes:
- We will update the "Last Updated" date at the top of this policy
- Continued use of the extension after changes constitutes acceptance of the updated policy

## Open Source

This extension's code can be reviewed in our GitHub repository, allowing full transparency into how the extension operates.

## Contact Information

If you have questions, concerns, or requests regarding this privacy policy or the extension's data practices, please contact us:

- **GitHub Issues**: [Create an issue in our repository]
- **Email**: [Your contact email]

## Compliance

This extension complies with:
- Chrome Web Store Developer Program Policies
- General Data Protection Regulation (GDPR) principles
- California Consumer Privacy Act (CCPA) requirements

## Your Rights

Depending on your location, you may have rights including:
- The right to know what data is collected (detailed in this policy)
- The right to access your data (all data is local to your device)
- The right to deletion (uninstall the extension)
- The right to opt-out (don't use the extension)

Since all data processing is local and temporary, these rights are inherently protected by the extension's design.

---

**Summary**: This extension operates with complete privacy. All PDF generation happens locally on your device, no data is transmitted anywhere, and no personal information is collected. You maintain full control over your data at all times.
