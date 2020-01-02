# Jira scripts

## Dashboard tweaks

### Reduce size of Sprint Health Gadget on the Dashboard

Script: `jira-dashboard-styles-sprint-health.user.js`

This script injects styles that reduce the font size of the Sprint Health Gadget within the Dashboard.

* Before: http://p.tri.be/PaGYhL
* After: http://p.tri.be/9XVPS1

## Navigation tweaks

### Add "Dashboard" link in Global Nav

Script: `jira-global-nav-dashboard.user.js`

This adds a *Dashboard icon* to the Global Navigation sidebar, allowing you to one-click to your dashboard if you have set your default page to the *Your Work* page.

Screencast: http://p.tri.be/ov7Grn

### Add "Your Work" link in Global Nav

Script: `jira-global-nav-your-work.user.js`

This adds a *Your Work* icon to the Global Navigation sidebar, allowing you to one-click to the *Your Work* page if you have set your default page to the *Dashboard* page.

Screencast: Basically...the same as the `jira-global-nav-dashboard.user.js`, only the inverse.

## Ticket page tweaks

### Remove Harvest from ticket page

Script: `jira-remove-harvest.user.js`

Removes the Harvest section in the sidebar of Jira.