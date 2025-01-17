
**Example Usage Scenarios:**

The following are example usage scenarios for this profile:

-   Query for survey SDOH screening results for a patient.
-  [Record or update] SDOH screening results results belonging to a Patient

### Mandatory and Must Support Data Elements

*In addition to* the mandatory and must support data elements in the US Core Observation Survey Profile, the following data-elements must always be present ([Mandatory] definition]) or must be supported if the data is present in the sending system ([Must Support] definition). They are presented below in a simple human-readable explanation.  Profile specific guidance and examples are provided as well.  The [Formal Views] below provides the  formal summary, definitions, and terminology requirements. Note that the *Must Support* view aggregates all the must support elements between this profile and its parent profiles.

**Each Observation must support:**

1. a category code of "sdoh"
2. an SDOH [LOINC] code, if available
4. references to other US Core SDOH assessments

**Profile specific implementation guidance:**

- This profile defines a Valueset based on a *starter set* of example survey LOINC codes made up of commonly asked social questions as identified by [FindHelp.org] and the PRAPARE, Hunger Vital Sign, AHC-HRSN screening tools referenced in USCDI v2+. It is not intended to be complete and implementers are expected include other LOINC or other codes to meet their business needs.
- See the [US Core Observation Survey Profile] page for how to represent individual responses, panels of multi-question surveys, and multi-select responses to “check all that apply” questions, and other implementation guidance.
- See the [SDOH] guidance page for how this profile *along with other Observation Profiles or alternatively QuestionnaireResponse* to is used represent SDOH assessments.

{% include link-list.md %}
