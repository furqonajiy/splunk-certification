<span style="font-family: Verdana ; font-size: 1.2em;">

# [SPLK-1002 - Splunk Core Certified Power User](https://www.splunk.com/en_us/training/certification-track/splunk-core-certified-power-user.html)

At search time
This solution is not 100% correct

<ol>
<li>
Which one of the following statements about the search command is true?

- [ ] It does not allow the use of wildcards.
- [ ] It treats field values in a case-sensitive manner.
- [ ] It can only be used at the beginning of the search pipeline.
- [X] <span style="background-color: #3367D1">It behaves exactly like search strings before the first pipe.

</li>

---

<li>
Which of the following actions can the eval command perform?

- [ ] Remove fields from results.
- [X] <span style="background-color: #3367D1">Create or replace an existing field.
- [ ] Group transactions by one or more fields.
- [ ] Save SPL commands to be reused in other searches.

</li>

---

<li>
When can a pipe follow a macro?

- [X] <span style="background-color: #3367D1">A pipe may always follow a macro.
- [ ] The current user must own the macro.
- [ ] The macro must be defined in the current app.
- [ ] Only when sharing is set to global for the macro.

</li>

---

<li>
Data models are composed of one or more of which of the following datasets? (Choose all that apply.)

- [X] <span style="background-color: #3367D1">Events datasets
- [X] <span style="background-color: #3367D1">Search datasets
- [X] <span style="background-color: #3367D1">Transaction datasets
- [ ] Any child of event, transaction, and search datasets

</li>

---

<li>
When using the Field Extractor (FX), which of the following delimiters will work? (Choose all that apply.)

- [X] <span style="background-color: #3367D1">Tabs
- [X] <span style="background-color: #3367D1">Pipes
- [X] <span style="background-color: #3367D1">Colons
- [X] <span style="background-color: #3367D1">Spaces

</li>

---

<li>
Which group of users would most likely use pivots?

- [X] <span style="background-color: #3367D1">Users
- [ ] Architects
- [ ] Administrators
- [ ] Knowledge Managers

</li>

---

<li>

When multiple event types with different color values are assigned to the same event, what determines the color
displayed for the event?

- [ ] Rank
- [ ] Weight
- [X] <span style="background-color: #3367D1">Priority
- [ ] Precedence

</li>

---

<li>

Based on the macro definition shown below, what is the correct way to execute the macro in a search string?
![](C:\Users\furqo\OneDrive\Desktop\splk-1002-prep-8.jpg)

- [ ] "convert_sales(euro,ג‚¬,.79)"
- [X] <span style="background-color: #3367D1">'convert_sales(euro,ג‚¬,.79)'
- [ ] "convert_sales($euro$,$ג‚¬$,$.79$)"
- [ ] 'convert_sales($euro$,$ג‚¬$,$.79$)'

</li>

---

<li>

There are several ways to access the field extractor. Which option automatically identifies the data type, source type,
and sample event?

- [X] <span style="background-color: #3367D1">Event Actions > Extract Fields
- [ ] Fields sidebar > Extract New Fields
- [ ] Settings > Field Extractions > New Field Extraction
- [ ] Settings > Field Extractions > Open Field Extractor

</li>

---

<li>

Which of the following statements would help a user choose between the transaction and stats commands?

- [ ] stats can only group events using IP addresses.
- [ ] The transaction command is faster and more efficient.
- [X] <span style="background-color: #3367D1">There is a 1000 event limitation with the transaction command.
- [ ] Use stats when the events need to be viewed as a single correlated event.

</li>

---

<li>

By default, how is acceleration configured in the Splunk Common Information Model (CIM) add-on?

- [X] <span style="background-color: #3367D1">Turned off.
- [ ] Turned on.
- [ ] Determined automatically based on the sourcetype.
- [ ] Determined automatically based on the data source.

</li>

---

<li>

Which of the following statements describe the Common Information Model (CIM)? (Choose all that apply.)

