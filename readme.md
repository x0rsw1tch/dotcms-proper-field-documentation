# dotCMS proper field documenation

## Synopsis

dotCMS field hints are often not sufficient when editing content from the perspective of a content contributor. It's handy to have readily visible information about how each individual field is supposed to function and how to properly use it. These modifications do just that.

## What this does (2 Things)

1. Shows field hints by default
1. Can setup HTML to display unrestricted information, much like a custom field

## Installation

1. Setup a new Structure called "Structure Documentation" (Velocity Var:StructureDocumentation)
	1. Requires these fields:
		1. Doc Structure Name (docStructureName), text
		1. Doc Field Name (docFieldName), text
		1. Body (body), textarea
1. Replace JSP files with provided in repo
1. Optional Step: To make hint field a textarea in structure field editor, replace edit_structure.jsp
1. Good to go!

## How to use

### Add documenation to a field

1. Create a new contentlet
1. Provide the Velocity Var name of the structure and the field you want to document
1. Add text/HTML
1. Done

## Compatibility

dotCMS 3.7.1


License: MIT