# NIST SP 800-171 Revision 1 in OpenControl Standard format

This repository encodes the [NIST Special Publication 800-171 Revision 1](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-171r1.pdf): Protecting Controlled Unclassified
Information in Nonfederal Systems and Organizations, with errata through Feb. 20, 2018, in the [OpenControl Standards](https://github.com/opencontrol/schemas) format, for use with [Compliance Masonry](https://github.com/opencontrol/compliance-masonry).

[NIST-SP-800-171r1.yaml](NIST-SP-800-171r1.yaml) is an OpenControl standards file containing a mapping from NIST SP 800-171 control numbers to their family and text (description), as well as a name for each control. Unlike NIST SP 800-53, NIST SP 800-171 does not name its controls. The `name` field in `NIST-SP-800-171r1.yaml` was filled in with names created by GovReady. To indicate these names are not official, we have set them off in brackets. Footnotes in the NIST publication are inserted into the control description and are set off as `[Footnote: ...]`.

[NIST-SP-800-171r1_all.yaml](NIST-SP-800-171r1_all.yaml) is an OpenControl certifications file that selects all NIST SP 800-171 controls.

To import these data into a OpenControl project add the follow code to your opencontrol.yaml file.

```yaml
dependencies:
  standards:
    - url: https://github.com/GovReady/NIST-800-171-Standards
      revision: master
```


For more information on the opencontrol.yaml visit the [Compliance Masonry CLI](https://github.com/opencontrol/compliance-masonry#creating-an-opencontrol-project).

The files in this repository were created by hand from the NIST publication.
