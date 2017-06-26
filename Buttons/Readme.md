# Buttons

## Description

Buttons allow the user to select actions and interact with the platform. Use button styles consistently to help the user predict and understand available actions within a flow.

---

## Default buttons indicate secondary actions to the user. Default button actions are subordinate to any primary button actions within the view.

### Button Default
```HTML
<button class="btn btn-default">Button</button>
```
![alt text](../images/btn-default.png "Button Default")
### Button Active/Selected
```HTML
<button class="btn btn-default active">Active/Selected</button>
```
![alt text](../images/btn-active.png "Button Active")

---
## Buttons that can indicate positive, forward-moving actions such as Next and Save.
### Button Primary
```HTML
<button class="btn btn-primary">Button</button>
```
![alt text](../images/btn-primary.png "Button Primary")
### Button Success
```HTML
<button class="btn btn-success">Button</button>
```
![alt text](../images/btn-success.png "Button Success")
### Button Success Subdued
```HTML
<button class="btn btn-success-subdued">Button</button>
```
![alt text](../images/btn-success-subdued.png "Button Success Subdued")

---
## Buttons that can indicate negative, or destructive actions such as Remove and Delete.
### Button Destructive
```HTML
<button class="btn btn-destructive">Button</button>
```
![alt text](../images/btn-destructive.png "Button Destructive")
### Button Destructive Subdued
```HTML
<button class="btn btn-destructive-subdued">Button</button>
```
![alt text](../images/btn-destructive-subdued.png "Button Destructive Subdued")
### Button Warning
```HTML
<button class="btn btn-warning">Button</button>
```
![alt text](../images/btn-warning.png "Button Warning")

---
## Icon buttons with commonly-used, recognizable icons. Include a tooltip on hover to describe the icon button’s action.

Icon buttons can be styled with or without borders.
### Button Default with Icon
```HTML
<button class="btn btn-default"><span class="icon icon-add"></span>Button</button>
```
![alt text](../images/btn-default-icon.png "Button Default with Icon")
### Button Icon
```HTML
<button class="btn btn-default icon-tree"></button>
```
![alt text](../images/btn-icon.png "Button Icon")
### Button Icon Active/Selected
```HTML
<button class="btn btn-default icon-tree active"></button>
```
![alt text](../images/btn-icon-active.png "Button Icon Active")
### Button Icon without Border
```HTML
<button class="btn btn-default icon-paperclip"></button>
```
![alt text](../images/btn-icon-noborder.png "Button Icon without Border")

---
### Widget Button
```HTML
<div class="sn-widget sn-widget-button sn-widget-button_row">
	<button class="btn btn-default icon">
		<span class="icon-add-circle-empty"></span>
		<span>Add Member to Group</span>
	</button>
</div>
```
![alt text](../images/btn-widget.png "Button Widget")

---
## Use Guidelines

### Alternately display primary and default actions with an icon and text label. Button elements without outlines or borders generally include this combined use.

### Align text labels in the horizontal center of the accompanying icon. When including items in a list, check that text labels and icons are appropriately aligned.

