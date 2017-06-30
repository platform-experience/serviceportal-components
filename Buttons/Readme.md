# Button

## Description

Buttons provide a clickable element that allow the user to select actions and interact with the platform. 
<!-- Button classes can be applied on an `<a>`, `<button>`, or `<input>` element.-->

<p><br/><br/><br/><br/></p>

## Button Default
---
Default buttons indicate secondary actions to the user. Default button actions are subordinate to any primary button actions within the view.

![alt text](../images/btn-default.png "Button Default")
```HTML
<button class="btn btn-default">Button</button>
```

#### Active/Selected
---
![alt text](../images/btn-active.png "Button Active")
```HTML
<button class="btn btn-default active">Active/Selected</button>
```

<p><br/><br/><br/><br/></p>

## Button Primary
---
Buttons that can indicate positive, forward-moving actions such as Next and Save.

![alt text](../images/btn-primary.png "Button Primary")
```HTML
<button class="btn btn-primary">Button</button>
```

#### Success
---
![alt text](../images/btn-success.png "Button Success")
```HTML
<button class="btn btn-success">Button</button>
```

#### Success Subdued
---
![alt text](../images/btn-success-subdued.png "Button Success Subdued")
```HTML
<button class="btn btn-success-subdued">Button</button>
```

<p><br/><br/><br/><br/><br/></p>


## Button Destructive
---
Buttons that can indicate negative, or destructive actions such as Remove and Delete.

![alt text](../images/btn-destructive.png "Button Destructive")
```HTML
<button class="btn btn-destructive">Button</button>
```

#### Destructive Subdued
---
![alt text](../images/btn-destructive-subdued.png "Button Destructive Subdued")
```HTML
<button class="btn btn-destructive-subdued">Button</button>
```

#### Button Warning
---
![alt text](../images/btn-warning.png "Button Warning")
```HTML
<button class="btn btn-warning">Button</button>
```

<p><br/><br/><br/><br/></p>

## Icon Button
---
Icon buttons with commonly-used, recognizable icons. Include a tooltip on hover to describe the icon button’s action.

Icon buttons can be styled with or without borders.

![alt text](../images/btn-default-icon.png "Button Default with Icon")
```HTML
<button class="btn btn-default"><span class="icon icon-add"></span>Button</button>
```

#### Icon Only
---
![alt text](../images/btn-icon.png "Button Icon")
```HTML
<button class="btn btn-default icon-tree"></button>
```

#### Icon Active/Selected
---
![alt text](../images/btn-icon-active.png "Button Icon Active")
```HTML
<button class="btn btn-default icon-tree active"></button>
```

#### Icon without Border
---
![alt text](../images/btn-icon-noborder.png "Button Icon without Border")
```HTML
<button class="btn btn-default icon-paperclip"></button>
```

<p><br/><br/><br/><br/></p>

### Widget Button
---
Expanding beyond the basics, using the `sn-widget sn-widget-button sn-widget-button_row` classes can provide more design and style to a button.

![alt text](../images/btn-widget.png "Button Widget")
``` HTML
<div class="sn-widget sn-widget-button sn-widget-button_row">
  <button class="btn btn-default icon">
    <span class="icon-add-circle-empty"></span>
    <span>Add Member to Group</span>
  </button>
</div>
```

<p><br/><br/><br/><br/></p>
