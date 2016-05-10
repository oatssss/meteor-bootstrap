# Meteor Bootstrap
A starting point from which a meteor app may be developed.

### Instructions:
1. Clone repo (`git clone` into folder that will be one level up).
2. `sudo chown -R <user> meteor-bootstrap` to recursively change file owner.
3. `sudo mv meteor-bootstrap/ <appFolder>` to rename the app folder.
4. Change `"name": "<appName>"` in `package.json` to reflect the actual app's name.
5. `meteor npm install` to install dependencies.
6. Change all instances of `<appName>` in `upstart-init.conf` to reflect the actual app's name (description and cd).
7. Rename `upstart-init.conf` to a more sensible filename and move to `/etc/init/` (using Apache).
