- [Sourced Data](#Sourced%20Data)
- [Privacy](#Privacy)
- [Management](#Management)
- [Types](#Types)
- [Formats](#Formats)
- [Bias](#Bias)
- [Ethics](#Ethics)
- [Metadata](#Metadata)

# Sourced Data

- First Party Data : Data originally collected by a group using their own resources.
- Second Party Data : Data collected by a group from its audience then sold.
- Third Party Data : Data collected from outside sources who did not collect it directly.

Always check for trustworthiness and accuracy by

- checking for reliability
- verifying the original source
- looking for a comprehensive source
- ensure it is current and relevant
- confirming that it can be cited and vetted

# Privacy

- obtain consent prior to obtaining data
- protect data via obfuscation and security
- be aware of regulations

# Management

Establish protocols for

- data retrieval
- data organization
- data use
- data integrity
- accountability
- storage and security
- data sharing

# Types

- numerical
- string
- boolean

**Quantitative** (numerical)

- Discrete
	- values
		- are finite
		- there are no measures available between points
		- usually represented as whole numbers
- Continuous
	- values
		- can be infinite
		- values usually grouped and represented within intervals
	- interval scale
		- ranked or ordered
		- distance between points is consistent
		- e.g. temperature
	- ratio scale
		- ranked or ordered
		- distance between points is consistent
		- contains a zero value from which all measurements begin
		- e.g. height

**Qualitative** (categorical)

- Nominal
	- not ranked or not ordered
- Ordinal
	- ranked or ordered
	- distance between points is not consistent
# Formats

## Wide

Each data subject exists in one row.
Columns hold the values of the various attributes of the data subject.

|Name|Colour|Size|
|--|--|--|
|Pusheen|gray|large|
|Hello Kitty|white|small|

## Long

Each data subjects exists in many rows.
Each row holds one time point per data subject.

|Name|Age|Size|
|--|--|--|
|Pusheen|1|small|
|Pusheen|2|med|
|Pusheen|3|large|
|Hello Kitty|1|small|
|Hello Kitty|2|small|
|Hello Kitty|3|small|

# Bias

## Sampling Bias

Obtaining a sample that is not representative of the whole population.

**Remediation**
- randomize sampling from the population
- make sure to include the whole population affected
## Observer Bias

Also known as experimenter bias or research bias. It is the tendency for different people to observe the same things differently.
## Interpretation Bias

Tendency to always interpret ambiguous situations in a positive or negative way.
## Confirmation Bias

Interpreting information in a manner that confirms pre existing beliefs.

# Ethics


- ownership
	- individuals own the data they provide and have primary control over its use
- transaction transparency
	- all data processing activities should be explained to and understood by the individual providing their data
- consent
	- individuals can know explicit details about why and how their data will be used prior to providing it
- currency
	- inform individuals of any financial transactions resulting from the use of their data
- privacy
	- preserving a data subject's information and activity for every data transaction
	- protection from unauthorized access to data
	- no inappropriate use of data
	- ability for individual to inspect, update, and correct their data
- openness
	- free access, usage, and sharing of data
	- available
	- redistribution
	- universal participation

# Metadata

- descriptive : used for subsequent identification
- structural : how is data organized , data collections it belongs to
- administrative : data source

Metadata repositories hold metadata and describe
- metadata state
- metadata location
- table structure
- data flow
- user access to the data
