Adds VSCode Icons artwork to Paseo's existing Files explorer on desktop and web. Named folders have closed and opened icons, and file icons recognize special filenames, compound extensions, and research formats including LaTeX, BibTeX, and bibliography styles.

The native folder disclosure arrows and file interactions remain available. Icons are bundled locally; the plugin does not read file contents or fetch icons from a server.

Requires Paseo 0.11.0 or later on the daemon and client. This uses the desktop/web file tree's DOM structure because Paseo has no file icon theme API. Host upgrades do not automatically disable the plugin; changes to the native tree may require a plugin update. Native iOS and Android clients retain their original icons. Disable all loaded instances to restore the original artwork.
