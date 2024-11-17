## Action, Activity Configure Understanding Document

### Action

* Action in configuration can mean several different things. Clicking on a button is one of the fundamental meanings, and other activities are referred to as actions.

* Data from one Entity Table Form is transferred to another using this action, which also displays the data on the Details Page when the Action Button is clicked.

### Who to create and use the Action :

* We start by clicking the __Studio__.
* After selecting the collection, select the entity.
* The *Action* menu will appear on the page.
* Clicking the __Create__ button will let you create an action.
* It will Create with the following Fields
  * Id
  * Name
  * Status
  * Version
  * Action

* After clicking the ID, the Action Form page will be redirected. Next, configure the field that you wish to see in the Action form.

* Go to the app and select the __Option__ menu, which appears at the top of the table.

* Click the Option ->More Options -> Scroll down to find the Add Column.

* Click Create ClientField, then add *lable*, *Name*, and *Datatype*. And submit it.

* What you created in the ClientField it visible in the Columns click the settings on the created columns. On the View Option page, the setting is located on the right side.

*  A **Form Config** popup will open then select the **Viwe type** in to **Button**, **Button Type** into **Option Action**, and select the **Action Form** in to Action we created in the entity then Submit it.

* Then goto __Data Source__ in the __View Option__ page select the __Datasource Type__ in to __Entity__, select __Entity List__ into you Entity name, select __Action type__ into *create, updata, delete* based on you needs and purpose.

* Field value:
  * If you want the table data you will use the __params__.

    Ex: you want Table data - __{{params.value}}__.

  * If you want the form data you will use the __FormData__.

    Ex: you want Form data - __{{FormData.value}}__.

### Activity		

 Although it has a slight modification on the details page, __Activity__ functions similarly to __Action__.

 * On the details page, the __Action__ is at the top and the __Activity__ is at the bottom.


  