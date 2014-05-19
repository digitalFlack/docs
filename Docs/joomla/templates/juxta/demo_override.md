---
title: Juxta: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Juxta Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/juxta:Juxta

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings present in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Juxta Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][Juxta2]

:   1. **Logo** [11%, 18%, se]
    2. **Menu** [6%, 18%, se]
    3. **Branding** [92%, 45%, se]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo.

>> Note: In the interest of simplicity, the override settings listed below are presented as they appear on our demo site.

### Style

![][styles]

| Style   | Option               | Position | Setting                                  |
| :------ | :---------------     | :------- | :--------------------------------------  |
| Default | Background Level     |          | High                                     |
| Default | Background Style     |          | Style 2                                  |
| Default | Body Level           |          | High                                     |
| Default | CSS Style            |          | Style 2                                  |
| Default | Link Color           |          | `#701110`                                |
| Default | Article Style        |          | Default                                  |
| Default | Header Graphic Image |          | On                                       |
| Default | Font Settings        |          | Font Family: Georgia, Font Size: Default |

### Features

![][features]

| Style   | Option           | Position  | Setting                                                                    |  
| :------ | :--------------- | :-------- | :------------------------------------------------------------------------- |  
| Default | Logo             | header-a  | Show: On, Auto Size: On                                                    |  
| Default | Date             | utility-b | Show: On, Client-Side Date: Off                                            |  
| Default | Font-Sizer       | feature-b | Show: Off                                                                  |  
| Default | Login Panel      | top-c     | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout` |  
| Default | Branding         | copyright | Show: On                                                                   |  
| Default | Copyright        | copyright | Show: Off, Text: `Designed by RocketTheme`                                 |  
| Default | SmartLoad        |           | Show: Off                                                                  |  
| Default | To-Top Scroller  | copyright | Show: Off, Text: `Scroll to Top`                                           |  
| Default | System Messages  | drawer    | Show: On                                                                   |  
| Default | Reset Settings   | copyright | Show: Off, Text: `Reset Settings`                                          |  
| Default | IE6 Warning      |           | Show: On, Delay: 2000                                                      |  
| Default | Google Analytics |           | Enable: Off                                                                |  


### Menu

![][menu]

| Style   | Option                | Setting                                          |
| :------ | :-------------------- | :----------------------------------------------- |
| Default | Menu Control          | Show: On, Type: Fusion-Menu                      |
| Default | Select a Menu         | Main Menu                                        |
| Default | Position              | navigation                                       |
| Default | Enable JavaScript     | On                                               |
| Default | Menu Opacity          | 1                                                |
| Default | Menu Effect           | Slide + Fade                                     |
| Default | Menu Delay            | 500                                              |
| Default | Menu Animation        | Circ.easeInOut                                   |
| Default | Menu Duration         | 300                                              |
| Default | Pill                  | Enable: Off                                      |
| Default | Enable ID             | Off                                              |
| Default | Module Cache          | On                                               |

### Layouts

![][layouts]

| Style   | Option                     | Setting               |
| :------ | :------------------------- | :-------------------- |
| Default | Top Positions              | Positions: 2, 5:7     |
| Default | Header Positions           | Positions: 1, 12      |
| Default | Showcase Positions         | Positions: 3, 4:4:4   |
| Default | Feature Positions          | Positions: 4, 3:3:3:3 |
| Default | Utility Positions          | Positions: 4, 3:3:3:3 |
| Default | MainTop Positions          | Positions: 3, 4:4:4   |
| Default | MainBody Positions         | Positions: 2, 8:4     |
| Default | MainBottom Positions       | Positions: 2, 4:8     |
| Default | Bottom Positions           | Positions: 2, 6:6     |
| Default | Footer Positions           | Positions: 3, 4:4:4   |

### Mobile

![][mobile]

| Style   | Option               | Position          | Setting                                                    |  
| :------ | :------------------- | :---------------- | :--------------------------------------------------------- |  
| Default | iPhone Custom Theme  |                   | On                                                         |  
| Default | Android Custom Theme |                   | On                                                         |  
| Default | Scalable Content     |                   | Off                                                        |  
| Default | Standard View Switch | mobile-copyright  | Enable: On, Position: mobile-copyright                     |  
| Default | Mobile Menu          |                   | Menu: Main Menu, Menu Animation: Slide                     |  
| Default | Image Resize         |                   | Enabled: On, Min-Width: 80, % of Resize: 25%               |  
| Default | Showcase Background  |                   | From: #ededed, To: #fff, Start: left top, End: left bottom |  
| Default | Positions Aliases    | mobile-drawer     | drawer                                                     |  
| Default | Positions Aliases    | mobile-top        | top-a                                                      |  
| Default | Positions Aliases    | mobile-header     | header-b                                                   |  
| Default | Positions Aliases    | mobile-navigation | mobile-navigation                                          |  
| Default | Positions Aliases    | mobile-showcase   | header-a                                                   |  
| Default | Positions Aliases    | mobile-footer     | footer-a                                                   |  
| Default | Positions Aliases    | mobile-copyright  | copyright                                                  |  

### Advanced

![][advanced]

| Style   | Option             | Setting                                                              |  
| :------ | :----------------- | :------------------------------------------------------------------- |  
| Default | Gantry Cache       | Enabled: On, Cache Timeout: 900                                      |  
| Default | Input Styling      | Enabled: On, Exclusions: `'.content_vote','#rt-popup','#vmMainPage'` |  
| Default | Display Component  | On                                                                   |  
| Default | Display Mainbody   | On                                                                   |  
| Default | RTL Support        | On                                                                   |  
| Default | Build Titles Spans | Off                                                                  |  
| Default | Page Suffix        | On                                                                   |  
| Default | Third Party        | Off                                                                  |  

[demo25]: assets/juxta.jpg
[menu]: ../../start/menu.md
[Style]: http://www.gantry-framework.org/documentation/joomla/configure
[Juxta2]: assets/juxta2.jpeg
[styles]: assets/setstyle.jpeg
[features]: assets/setfeatures.jpeg
[menu]: assets/setmenu.jpeg
[layouts]: assets/setlayouts.jpeg
[mobile]: assets/setmobile.jpeg
[advanced]: assets/setadvanced.jpeg