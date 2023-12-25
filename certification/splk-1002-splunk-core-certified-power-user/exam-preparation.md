<span style="font-family: Verdana ; font-size: 1.2em;">

# [SPLK-1002 - Splunk Core Certified Power User](https://www.splunk.com/en_us/training/certification-track/splunk-core-certified-power-user.html)

This solution is not 100% correct

<ol>
<li>
Which one of the following statements about the search command is true?

- [ ] It does not allow the use of wildcards.
- [ ] It treats field values in a case-sensitive manner.
- [ ] It can only be used at the beginning of the search pipeline.
- [X] **It behaves exactly like search strings before the first pipe.**

</li>

---

<li>
Which of the following actions can the eval command perform?

- [ ] Remove fields from results.
- [X] **Create or replace an existing field.**
- [ ] Group transactions by one or more fields.
- [ ] Save SPL commands to be reused in other searches.

</li>

---

<li>
When can a pipe follow a macro?

- [X] **A pipe may always follow a macro.**
- [ ] The current user must own the macro.
- [ ] The macro must be defined in the current app.
- [ ] Only when sharing is set to global for the macro.

</li>

---

<li>
Data models are composed of one or more of which of the following datasets? (Choose all that apply.)

- [X] **Events datasets**
- [X] **Search datasets**
- [X] **Transaction datasets**
- [ ] Any child of event, transaction, and search datasets

</li>

---

<li>
When using the Field Extractor (FX), which of the following delimiters will work? (Choose all that apply.)

- [X] **Tabs**
- [X] **Pipes**
- [X] **Colons**
- [X] **Spaces**

</li>

---

<li>
Which group of users would most likely use pivots?

- [X] **Users**
- [ ] Architects
- [ ] Administrators
- [ ] Knowledge Managers

</li>

---

<li>

When multiple event types with different color values are assigned to the same event, what determines the color displayed for the event?

- [ ] Rank
- [ ] Weight
- [X] **Priority**
- [ ] Precedence

</li>

---

<li>

Based on the macro definition shown below, what is the correct way to execute the macro in a search string?
![](C:\Users\furqo\OneDrive\Desktop\splk-1002-prep-8.jpg)

- [ ] "convert_sales(euro,ג‚¬,.79)"
- [X] **'convert_sales(euro,ג‚¬,.79)'**
- [ ] "convert_sales($euro$,$ג‚¬$,$.79$)"
- [ ] 'convert_sales($euro$,$ג‚¬$,$.79$)'

</li>

---

<li>

There are several ways to access the field extractor. Which option automatically identifies the data type, source type, and sample event?

- [X] **Event Actions > Extract Fields**
- [ ] Fields sidebar > Extract New Fields
- [ ] Settings > Field Extractions > New Field Extraction
- [ ] Settings > Field Extractions > Open Field Extractor

</li>

---

<li>

Which of the following statements would help a user choose between the transaction and stats commands?

- [ ] stats can only group events using IP addresses.
- [ ] The transaction command is faster and more efficient.
- [X] **There is a 1000 event limitation with the transaction command.**
- [ ] Use stats when the events need to be viewed as a single correlated event.

</li>

---

<li>

By default, how is acceleration configured in the Splunk Common Information Model (CIM) add-on?

- [X] **Turned off.**
- [ ] Turned on.
- [ ] Determined automatically based on the sourcetype.
- [ ] Determined automatically based on the data source.

</li>

---

<li>

Which of the following statements describe the Common Information Model (CIM)? (Choose all that apply.)

- [X] **CIM is a methodology for normalizing data.**
- [X] **CIM can correlate data from different sources.**
- [X] **The Knowledge Manager uses the CIM to create knowledge objects.**
- [X] **CIM is an app that can coexist with other apps on a single Splunk deployment.**

</li>

---

<li>

Which of the following knowledge objects represents the output of an eval expression?

- [ ] Eval fields
- [X] **Calculated fields**
- [ ] Field extractions
- [ ] Calculated lookups

</li>

---

<li>

What do events in a transaction have in common?

- [ ] All events in a transaction must have the same timestamp.
- [ ] All events in a transaction must have the same sourcetype.
- [ ] All events in a transaction must have the exact same set of fields.
- [X] **All events in a transaction must be related by one or more fields.**

</li>

---

<li>

Which delimiters can the Field Extractor (FX) detect? (Choose all that apply.)

- [X] **Tabs**
- [X] **Pipes**
- [X] **Spaces**
- [X] **Commas**

</li>

---

<li>

A data model consists of which three types of datasets?

