# Angular Form : New User

![Image Empty Form](images/form-empty.png)
## Description

The New User Form application exemplifies using a simple template based Form that uses a data service to hold the submitted value. the data service provides an Observable stream to monitor updates. A table component subscribes to the data service and displays the more recently submitted user info.

The New User Form application is composed of 3 components and 1 service:

## Components

* AppComponent
* FormNewUserComponent
* UserInfoComponet

## Service

* NewUserService


## Architecture

![Image App UML](images/app-uml.png)

The Angular app makes use of RxJS to create a continious data stream to publish the User info. When the _Create_ button is clicked on, the user data is send to the service using a API call. The service then publishes the data using the RxJS Subject.

The HTML Form is provided by the `FormNewUserComponent` component, while the table display of the User info is presneted by the `UserInfoComponent`, it simplies subscribes to the Subject publishing the data,

## Opening Augury
To use Augury, we need to open DevTools.

```
Ctrl + Shift + I (Cmd + Opt + I on Mac)
```

When DevTools is open, select the **Augury** tab, located on the far right. In DevTools, under the "Component Tree" tab, you will see the following parent and children tree relationship of Angular Component and the HTML DOM elements.

![Image Component Tree](images/component-tree.png)

This is the default view setting, which is called the "Hybrid view". This view setting can be changed, from the settings [todo]: need ui name?.

![Image Component Tree View Settings](images/component-tree-view-setting.png)

## Component View

Augury shows that the New User Form Angular application has 3 components. The root application component is called `AppComponent` which in turn contains

---
### The Augury Team!

[Copyright notice etc.]
