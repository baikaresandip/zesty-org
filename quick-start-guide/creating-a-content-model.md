---
description: >-
  Content Model is a collection of content entries with shared settings and
  defined fields.
---

# Creating a Content Model

### Types of Content Models

Content models can be formatted based on the needs of the content and how it is to be displayed. There are three types of Content Models:

* **Single Entry** Item 
  * Includes Meta fields & URLs
* **Multi-Entry** Item Groupings
  * Includes Meta fields & URLs
* Parented or Non-parented **Dataset**
  * Does not include Meta fields nor URLs

### Which Content Model Should I Choose?

Choosing a Content Model type should be based on the needs of viewing and accessing the content within. Which list of options best suits your needs for your content item-set ?

#### ~ Single Entry Item

* [ ] Includes a view located in the Code tab after creation
* [ ] Each field will only need 1 content entry
* [ ] Autogenerated Meta fields and URLs
* [ ] Can be parented 

#### ~ Multi-Entry Item Groupings

* [ ] Includes a view located in the Code tab after creation 
* [ ] Fields are grouped together in rows allowing for multiple entries for the same field grouping. 
* [ ] Each grouping will have its own autogenerated Meta fields and corresponding URLs
* [ ] Can be parented
* [ ] Can be built with a one-to-one Or one-to-many relationship

#### ~ Parented & Non-Parented Dataset

* [ ] Does NOT include views for each grouping \( i.e.: Items that do not require unique URLs\)
  * [ ] Does not have autogenerated Meta fields nor URLs
* [ ] Fields are grouped together in rows allowing for multiple entries for the same field grouping
* [ ] Can be parented OR non-parented \(allowing access in any view\)
  * [ ] Non-parented datasets will be located under the Parentless Dataset tab on the Content Manager Dashboard for easy access and organization 
  * [ ] Non-parented datasets can be thought of as **global**. 

### Creating the Model

Navigate to the Schema tab in the sidebar to the left. On the schema home screen will be provided with a blank content model creation form. You can also trigger this form manually with the create model button from the schema screen in the top left corner.

![](../.gitbook/assets/image%20%2851%29.png)

Within the content model creation form, you will have the ability to choose the content model that suits your content based on the parameters above. Parent your model, if necessary, an more

![Creating a content model](../.gitbook/assets/image%20%2848%29.png)

### Defining a Content Model's Schematics

Defining fields within your Content Model allow you to define the type of content to be included, as well as the relationship those fields may have to other Content Models. For example a _One-to-One_ OR _One-to-Many_ correlation. Each type of Field will have specific functionality and output based on the selection. For a complete list of fields and definitions, please click [here](../services/manager-ui/schema/fields.md#overview). 

### 1. Selecting your Content Model 

After creating your Content Models, you can find your complete list of models in the Schema tab. If you have just created your content model you will automatically be redirected to the content model. If not, select the Content Model you would like to define a schema for. Upon selection you will be presented with a screen that looks like the one below. From this screen you will be able to see the details of the Content Model on the right including: 

* Content model type
* Content model ZUID
* Label and Parsley reference name
* URL and multi-item details 
* Model settings and Delete Model 
* and quick access links to edit content or code 

![](../.gitbook/assets/image%20%2858%29.png)

### 2. Adding and Defining Fields

To add content you will select a filed type that will define the type of content held within. Once selected you will be presented with a form to complete regarding the field being created. The form will include:

* Field Label
* Field Name \(the name used to reference this field via Parsley\)
* Tool Tip display
* Description displayed to content editors
* Is this field required toggle
* Show value in table toggle
* And specific field needs based on the type of field selected. \(i.e.: Parent for One-to-One or One-to-Many field types\)

![](../.gitbook/assets/image%20%2898%29.png)

### 3. Proceed to Adding content

After completing all of the field additions needed for a Content Model, you can proceed to the to Content tab and select the model you would like to begin adding content to.

{% hint style="info" %}
**Hint**: You can continue to add fields to your schema at any time after creating your Content Model. As additional field needs arise, simply proceed to the corresponding schema and build on to the content.
{% endhint %}

### Next Steps

Covered in the next section is adding and updating content. Along with adding unique Meta data and Head tags to content models.