- [ ] Constraint, field, value.
- [X] **Events, searches, transactions.**
- [ ] Field extraction, regex, delimited.
- [ ] Transaction, session ID, metadata.

</li>

---

<li>

Where are the results of eval commands stored?

- [X] **In a field.**
- [ ] In an index.
- [ ] In a KV Store.
- [ ] In a database.

</li>

---

<li>

Which of the following statements describe calculated fields? (Choose all that apply.)

- [X] **Calculated fields can be used in the search bar.**
- [x] **Calculated fields can be based on an extracted field.**
- [ ] Calculated fields can only be applied to host and sourcetype.
- [x] **Calculated fields are shortcuts for performing calculations using the eval command.**

</li>

---

<li>

Calculated fields can be based on which of the following?

- [ ] Tags
- [X] **Extracted fields**
- [ ] Output fields for a lookup
- [ ] Fields generated from a search string

</li>

---

<li>

When should transaction be used?

- [ ] Only in a large distributed Splunk environment.
- [ ] When calculating results from one or more fields.
- [X] **When event grouping is based on start/end values.**
- [ ] When grouping events results in over 1000 events in each group.

</li>

---

<li>

When performing a regular expression (regex) field extraction using the Field Extractor (FX), what happens when the require option is used?

- [ ] The regex can no longer be edited.
- [ ] The field being extracted will be required for all future events.
- [ ] The events without the required field will not display in searches.
- [X] **Only events with the required string will be included in the extraction.**

</li>

---

<li>

When using | timechart by host, which field is represented on the x-axis?

- [ ] date
- [ ] host
- [ ] time
- [X] **_time**

</li>

---

<li>

Which of the following is the correct way to use the datamodel command to search fields in the Web data model within the Web dataset?

- [X] **| datamodel Web Web search | fields Web***
- [ ] | search datamodel Web Web | fields Web*
- [ ] | datamodel Web Web fields | search Web*
- [ ] datamodel=Web | search Web | fields Web*

</li>

---

<li>

Which of the following statements describe the command below? (Choose all that apply.)

`sourcetype=access_combined | transaction JSESSIONID`

- [ ] An additional field named maxspan is created.
- [X] **An additional field named duration is created.**
- [X] **An additional field named eventcount is created.**
- [X] **Events with the same JSESSIONID will be grouped together into a single event.**

</li>

---

<li>

Which of the following searches will return events containing a tag named Privileged?

- [ ] tag=Priv
- [X] **tag=Priv***
- [ ] tag=priv*
- [ ] tag=privileged

</li>

---

<li>

Given the macro definition below, what should be entered into the Name and Arguments fields to correctly configure the macro?
![](C:\Users\furqo\OneDrive\Desktop\splk-1002-prep-26.jpg)

- [ ] The macro name is sessiontracker and the arguments are action, JESSIONID.
- [X] **The macro name is sessiontracker(2) and the arguments are action, JESSIONID.**
- [ ] The macro name is sessiontracker and the arguments are $action$, $JESSIONID$.
- [ ] The macro name is sessiontracker(2) and the Arguments are $action$, $JESSIONID$.

</li>

---

<li>

What is required for a macro to accept three arguments?

- [X] **The macro's name ends with (3).**
- [ ] The macro's name starts with (3).
- [ ] The macro's argument count setting is 3 or more.
- [ ] Nothing, all macros can accept any number of arguments.

</li>

---

<li>

Which workflow action method can be used when the action type is set to link?

- [X] **GET**
- [ ] PUT
- [ ] Search
- [ ] UPDATE

</li>

---

<li>

Which of the following statements about tags is true? (Choose all that apply.)

- [ ] Tags are case-insensitive.
- [X] **Tags are based on field/value pairs.**
- [ ] Tags categorize events based on a search.
- [X] **Tags are designed to make data more understandable.**

</li>

---

<li>

Which of the following statements about macros is true? (Choose all that apply.)

- [ ] Arguments are defined at execution time.
- [X] **Arguments are defined when the macro is created.**
- [X] **Argument values are used to resolve the search string at execution time.**
- [ ] Argument values are used to resolve the search string when the macro is created.

</li>

---

<li>

Information needed to create a GET workflow action includes which of the following? (Choose all that apply.)

- [X] **A name for the workflow action.**
- [ ] A URI where the user will be directed at search time.
- [X] **A label that will appear in the Event Action menu at search time.**
- [ ] A name for the URI where the user will be directed at search time.

</li>

---

<li>

