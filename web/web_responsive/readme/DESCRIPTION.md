> **Odoo 20 port by the Maxdoo Team.** This is *not* the official OCA version. It is a
> simple port of OCA/web `19.0` (commit `d3748a6ea5`) to Odoo 20, offered as a courtesy
> from the Maxdoo Team on behalf of Benedito Monteiro, meanwhile the official OCA version
> for Odoo 20 is not released. All original authors, copyrights and the LGPL-3 license
> are preserved; once the official version is available, prefer it.

This module adds responsiveness to web backend.

**Features for all devices**:

- Redirect to the dashboard after logging in.
Users will only be redirected to the home page after login
if they have enabled the 'Redirect to Home' option in
their profile settings.

  ![image](../static/img/redirecthome.gif)

- New navigation with the fullscreen app menu

  ![image](../static/img/appmenu.gif)

- Quick menu search inside the app menu

  ![image](../static/img/appsearch.gif)

- Sticky header & footer in list view

  ![image](../static/img/listview.gif)

- Sticky statusbar in form view

  ![image](../static/img/formview.gif)

- Bigger checkboxes in list view

  ![image](../static/img/listview.gif)

**Features for mobile**: \* View type picker dropdown displays
comfortably

- Control panel buttons use icons to save space.

  ![image](../static/img/form_buttons.gif)

- Followers and send button is displayed on mobile. Avatar is hidden.

  ![image](../static/img/chatter.png)

- Big inputs on form in edit mode

**Features for desktop computers**:

- Keyboard shortcuts for easier navigation, **using \`Alt + Shift +
  \[NUM\]\`** combination instead of just Alt + \[NUM\] to avoid
  conflict with Firefox Tab switching. Standard Odoo keyboard hotkeys
  changed to be more intuitive or accessible by fingers of one hand.
  F.x. Alt + S for Save

  ![image](../static/img/shortcuts.gif)

- Autofocus on search menu box when opening the app menu

  ![image](../static/img/appsearch.gif)

- When the chatter is on the side part, the document viewer fills that
  part for side-by-side reading instead of full screen. You can still
  put it on full width preview clicking on the new maximize button.

  ![image](../static/img/document_viewer.gif)

- When the user chooses to send a public message the color of the
  composer is different from the one when the message is an internal
  log.

  ![image](../static/img/chatter-colors.png)
