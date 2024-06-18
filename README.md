# TCAPS Test Server Identification plugin

This is a fork of Adam Larsen's
[Test Server Identification](https://support.powerschool.com/exchange/view.action?download.id=728)
plugin, updated to work with PowerSchool's Enhanced User Interface. Its features include
recoloring the top blue bar of the PowerSchool UI using a revamped color picker, replacing the
PowerSchool SIS text in the blue bar with the name of the server, and setting the sign in
messages for the admin, public, teacher, and substitute portals.

## Installation

1. Download the latest release from the
   [releases page](https://github.com/schaubda/test-server-id/releases).
2. Install the downloaded zip file on PowerSchool's Plugin Configuration page.
3. Enable the TCAPS Test Server Identification plugin.

## Usage

All settings for the plugin are located on the following page:

<ins>EUI</ins>

District Management > Display Preferences > Test Server Display Settings

<ins>Standard UI</ins>

System > Server > Test Server Display Settings

### Settings

| Setting                            | Description                                                                                                                                   |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| Server Name                        | Text entered here will replace the "PowerSchool SIS" text in the top blue bar. It will also be appended to the beginning of every page title. |
| Override Background Color          | Controls whether the color of the top blue bar will be replaced by the color in the Background Color setting.                                 |
| Background Color                   | If the Override Background Color setting is enabled, the color chosen here will replace the blue color in the top bar.                        |
| Student and Parent Sign In Message | A message that will be displayed at the bottom of the login screen for the Parent/Student (Public) portal.                                    |
| Teacher Sign In Message            | A message that will be displayed at the bottom of the login screen for the Teachers portal.                                                   |
| Substitute Teacher Sign In Message | A message that will be displayed at the bottom of the login screen for the Substitute portal.                                                 |
| Administrator Sign In Message      | A message that will be displayed at the bottom of the login screen for the Administrator portal.                                              |