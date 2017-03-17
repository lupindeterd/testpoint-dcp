# DCP-client-bash

Bunch of scripts to query https://dcp.testpoint.io/ or any other instance of DCP service.

Usage:
1. Get your JWT token (how to do it is described on https://idp.testpoint.io)
2. Export it as CB_AUTH variable:
`export CB_AUTH="JWT eyXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"`
3. run `./do_demo_auth.sh.sample` script to ensure it works.

You can copy and rename any .sample script to .sh, *.sh files are gitignored by default, and add your custom code there.

First you might want to start with demo_auth, then `get_*`, then `put_*`, then `delete_*` and so on. You might want to update participant ID and service ID in scripts. At least - update participant ID to one you have claimed from the idp.testpoint.io.