- [X] <span style="background-color: #3367D1">CIM is a methodology for normalizing data.
- [X] <span style="background-color: #3367D1">CIM can correlate data from different sources.
- [X] <span style="background-color: #3367D1">The Knowledge Manager uses the CIM to create knowledge objects.
- [X] <span style="background-color: #3367D1">CIM is an app that can coexist with other apps on a single Splunk deployment.

</li>

---

<li>

Which of the following knowledge objects represents the output of an eval expression?

- [ ] Eval fields
- [X] <span style="background-color: #3367D1">Calculated fields
- [ ] Field extractions
- [ ] Calculated lookups

</li>

---

<li>

What do events in a transaction have in common?

- [ ] All events in a transaction must have the same timestamp.
- [ ] All events in a transaction must have the same sourcetype.
- [ ] All events in a transaction must have the exact same set of fields.
- [X] All events in a transaction must be related by one or more fields.

</li>

---

<li>

Which delimiters can the Field Extractor (FX) detect? (Choose all that apply.)

- [X] <span style="background-color: #3367D1">Tabs
- [X] <span style="background-color: #3367D1">Pipes
- [X] <span style="background-color: #3367D1">Spaces
- [X] <span style="background-color: #3367D1">Commas

</li>

---

<li>

A data model consists of which three types of datasets?

- [ ] Constraint, field, value.
- [X] <span style="background-color: #3367D1">Events, searches, transactions.
- [ ] Field extraction, regex, delimited.
- [ ] Transaction, session ID, metadata.

</li>

---

<li>

Where are the results of eval commands stored?

- [X] <span style="background-color: #3367D1">In a field.
- [ ] In an index.
- [ ] In a KV Store.
- [ ] In a database.

</li>

---

<li>

Which of the following statements describe calculated fields? (Choose all that apply.)

- [X] <span style="background-color: #3367D1">Calculated fields can be used in the search bar.
- [x] <span style="background-color: #3367D1">Calculated fields can be based on an extracted field.
- [ ] Calculated fields can only be applied to host and sourcetype.
- [x] <span style="background-color: #3367D1">Calculated fields are shortcuts for performing calculations using the eval command.

</li>

---

<li>

Calculated fields can be based on which of the following?

- [ ] Tags
- [X] <span style="background-color: #3367D1">Extracted fields
- [ ] Output fields for a lookup
- [ ] Fields generated from a search string

</li>

---

<li>

When should transaction be used?

- [ ] Only in a large distributed Splunk environment.
- [ ] When calculating results from one or more fields.
- [X] <span style="background-color: #3367D1">When event grouping is based on start/end values.
- [ ] When grouping events results in over 1000 events in each group.

</li>

---

<li>

When performing a regular expression (regex) field extraction using the Field Extractor (FX), what happens when
the require option is used?

- [ ] The regex can no longer be edited.
- [ ] The field being extracted will be required for all future events.
- [ ] The events without the required field will not display in searches.
- [X] <span style="background-color: #3367D1">Only events with the required string will be included in the extraction.

</li>

---

<li>

When using | timechart by host, which field is represented on the x-axis?

- [ ] date
- [ ] host
- [ ] time
- [X] <span style="background-color: #3367D1">_time

</li>

---

<li>

Which of the following is the correct way to use the datamodel command to search fields in the Web data model within the
Web dataset?

- [X] <span style="background-color: #3367D1">`| datamodel Web Web search | fields Web*`
- [ ] `| search datamodel Web Web | fields Web*`
- [ ] `| datamodel Web Web fields | search Web*`
- [ ] `datamodel=Web | search Web | fields Web*`

</li>

---

<li>

Which of the following statements describe the command below? (Choose all that apply.) sourcetype=access_combined |
transaction JSESSIONID

- [ ] An additional field named maxspan is created.
- [X] An additional field named duration is created.
- [X] An additional field named eventcount is created.
- [X] Events with the same JSESSIONID will be grouped together into a single event.

</li>



</ol>