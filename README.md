wp-cli-bh-vps
=============

Use this to alias WP-CLI to 'wp' on a Bluehost VPS hosting account. Since WP-CLI is already on Bluehost's servers by default, this basically just creates the alias in your .bashrc file, sources it and makes it usable with running ```wp```, e.g. ```wp option get siteurl``` or ```wp user list```. For more information about WP-CLI, you can check it out here: [http://wp-cli.org/](http://wp-cli.org/) and you can find a list of commands to use with it here: [http://wp-cli.org/commands/](http://wp-cli.org/commands/). Also, because WP-CLI works differently VPS (opposed to shared), the alias is a little different. It is also worth noting that ```--allow-root``` is required to run commands if you are logged in as root.
