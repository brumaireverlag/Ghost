## brumaire ghost fork

this is a fork of the ghost repo with modifications

branches:
- main: the main branch
- compat: the checkout release of our ghost installations at staging and production
- modifications: the modifications based of the current compat branch

modifications:
- ghost portal checkout links: ghost portal checkout links are read from window and augmented by our ghost template if set.
- ghost notification bar: notification sent by custom event are displayed as portal notifications
