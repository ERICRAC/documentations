# Objects
**Tools → Objects**

The **objects** allow you to define the tree structure of your home automation.
All the equipment that you create must belong to an object and can thus be more easily located. We then say that the object is the **relative** equipment.

To give free choice to personalization, you can name these objects as you wish. Usually, we will define the different parts of his house, like the names of the rooms (this is the recommended configuration, by the way).

## Management

You have two options :
- **Add** : Create a new object.
- **Overview** : Displays the list of objects created and their configuration.

## My objects

Once you have created an object, it will appear in this part.

> **Tip**
>
> You can open an object by doing :
> - Click on one of them.
> - Ctrl Clic or Clic Center to open it in a new browser tab.

You have a search engine to filter the display of objects. The Escape key cancels the search.
To the right of the search field, three buttons found in several places in Jeedom:
- The cross to cancel the search.
- The open folder to unfold all the panels and display all the objects.
- The closed folder to fold all the panels.

Once on the configuration of an object, you have a contextual menu with the Right Click on the tabs of the object. You can also use a Ctrl Click or Center Click to directly open another object in a new browser tab.

## Object tab

By clicking on an object, you access its configuration page.
Whatever changes you make, don&#39;t forget to save it.

Here are the different characteristics to configure an object :

- **Object name** : The name of your object.
- **Dad** : Indicates the relative of the current object, this makes it possible to define a hierarchy between the objects. for example : The living room is related to the apartment. An object can have only one relative but several objects can have the same relative.
- **Visible** : Check this box to make this object visible.
- **Hide on the Dashboard** : Check this box to hide the object on the Dashboard. It is still kept in the list, which allows it to be displayed, but only explicitly..
- **Hide on summary &#39;** : Check this box to hide the object on the summary &#39;&#39;. It is still kept in the list, which allows it to be displayed, but only explicitly..
- **Icon** : Allows you to choose an icon for your object.
- **Custom colors** : Activates the consideration of the two optional color parameters.
- **Tag color** : Allows you to choose the color of the object and the equipment attached to it.
- **Tag text color** : Allows you to choose the color of the text of the object. This text will be over the **color of the tag**. You choose a color to make the text readable.
- **Picture** : You have the option to upload an image or delete it. In jpeg format this image will be the background image of the object when you display it on the Dashboard.

> **Tip**
>
> You can change the display order of objects in the Dashboard. In the overview, select your object with the mouse and drag and drop it to give it a new place.

> **Tip**
>
> You can see a graph representing all the elements of Jeedom attached to this object by clicking on the button **Connections**, top right.

> **Tip**
>
> When a device is created and no relative has been defined, it will have as relative : **No**.

## Summary tab

Summaries are global information, assigned to an object, which are displayed in particular on the Dashboard next to its name..

### Bulletin board

The columns represent the summaries assigned to the current object. Three lines are proposed to you :

- **Go up in the global summary** : Check the box if you want the summary to be displayed in the Jeedom menu bar.
- **Hide on desktop** : Check the box if you do not want the summary to appear next to the object name on the Dashboard.
- **Hide on mobile** : Check the box if you do not want the summary to appear when you view it from a mobile.

### Orders

Each tab represents a type of summary defined in the configuration of Jeedom. Click on **Add an order** so that it is taken into account in the summary. You have the choice to select the command of any Jeedom equipment, even if it does not have this object as relative.

> **Tip**
>
> If you want to add a type of summary or to configure the calculation method of the result, the unit, the icon and the name of a summary, you must go to the general configuration of Jeedom : **Settings → System → Configuration : Summaries tab**.

## Overview

The overview allows you to view all the objects in Jeedom, as well as their configuration :

- **ID** : Object ID.
- **Object** : Object name.
- **Dad** : Name of relative object.
- **Visible** : Object visibility.
- **Mask** : Indicates if the object is hidden on the Dashboard.
- **Summary Defined** : Indicates the number of orders per summary. What is in blue is taken into account in the global summary.
- **Hidden Dashboard Summary** : Indicates hidden summaries on the Dashboard.
- **Hidden Mobile Summary** : Show hidden summaries on mobile.