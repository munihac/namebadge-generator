# Namebadges Generator for MuniHac 2019

0. Clone project, cd into project directory.
1. Download the list of attendees from [EventBrite](https://eventbrite.com/), put it into project directory as `attendees.csv`.
2. Execute `gen-namebadges`. On NixOS, simply run
   ```bash
   $ ./gen-namebadges
   ```
   which also downloads the necessary dependencies. On other operating systems, make sure that Python and LaTeX are installed, then run
   ```bash
   $ python3 gen-namebadges
   ```