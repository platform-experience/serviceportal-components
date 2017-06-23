# Buttons

## Description

Buttons allow the user to select actions and interact with the platform. Use button styles consistently to help the user predict and understand available actions within a flow.


---
## Examples

## Default buttons indicate secondary actions to the user. Default button actions are subordinate to any primary button actions within the view.

### Button Default
```HTML
<button class="btn btn-default">Button</button>
```
<button class="btn btn-default">Button</button>

### Button Active/Selected
```HTML
<button class="btn btn-default active">Active/Selected</button>
```
<button class="btn btn-default active">Active/Selected</button>

---
## Buttons that can indicate positive, forward-moving actions such as Next and Save.
### Button Primary
```HTML
<button class="btn btn-primary">Button</button>
```
<button class="btn btn-primary">Button</button>

### Button Success
```HTML
<button class="btn btn-success">Button</button>
```
<button class="btn btn-success">Button</button>

### Button Success Subdued
```HTML
<button class="btn btn-success-subdued">Button</button>
```
<button class="btn btn-success-subdued">Button</button>

---
## Buttons that can indicate negative, or destructive actions such as Remove and Delete.
### Button Destructive
```HTML
<button class="btn btn-destructive">Button</button>
```
<button class="btn btn-destructive">Button</button>

### Button Subdued
```HTML
<button class="btn btn-destructive-subdued">Button</button>
```
<button class="btn btn-destructive-subdued">Button</button>

### Button Warning
```HTML
<button class="btn btn-warning">Button</button>
```
<button class="btn btn-warning">Button</button>

---
## Icon buttons with commonly-used, recognizable icons. Include a tooltip on hover to describe the icon button’s action.

Icon buttons can be styled with or without borders.
### Button Default with Icon
```HTML
<button class="btn btn-default"><span class="icon icon-add"></span>Button</button>
```
<button class="btn btn-default"><span class="icon icon-add"></span>Button</button>

### Button Icon
```HTML
<button class="btn btn-default icon-tree"></button>
```
<button class="btn btn-default icon-tree"></button>

### Button Icon Active/Selected
```HTML
<button class="btn btn-default icon-tree active"></button>
```
<button class="btn btn-default icon-tree active"></button>

### Button Icon without Border
```HTML
<button class="btn btn-default icon-paperclip"></button>
```
<button class="btn btn-default icon-paperclip"></button>

### Button Icon Active/Selected without Border
```HTML
<button class="btn btn-icon icon-paperclip active"></button>
```
<button class="btn btn-icon icon-paperclip active"></button>

---
## Alternately display primary and default actions with an icon and text label. Button elements without outlines or borders generally include this combined use.

## Align text labels in the horizontal center of the accompanying icon. When including items in a list, check that text labels and icons are appropriately aligned.

### Widget Button
```HTML
<div class="sn-widget sn-widget-button sn-widget-button_row">
	<button class="btn btn-default icon">
		<span class="icon-add-circle-empty"></span>
		<span>Add Member to Group</span>
	</button>
</div>
```
<div class="sn-widget sn-widget-button sn-widget-button_row">
	<button class="btn btn-default icon">
		<span class="icon-add-circle-empty"></span>
		<span>Add Member to Group</span>
	</button>
</div>


---
## Configuration

> None

---
## Dependencies

> None