Which of the following can be used with the eval command `tostring` function? (Choose all that apply.)

- [X] **"hex"**
- [X] **"commas"**
- [ ] "decimal"
- [X] **"duration"**

</li>

---

<li>

Which of the following searches show a valid use of a macro? (Choose all that apply.)

- [X] **index=main source=mySource oldField=*** **|'makeMyField(oldField)'| table _time newField**
- [ ] index=main source=mySource oldField=* | stats if('makeMyField(oldField)') | table _time newField
- [X] **index=main source=mySource oldField=*** **| eval newField='makeMyField(oldField)'| table _time newField**
- [ ] index=main source=mySource oldField=* | "newField('makeMyField(oldField)')" | table _time newField

</li>

---

<li>

A user wants to convert numeric field values to strings and also to sort on those values. Which command should be used first, the eval or the sort?

- [X] **It doesn't matter whether eval or sort is used first.**
- [ ] Convert the numeric to a string with eval first, then sort.
- [ ] Use sort first, then convert the numeric to a string with eval.
- [ ] You cannot use the sort command and the eval command on the same field.

</li>

---

<li>

Which Knowledge Object does the Splunk Common Information Model (CIM) use to normalize data, in addition to field aliases, event types, and tags?

- [ ] Macros
- [X] **Lookups**
- [ ] Workflow actions
- [X] **Field extractions**

---

<li>

Which of the following statements describe data model acceleration? (Choose all that apply.)

- [ ] Root events cannot be accelerated.
- [X] **Accelerated data models cannot be edited.**
- [X] **Private data models cannot be accelerated.**
- [X] **You must have administrative permissions or the accelerate_datamodel capability to accelerate a data model.**

</li>

---

<li>

How does a user display a chart in stack mode?

- [ ] By using the stack command.
- [ ] By turning on the Use Trellis Layout option.
- [X] **By changing Stack Mode in the Format menu.**
- [ ] You cannot display a chart in stack mode, only a timechart.

</li>


---

<li>

If no value is specified with the fillnull command, what default value will be used?

- [X] **0**
- [ ] N/A
- [ ] ג€"
- [ ] NULL

</li>

---

<li>

What other syntax will produce exactly the same results as | chart count over vendor_action by user?

- [X] **| chart count by vendor_action, user**
- [ ] | chart count over vendor_action, user
- [ ] | chart count by vendor_action over user
- [ ] | chart count over user by vendor_action

</li>

---

<li>

What are the two parts of a root event dataset?

- [ ] Fields and variables.
- [ ] Fields and attributes.
- [X] **Constraints and fields.**
- [ ] Constraints and lookups.

</li>

---

<li>

When using timechart, how many fields can be listed after a by clause?

- [ ] 0, because timechart doesn't support using a by clause.
- [X] **1, because _time is already implied as the x-axis.**
- [ ] 2, because one field would represent the x-axis and the other would represent the y-axis.
- [ ] There is no limit specific to timechart.

</li>

---

<li>

A field alias has been created based on an original field. A search without any transforming commands is then executed in Smart Mode. Which field name appears in the results?

- [ ] Both will appear in the All Fields list, but only if the alias is specified in the search.
- [X] **Both will appear in the Interesting Fields list, but only if they appear in at least 20 percent of events.**
- [ ] The original field only appears in All Fields list and the alias only appears in the Interesting Fields list.
- [ ] The alias only appears in the All Fields list and the original field only appears in the Interesting Fields list.

</li>

---

<li>

Which of the following statements describes macros?

- [ ] A macro is a reusable search string that must contain the full search.
- [ ] A macro is a reusable search string that must have a fixed time range.
- [X] **A macro is a reusable search string that may have a flexible time range.**
- [ ] A macro is a reusable search string that must contain only a portion of the search.

</li>

---

<li>

In what order are the following knowledge objects/configurations applied?

- [ ] Field Aliases, Field Extractions, Lookups
- [X] **Field Extractions, Field Aliases, Lookups**
- [ ] Field Extractions, Lookups, Field Aliases
- [ ] Lookups, Field Aliases, Field Extractions

</li>

---

<li>

In which of the following scenarios is an event type more effective than a saved search?

- [ ] When a search should always include the same time range.
- [ ] When a search needs to be added to other users' dashboards.
- [X] **When the search string needs to be used in future searches.**
- [ ] When formatting needs to be included with the search string.

</li>

---

<li>

When using the transaction command, what does the argument maxspan do?

