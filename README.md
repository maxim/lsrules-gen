# Little Snitch rules generators

This repo auto-generates `.lsrules` for Little Snitch and publishes them as Github Gists daily. You can subscribe to these gist files in Little Snitch. Just add the raw gist urls listed below as subscriptions to your Little Snitch.

List of generated rule files

* [msteams.lsrules](https://gist.githubusercontent.com/maxim/2ae0a2b68bb6ae053ee0a72e57e4e34d/raw/8a11aadf5b2324a83ccda52b91e132d86c7a1f87/msteams.lsrules) — Microsoft Teams ruleset generated from [endpoint lists](https://endpoints.office.com/endpoints/worldwide?clientrequestid=d61270c3-85db-4d9c-876d-daa00ca97583&ServiceAreas=Skype) provided by Microsoft. Caveat: after I applied these rules, I still had to deal with a couple of additional Sharepoint endpoints, not sure why, but hopefully this eliminates most of the annoying popups without allowing all outgoing connections. Microsoft marks a bunch of endpoints as "optional" and provides a note explaining what they are. Little Snitch will ask you about allowing these routes, and show Microsoft's note to explain what it is.
