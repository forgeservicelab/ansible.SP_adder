## Requirements

The playbook expects the remote SP's metadata file in XML format at the playbook's root, with name `metadata.xml`

## Playbook run.

This should work in most cases:

```
$ ansible-playbook -i 'idp.forgeservicelab.fi,' -e metadata_file=/var/simplesamlphp/metadata/saml20-sp-remote.php add_sp.yml
```
