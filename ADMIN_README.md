## Pull Request Notifications

This repository is configured to send email notifications to a Gaggle group whenever a pull request is submitted. This helps maintainers and contributors stay informed about new contributions in real-time.

### Setting Up PR Notifications

To enable PR notifications via Gaggle, you'll need to configure the following GitHub repository secrets:

- `GAGGLE_API_KEY` - Your Gaggle API key
- `GAGGLE_GROUP_EMAIL` - The Gaggle group email to send notifications to (e.g., `notifications@gaggle.email`)

**To add these secrets:**
1. Go to your repository Settings
2. Navigate to Secrets and Variables → Actions
3. Click "New repository secret"
4. Add each of the above secrets with their respective values
