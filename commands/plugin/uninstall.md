# wp plugin uninstall

Uninstall a plugin.

### OPTIONS

&lt;plugin&gt;...
: One or more plugins to uninstall.

[\--deactivate]
: Deactivate the plugin before uninstalling. Default behavior is to warn and skip if the plugin is active.

[\--skip-delete]
: If set, the plugin files will not be deleted. Only the uninstall procedure
will be run.

### EXAMPLES

    $ wp plugin uninstall hello
    Uninstalled and deleted 'hello' plugin.
    Success: Installed 1 of 1 plugins.


