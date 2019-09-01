# Namebadges Generator for MuniHac 2019

1. Download the list of attendees from [EventBrite](https://eventbrite.com/).
2. Execute `gen-namebadges`. On NixOS, simply run
   ```bash
   $ ./gen-namebadges
   ```
   which also downloads the necessary dependencies. On other operating systems, make sure that Python and LaTeX are installed, then run
   ```bash
   $ python3 gen-namebadges
   ```