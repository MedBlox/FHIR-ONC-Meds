# {{ page.title }}

<!-- source pages/\_include/{{page.md_filename}}.md  file  -->

**Validator Pack and Definitions:**

The following file contains all the value sets, profiles, extensions, list of pages and urls in the IG defined as part of this Implementation Guides.:

- [Validator Pack](validator.pack)

In addition there are format specific definitions files.
- [XML](definitions.xml.zip)
- [JSON](definitions.json.zip)
- [TTL](definitions.ttl.zip)

These files should be the first choice whenever generating any implementation artifacts since they contain all of the rules about what makes these US-Core and US Meds profiles valid. Implementers will still need to be familiar with the content of the specification and profiles that apply in order to make a conformant implementation.  See the overview on [validating FHIR profiles and resources]({{ site.data.fhir.path }}/validation.html) for more information about validating profiles and how to use these artifacts

**Schematrons** are also available and listed below:

- [MedicationDispense](medicationdispense.sch)
- [MedicationAdministration](medicationadministration.sch)

**Examples:** all the examples that are used in this Implementation Guide available for download:

- [XML](examples.xml.zip)
- [JSON](examples.json.zip)
- [TTl](examples.ttl.zip)
