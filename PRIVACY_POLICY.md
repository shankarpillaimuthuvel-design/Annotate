# Privacy Policy for Annotate

**Last Updated:** April 17, 2026

This Privacy Policy describes how the Annotate Chrome Extension ("we", "our", or "the Extension") collects, uses, and protects your information.

## 1. Information We Collect

To provide the core functionality of leaving comments and pins on webpages, we collect and store the following information:

*   **Authentication & Profile Information:** When you sign in using Google OAuth, we collect your email address, Google user ID, and name to create your profile and associate your annotations with your account. You may also choose a custom display name and avatar within the extension.
*   **Annotation Data:** When you create a pin or comment, we collect the content of your comment, the URL of the webpage you are annotating (`page_url`), and the specific location on the page where the pin is placed (CSS `selector`, `offset_x`, and `offset_y`).
*   **Usage State:** We locally store your preference for whether the annotation mode is toggled ON or OFF.

## 2. How We Use Your Information

We use the collected information solely for the purpose of providing and improving the Extension's features:

*   To authenticate you and maintain your session securely.
*   To display your chosen name and avatar next to your comments.
*   To save your pins and comments to our database (Supabase) so they persist across browsing sessions and can be loaded when you revisit a page.
*   To accurately position your pins on the correct elements of the webpages you annotate.

## 3. Data Storage and Security

Your authentication state and profile preferences are stored locally on your device using Chrome's secure local storage API. Your annotation data (comments, pin locations, and profile snapshots) is transmitted securely over HTTPS and stored in our Supabase database. We implement standard security measures to protect your data from unauthorized access.

## 4. Third-Party Services

We use the following third-party services:

*   **Google OAuth:** Used exclusively for secure user authentication.
*   **Supabase:** Used as our backend database to store user profiles, pins, and comments.

We do not sell, rent, or trade your personal information or annotation data to any third parties. We do not use your data for advertising or tracking purposes outside of the Extension's core functionality.

## 5. Your Rights

You have the right to access, modify, or delete your personal information and annotations. You can delete individual pins and comments directly within the Extension. If you wish to delete your entire account and all associated data, please contact us.

## 6. Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be reflected by updating the "Last Updated" date at the top of this policy.

## 7. Contact Us

If you have any questions or concerns about this Privacy Policy or our data practices, please contact the developer at: [Insert Your Email Address Here]