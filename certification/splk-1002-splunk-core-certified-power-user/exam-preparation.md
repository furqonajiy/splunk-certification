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

- [A] **The macro's name ends with (3).**
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

- [ ] `index=main source=mySource oldField=* |'makeMyField(oldField)'| table _time newField`
- [ ] `index=main source=mySource oldField=* | stats if('makeMyField(oldField)') | table _time newField`
- [ ] `index=main source=mySource oldField=* | eval newField='makeMyField(oldField)'| table _time newField`
- [ ] `index=main source=mySource oldField=* | "'newField('makeMyField(oldField)')'" | table _time newField`

</li>

---

<li>

Which of the following searches show a valid use of a macro? (Choose all that apply.)

- [X] **index=main source=mySource oldField=* |'makeMyField(oldField)'| table _time newField**
- [ ] index=main source=mySource oldField=* | stats if('makeMyField(oldField)') | table _time newField
- [X] **index=main source=mySource oldField=* | eval newField='makeMyField(oldField)'| table _time newField**
- [ ] index=main source=mySource oldField=* | "newField('makeMyField(oldField)')" | table _time newField

</li>

---

<li>

A user wants to convert numeric field values to strings and also to sort on those values. Which command should be used first, the eval or the sort?

- [ ] It doesn't matter whether eval or sort is used first.
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




</ol>