# Employers #
The employers page is the primary page for managing employers. In addition to creating, editing, and deleting employer records, the employer page is the only page that allows for the creation of work orders.

![http://machete-crm.googlecode.com/svn/wiki/images/PageEmployer-1.png](http://machete-crm.googlecode.com/svn/wiki/images/PageEmployer-1.png)

The reason that work order creation is on the employer page is that all work orders must be associated with an employer record at the time of creation. There are no employer-less work orders in Machete. Therefore, an employer record must first be selected, and the employer page provides the means do select an employer.

## Searching for an Employer ##
The employer page shows the List employers tab when it is first loaded. It is a good idea to search for an existing employer before creating a new employer. Duplicating an employer record reduces the ability to report how many employers are new vs. returning employers, distorting customer satisfaction analysis.
The search box on the List tab searches all of the employers in Machete, as you type. You do not need to type the entire name or phone number; Machete will search based on the text you provide.

![http://machete-crm.googlecode.com/svn/wiki/images/PageEmployer-Searching-1.png](http://machete-crm.googlecode.com/svn/wiki/images/PageEmployer-Searching-1.png)

Machete searches:
  * using the entire string that you type in; it does not detect words and search for them individually
  * the name field
  * the address field
  * the city field
  * the phone number field

## Editing an existing Employer ##
To edit an existing employer record, first use the List tab on the employer page to search and find the record to edit. Double-click on the employer row in the List tab to open the record tab and edit it.

![http://machete-crm.googlecode.com/svn/wiki/images/PageEmployer-Editing-1.png](http://machete-crm.googlecode.com/svn/wiki/images/PageEmployer-Editing-1.png)

Double-clicking on the employer record row will open a record tab. This provides access to update information on the employer and to create or edit work orders for that employer.

![http://machete-crm.googlecode.com/svn/wiki/images/PageEmployer-Editing-2.png](http://machete-crm.googlecode.com/svn/wiki/images/PageEmployer-Editing-2.png)

Be sure to click the Save button in order to save any changes made to the record.

## Creating a new Employer ##
To create a new employer record, use the Create New Employer tab on the employer page. The tab will provide a blank employer record. Fill out the information and click the Save button.
  * Note: Some fields are required, and cannot be left blank. If you attempt to save a record without providing information for a required field, the field will be highlighted in red. You record is not saved until you put some value in the required field and click the Save button again. If the employer will not provide the information, put �not available� or �N/A� in the field.
Once you save the employer record, a record tab for the new record will open, showing the information you just entered. The record tab will also give access to the work order information for the employer.

## Deleting an Employer ##
To delete an employer record, open the Record tab for the employer you want to delete. On the right hand side, if you have permission to delete records, a button to delete the record will be visible.
  * Note: Deleting an employer record will also delete all work orders and all assignments for that employer. Any survey information associate with those work orders will also be deleted. Deleting employers is only necessary if you�re removing a duplicate employer and have moved existing work orders to a different employer.
Click the delete button to delete the employer record. A dialog box will appear asking to confirm the delete. If you confirm, the employer record and all its work orders and work assignments will be deleted. Use carefully!

## Creating a new Work Order ##
To create a new work order, you must first search for and open a record tab for an existing employer record, or create a new employer record. Creating a new employer will open the record tab when you save the new employer record. At the bottom of the employer record tab, there will be tabs for the work order records.

![http://machete-crm.googlecode.com/svn/wiki/images/PageEmployer-WO-Creating-1.png](http://machete-crm.googlecode.com/svn/wiki/images/PageEmployer-WO-Creating-1.png)

By default, the employer record tab opens the list tab for work orders belong to the employer. This list tab works the same way as the other list tabs: double-click on a work order record to open it. Use the create new work order tab to create a new work order for the employer.

![http://machete-crm.googlecode.com/svn/wiki/images/PageEmployer-WO-Creating-2.png](http://machete-crm.googlecode.com/svn/wiki/images/PageEmployer-WO-Creating-2.png)

Fill in the fields and click the �save�button to save the new work order. The work order is not saved until you use the save button. When you save an order, the Work Assignment tabs will appear.
  * Note: At least one work assignment must be created. Once an assignment is created, the �activate work order� button will be visible at the bottom of the screen. Users must activate orders for them to be visible on the dispatch page.

## Work Order buttons ##
The following functionality is provided through buttons on the work order tab. Some buttons, such as printing, are only visible when editing a work order. To print an order create it, then save it, then open the record and print button will be available.
  * **Print order:** The print order button on the work orders opens a separate browser tab to print the order. The page content is formatted for printing.  On the new page, there are two buttons, �print work order� and �print google maps�. The second print work order button opens the browser dialog box. The print google button opens another browser window to maps.google.com.
The multiple browser pages and print buttons are a quirk of printing from browers. The first button goes to a page with some fields hidden for printing. The second button intiates the brower�s print functionality.
  * **Print Google map:** The print google map button takes the address from the work order, the work site address, and sends it to Google maps to create a map to get the work site. The button assumes that the starting address is Casa Latina's address. If the users wants a different map, they can use the google maps webpage to change the starting address and re-draw the map.
  * **Copy employer info:** This button copies some information from the employer record. Once the information is copied, it can be changed as needed. This button is only available when first creating a record.
  * **Save:** The save button saves the record and returns to the list tab.
  * **Delete:** The delete button will delete the work order and any work assignments created in it. This button is only available to managers.

## Work Order fields ##
While some work order fields are self-explanatory, others require explanation.
  * **Alternate order ID:** Machete has automatically gives a unique ID to each order. However, other numbering systems may exist (such as paper ordering systems), so Machete allows the user to enter an alternate ID for the order. If an ID number is entered, that ID is used for searching and printing. If an ID is not entered, the internal number will be used.
  * **Permanent placement:** Machete will track both temporary and permanent work placement. Permanent job placement can be identified by setting this value to �yes�; otherwise, leave it as �no�.
  * **English required:** Machete has both a required English level for each work assignment and a general English required field. The field on the work order is general; when set to �yes�, it reveals an additional text box to record employer requests regarding language skill requirements. The use of this field is optional and does not affect any other parts of the Machete system.
  * **Worker Requests:** The worker requests buttons allow the user to find and record when an employer requests a specific user. The �add� button creates a modal dialog box that allows the user to search through existing workers, by name or membership ID number. The table within the dialog box works the same way as other tables in Machete: search using the search box and select a record by double-clicking on the record row.

> ![http://machete-crm.googlecode.com/svn/wiki/images/PageEmployer-WO-fields-1.png](http://machete-crm.googlecode.com/svn/wiki/images/PageEmployer-WO-fields-1.png)

> The requests are used in the dispatch process. Workers specifically requested by an employer are visible on the dispatch page using the �Requested� filter. Using the worker requests feature is important because it rewards workers for hard work. The request is tracked by Machete and will be used in reporting and customer satisfaction analysis.

  * **Work order status:** The status of a work order is important for processing work orders. While users of Machete cannot edit the status directly, managers are able to set the status of an order. Order status will be documented in the Work Orders section of the documentation, below.

## Searching for and editing an existing Work Order ##
## Deleting Work Orders ##
## Creating a new Work Assignment ##
## Work Assignment Buttons ##
## Assigning directly (Orphaned Assignment) ##