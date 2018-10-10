# Organising data

## Tags vs. groups

A quick summary of the differences between tags and groups. Remember:

- There is quite a lot of overlap between tags and groups
- You'll learn from experience when to use one and not the other.
- You can reasonably easily change from a group to a tag and visa versa (select all contacts with a tag, and add them to a group)


&nbsp; | Tags | Groups
 --- | --- | ---
Where | Can be added to contacts, activities and cases | Can only be added to contacts
History | No history (unless you have logging turned on) | Includes a history of when a contact was added and removed
Mailings | Limited integration with CiviMail | Basic building block for CiviMail
Profiles | Can be displayed in profiles | Can be displayed in profiles. Can also limit profile listings to a group and add contacts to a group on submission of profiles.
Permissions | Don't interact with permissions | Can be used for CiviCRM ACLs (a type of permissioning


## Exercises

### Creating a custom data set

**You'd like to collect more detailed information on potential funders of your organisation.**

**You want to to collect 'free text' under the following headings...**

- **Background and history**
- **Funders priorities**
- **Strategic fit with our organisation**

**...and a multiple choice question 'Likelihood of funding' which allows users to select **one** of the following**

- **Certain**
- **Very likely**
- **Moderate**
- **Unlikely**
- **Impossible**

**Since we only want to collect this information for certain organisations, it makes sense to create a new contact type based on organisations called Funders.**

1) Create a new contact type that extends Organisations called funder.

2) Create a custom data set that is attached to Funders. There are quite a few options when it comes to creating custom data sets.

3) Add custom data fields as above to this group

4) Create a couple of new funders. Feel free to use your own information or the details below.

Field | Walter Foundation | Cadence Trust
--- | --- | ---
Background and history | Founded in 1995 by private individual | Established 1950
Funders priorities | Improve access to education | Promoting sustainable agriculture
Strategic fit with our organisation | Fits with our education projects | Potentially fits with our city farms project.
Likelihood of funding | Very likely | Moderate

### Searching for custom data

Now that we have some data in CiviCRM, use the **Advanced search** for all organisations that are very likely to fund your organisation (hopefully you will find one!)

Note: if you are having trouble finding the Likelihood of funding field in advanced search, make sure that you have set it to searchable.

### Custom data settings

Using the custom data set you created above, explore how the following four options effect the display of data.

- Display Style
- Collapse this set on initial display
- Collapse this set in Advanced Search
- Is this Custom Data Set active?
