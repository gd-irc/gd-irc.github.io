## Renaming "Realname" to "Userdata"

The IRC specification currently calls for a "realname" field. In addition to serving identification purposes, this field is often auto-filled by IRC clients with the IRC client name, as well as being used by the [gender spec](./gender-spec.md) to carry genders.

This specification proposes calling it "userdata", at least in user interface. Projects may also want to call it `userdata` or `irc_userdata` in code.
