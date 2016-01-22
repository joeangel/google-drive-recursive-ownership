Google Drive Recursive Ownership Tool
==

Notice
--

Don't running script on OS X system, may occur error!

Setup
--

    git clone https://github.com/davidstrauss/google-drive-recursive-ownership
    pip install --upgrade google-api-python-client

Usage
--

    python transfer.py PATH-PREFIX NEW-OWNER-EMAIL SHOW-ALREADY-OWNER
    python transfer.py test-folder-or-file new-owner-email true

- PATH-PREFIX assumes use of "/" or "\" as appropriate for your operating system.
- PATH-PREFIX only support ascii, not support chinese. Bug the subfolder can has chinese char.
- SHOW-ALREADY-OWNER "true"|"false" (default true) to hide feedback for files already set correctly.

