# Firefox assistant scripts

For the deanishe FF Alfred Script.

This `scripts` directory needs to be symlinked to the Workflow Data directory in the workflow.

See https://github.com/deanishe/alfred-firefox/blob/master/doc/scripts.md

E.g. `ln -s /Users/mmuldoon/dotfiles/alfred-custom/firefox-assistant/scripts /Users/mmuldoon/Library/Application Support/Alfred/Workflow Data/net.deanishe.alfred.firefox-assistant`

One time I had to delete the existing scripts directory to get this to work right.

Also you need to update the Workflow environment variables to add something like:

"URL_OPT     Copy to Clipboard"

That will interpret the OPT key as a shortcut to run the Copy to Clipboard.sh script
