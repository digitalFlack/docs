---
title: Ethereal: Recreating the Demo - Our Team Page
description: Your Guide to Recreating Elements of the Ethereal Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ethereal:Ethereal

---

## Introduction

The **Our Team** example page demonstrates how you can create a beautiful page with the Ethereal template. Here is some information to help you replicate this page as it appears in the demo.

## Modules and Particles

Below is a brief rundown of the modules and particles used to make up the demo page.

![](assets/page_ourteam.jpeg)

:   1. **Showcase - Custom HTML (Module)** [9%, 45%, se]
    2. **Mainbar - Page Content** [14%, 15%, se]
    3. **Feature - Custom HTML (Module)** [28%, 15%, se]
    4. **Extension - Custom HTML (Module)** [33%, 15%, se]
    5. **Bottom - Custom HTML (Module)** [70%, 35%, se]
    6. **Footer - Custom HTML (Module)** [80%, 15%, se]
    7. **Footer - Custom HTML (Module)** [80%, 38%, se]
    8. **Footer - Custom HTML (Module)** [80%, 65%, se]

1. [Showcase](#showcase-section)
2. [Mainbar](#mainbar-section)
3. [Feature](#feature-section)
3. [Extension](#extension-section)
4. [Bottom](#bottom-section)
4. [Footer](#footer-section)

## Showcase Section

![](assets/page_ourteam_1.jpeg)

This area of the page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Module)

### Details

| Field      | Setting             |
| :-----     | :-----              |
| Title      | `Our Team - Header` |
| Show Title | Hide                |
| Position   | `showcase-a`        |
| Status     | Published           |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-layercontent g-layercontent-small">
  <h2 class="g-layercontent-title">Our Team</h2>
  <div class="g-layercontent-subtitle">Meet the People Behind Ethereal</div>
</div>
~~~

### Basic

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

| Option              | Setting        |
| :----------         | :----------    |
| Module Class Suffix | `flush center` |

## Feature Section

![](assets/page_ourteam_2.jpeg)

This area of the page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Module)

### Details

| Field      | Setting             |
| :-----     | :-----              |
| Title      | `Joe Jensen - Paul Lee` |
| Show Title | Hide                |
| Position   | `feature-a`        |
| Status     | Published           |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-grid">
  <div class="g-block box4 size-50">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-01.jpg">
      <h2>
        Joe Jensen
      </h2>
      <p>
        Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas.
      </p>
      <p>
        Image attribution: <a href="http://www.flickr.com/photos/astragony/8260117875/sizes/l/">AMaze by Daniele Zedda</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
  <div class="g-block box4 size-50">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-02.jpg">
      <h2>
        Paul Lee
      </h2>
      <p>
        Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas.
      </p>
      <p>
        Image attribution: <a href="http://www.flickr.com/photos/astragony/4728211246/sizes/l/">Stare by JohnONolan</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
</div>
~~~

### Basic

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | Blank       |

## Mainbar Section

![](assets/page_ourteam_3.jpeg)

The **Mainbar** section includes the **Our Team** article, displayed through the **Page Content** particle. Here are the settings found in the **Our Team** article.

| Option   | Setting        |
| :-----   | :-----         |
| Title    | `Our Team`     |
| Alias    | `our-team`     |
| Status   | Published      |
| Featured | No             |
| Category | `Sample Pages` |

**Content Body**

~~~ .html
<h3><em>"Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service." - Robert Smith</em></h3>
~~~

## Extension Section

![](assets/page_ourteam_4.jpeg)

This area of the page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Module)

### Details

| Field      | Setting                                 |
| :-----     | :-----                                  |
| Title      | `Team Photos` |
| Show Title | Hide                                    |
| Position   | `extension-a`                           |
| Status     | Published                               |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-grid">
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-03.jpg">
      <h2 class="g-title">
        Louis Wells
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="https://www.flickr.com/photos/johnonolan/5378754404/sizes/l/">JohnONolan</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-04.jpg">
      <h2 class="g-title">
        Sara Valdez
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="http://www.flickr.com/photos/thomasleuthard/5807793226/sizes/l/">Thomas Leuthard</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-05.jpg">
      <h2 class="g-title">
        Joseph Hart
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="http://www.flickr.com/photos/astragony/5959165576/sizes/l/">Daniele Zedda</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
</div>
<div class="g-grid">
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-06.jpg">
      <h2 class="g-title">
        Amy Guzman
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="http://www.flickr.com/photos/mr-h/4217144639/sizes/l/">AllansBrain</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-07.jpg">
      <h2 class="g-title">
        Randy Hicks
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="http://www.flickr.com/photos/carianoff/5327733275/sizes/l/">carianoff</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-08.jpg">
      <h2 class="g-title">
        Grace Patel
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="http://www.flickr.com/photos/carianoff/4070347417/sizes/l/">carianoff</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
</div>
<div class="g-grid">
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-09.jpg">
      <h2 class="g-title">
        Roy Fisher
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="http://www.flickr.com/photos/carianoff/5328421868/sizes/l/">carianoff</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-10.jpg">
      <h2 class="g-title">
        Pamela Little
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="http://www.flickr.com/photos/carianoff/5328368478/sizes/l/">carianoff</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
  <div class="g-block box-grey size-33-3">
    <div class="g-content">
      <img alt="image" src="images/rocketlauncher/pages/our-team/img-11.jpg">
      <h2 class="g-title">
        Scott Bell
      </h2>
      <p>
        Collaboratively administrate empowered markets via available great networks.
      </p>
      <p>
        Image by <a href="http://www.flickr.com/photos/carianoff/5327739397/sizes/l/">carianoff</a>.
      </p>
      <div class="g-social">
        <a href="#">
            <span class="fa fa-twitter fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-facebook fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-google fa-fw"></span>
        </a>
        <a href="#">
            <span class="fa fa-linkedin fa-fw"></span>
        </a>  
      </div>
    </div>
  </div>
</div>
~~~

### Basic

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | Blank       |

## Bottom Section

![](assets/page_ourteam_5.jpeg)

This area of the page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Module)

### Details

| Field      | Setting         |
| :-----     | :-----          |
| Title      | `We Are Hiring` |
| Show Title | Hide            |
| Position   | `bottom-a`      |
| Status     | Published       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-layercontent g-layercontent-small">
  <h2 class="g-layercontent-title">We Are Hiring</h2>
  <div class="g-layercontent-subtitle">Join Our Awesome Team with a Great Work Environment</div>
  <a href="http://www.rockettheme.com/joomla/templates/ethereal" class="button button-2">Join Ethereal</a>
</div>
~~~

### Basic

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

| Option              | Setting        |
| :----------         | :----------    |
| Module Class Suffix | `flush center` |

## Footer Section

![](assets/page_aboutus_6.jpeg)

:   1. **Custom HTML (Module) 1** [20%, 5%, se]
    2. **Custom HTML (Module) 2** [20%, 38%, se]
    3. **Custom HTML (Module) 3** [20%, 65%, se]

This area of the page is made up of three **Custom HTML** modules spanning three different module positions: `footer-a`, `footer-b`, and `footer-c`. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Custom HTML (Module) 1

### Details

| Field      | Setting          |
| :-----     | :-----           |
| Title      | `About Ethereal` |
| Show Title | Show             |
| Position   | `footer-a`       |
| Status     | Published        |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p>All demo content is for sample purposes only, intended to represent a live site.</p>

<p>The sample pages are intended to show how Ethereal can be constructed on your site.</p>
~~~

### Basic

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | Blank       |

### Custom HTML (Module) 2

### Details

| Field      | Setting      |
| :-----     | :-----       |
| Title      | `Newsletter` |
| Show Title | Show         |
| Position   | `footer-b`   |
| Status     | Published    |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-newsletter">
  <div class="g-newsletter-headtext">
    Subscribe to our newsletter and stay updated on the latest developments and special offers!
  </div>
  <form onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true" target="popupwindow" method="post" action="http://feedburner.google.com/fb/a/mailverify" class="g-newsletter-form">
    <input type="text" name="email" placeholder="Email Address" class="g-newsletter-inputbox"> <input type="hidden" name="uri" value="rocketthemeblog"> <input type="hidden" value="en_US" name="loc"> <input type="submit" value="Join" class="g-newsletter-button button button-3" name="Submit">
  </form>
</div>
~~~

### Basic

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | Blank       |

### Custom HTML (Module) 3

### Details

| Field      | Setting          |
| :-----     | :-----           |
| Title      | `Sample Sitemap` |
| Show Title | Show             |
| Position   | `footer-c`       |
| Status     | Published        |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-grid">
    <div class="g-block">
        <ul class="nomarginall noliststyle">
            <li><a href="index.php">Home</a></li>
            <li><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=105">Features</a></li>
            <li><a href="index.php?option=com_content&amp;view=article&amp;id=2&amp;Itemid=106">Typography</a></li>
            <li><a href="index.php?option=com_content&amp;view=article&amp;id=2&amp;Itemid=106">Particles</a></li>
            <li><a href="index.php?option=com_content&amp;view=article&amp;id=3&amp;Itemid=107">Variations</a></li>
        </ul>
    </div>
    <div class="g-block">
        <ul class="nomarginall noliststyle">
            <li><a href="index.php?option=com_content&amp;view=article&amp;id=2&amp;Itemid=106">Buttons</a></li>
            <li><a href="index.php?option=com_content&amp;view=article&amp;id=4&amp;Itemid=111">Pages</a></li>
            <li><a href="http://www.rockettheme.com/docs/joomla/templates/ethereal">Guide</a></li>
            <li><a href="http://www.rockettheme.com/forum/joomla-template-ethereal">Support</a></li>
            <li><a href="http://www.rockettheme.com/joomla/templates/ethereal">Download</a></li>
        </ul>       
    </div>  
</div>
~~~

### Basic

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | Blank       |