- [ ] Sets the maximum total time between events in a transaction.
- [ ] Sets the maximum length of all the events within a transaction.
- [X] **Sets the maximum total time between the earliest and latest events in a transaction.**
- [ ] Sets the maximum length that any single event can reach to be included in the transaction.

</li>

---

<li>

When creating a Search workflow action, which field is required?

- [X] **Search string**
- [ ] Data model name
- [ ] Permission setting
- [ ] An eval statement

</li>

---

<li>

To identify all of the contributing events within a transaction that contain at least one REJECT event, which syntax is correct?

- [ ] index=main REJECT | transaction sessionid
- [X] **index=main | transaction sessionid | search REJECT**
- [ ] index=main | transaction sessionid | where transaction=reject
- [ ] index=main | transaction sessionid | where transaction="REJECT*"

</li>

---

<li>

After manually editing a regular expression (regex), which of the following statements is true?

- [ ] Changes made manually can be reverted in the Field Extractor (FX) UI.
- [X] **It is no longer possible to edit the field extraction in the Field Extractor (FX) UI.**
- [ ] It is not possible to manually edit a regular expression (regex) that was created using the Field Extractor (FX) UI.
- [ ] The Field Extractor (FX) UI keeps its own version of the field extraction in addition to the one that was manually edited.

</li>

---

<li>

Which of the following statements describes POST workflow actions?

- [ ] Configuration of a POST workflow action includes choosing a sourcetype.
- [ ] POST workflow actions can be configured to send email to the URI location.
- [ ] By default, POST workflow actions are shown in both the event and field menus.
- [X] **POST workflow actions can be configured to send POST arguments to the URI location.**

</li>

---

<li>

Which of the following statements is true, especially in large environments?

- [ ] Use the stats command when you need to group events by two or more fields.
- [X] **The stats command is faster and more efficient than the transaction command.**
- [ ] The transaction command is faster and more efficient than the stats command.
- [ ] Use the transaction command when you want to see the results of a calculation.

</li>

---

<li>

What does the following search do?

`index=corndog type= mysterymeat action=eaten | stats count as corndog_count by user`

- [ ] Creates a table of the total count of users and split by corndogs.
- [X] **Creates a table of the total count of mysterymeat corndogs split by user.**
- [ ] Creates a table with the count of all types of corndogs eaten split by user.
- [ ] Creates a table that groups the total number of users by vegetarian corndogs.

</li>

---

<li>

Which of the following statements about event types is true? (Choose all that apply.)

- [X] **Event types can be tagged.**
- [ ] Event types must include a time range.
- [X] **Event types categorize events based on a search.**
- [X] **Event types can be a useful method for capturing and sharing knowledge.**

</li>

---

<li>

The Field Extractor (FX) is used to extract a custom field. A report can be created using this custom field. The created report can then be shared with other people in the organization.

If another person in the organization runs the shared report and no results are returned, why might this be? (Choose all that apply.)

- [ ] Fast mode is enabled.
- [ ] The dashboard is private.
- [X] **The extraction is private.**
- [X] **The person in the organization running the report does not have access to the index.**

</li>

---

<li>

Which of the following statements describe the search string below?

`| datamodel Application_State All_Application_State search`

- [ ] Events will be returned from dataset named Application_State.
- [X] **Events will be returned from the data model named Application_State.**
- [ ] Events will be returned from the data model named All_Application_State.
- [ ] No events will be returned because the pipe should occur after the datamodel command.

</li>

---

<li>

What is the correct syntax to search for a tag associated with a value on a specific field?

- [ ] tag=<field>
- [ ] tag=<field>(<tagname>)
- [ ] tag=<field>::<tagname>
- [X] **tag::<field>=<tagname>**

</li>

---

<li>

In most large Splunk environments, what is the most efficient command that can be used to group events by fields?

- [ ] join
- [X] **stats**
- [ ] streamstats
- [ ] transaction

</li>

---

<li>

Which workflow uses field values to perform a secondary search?

- [ ] POST
- [ ] Action
- [X] **Search**
- [ ] Sub-search

</li>

---

<li>

Which of the following statements describes field aliases?

- [ ] Field alias names replace the original field name.
- [X] **Field aliases can be used in lookup file definitions.**
- [ ] Field aliases only normalize data across sources and sourcetypes.
- [ ] Field alias names are not case sensitive when used as part of a search.

</li>

---

<li>

Which statement is true?

- [ ] Pivot is used for creating datasets.
- [ ] Data models are randomly structured datasets.
- [X] **Pivot is used for creating reports and dashboards.**
- [ ] In most cases, each Splunk user will create their own data model.

</li>




</ol>