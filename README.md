# NIST SP 800-171 Revision 1 in OpenControl Standard format

This repository encodes the [NIST Special Publication 800-171 Revision 1](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-171r1.pdf), Protecting Controlled Unclassified
Information in Nonfederal Systems and Organizations, in the [OpenControl Standards](https://github.com/opencontrol/schemas) format, for use with [Compliance Masonry](https://github.com/opencontrol/compliance-masonry)

To import these data into a OpenControl project add the follow code to your opencontrol.yaml file.
```yaml
dependencies:
  standards:
    - url: https://github.com/GovReady/NIST-800-171-Standards
      revision: master
```

For more information on the opencontrol.yaml visit the [Compliance Masonry CLI](https://github.com/opencontrol/compliance-masonry#creating-an-opencontrol-project).