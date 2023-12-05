# Little Snitch rules generators

This repo auto-generates `.lsrules` for Little Snitch and publishes them as Github Gists daily. You can subscribe to these gist files in Little Snitch. Just add the raw gist urls listed below as subscriptions to your Little Snitch.

List of generated rule files

* [msteams.lsrules](https://gist.githubusercontent.com/maxim/2ae0a2b68bb6ae053ee0a72e57e4e34d/raw/msteams.lsrules) — Microsoft Teams classic ruleset generated from [endpoint lists](https://endpoints.office.com/endpoints/worldwide?clientrequestid=d61270c3-85db-4d9c-876d-daa00ca97583&ServiceAreas=Skype) provided by Microsoft. Caveat: after I applied these rules, I still had to deal with a couple of additional Sharepoint endpoints, not sure why, but hopefully this eliminates most of the annoying popups without allowing all outgoing connections. Microsoft marks a bunch of endpoints as "optional" and provides a note explaining what they are. Little Snitch will ask you about allowing these routes, and show Microsoft's note to explain what it is.

* [msteams-new.lsrules](https://gist.githubusercontent.com/maxim/885e395b7d6cd2991790c0f3167326ee/raw/msteams-new.lsrules) — Same as above, but with updated process path.

* [skype.lsrules](https://gist.githubusercontent.com/maxim/48753f090f99f21e6091a62e0b56311e/raw/skype.lsrules) — Skype ruleset generated from [Skype's FAQ page](https://support.skype.com/en/faq/FA148/which-ports-need-to-be-open-to-use-skype-on-desktop). Some popups might still occur.
