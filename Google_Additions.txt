We need to turn this into an automated build process, but it's manual for now. Here are the steps.

# Add the TOS to template.tpl
___TERMS_OF_SERVICE___
By creating or modifying this file you agree to Google Tag Manager's Community
Template Gallery Developer Terms of Service available at
https://developers.google.com/tag-manager/gallery-tos (or such other URL as
Google may provide), as modified from time to time.

# Add the Categories to template.tpl
"categories": ["ANALYTICS", "HEAT_MAP", "SESSION_RECORDING"],

# Commit
Commit those changes to template.tpl

# Update Git Commit SHA
Run `git log` and copy the commit SHA ID for the change you want. Then paste that into metadata.yml and update the sha field.
