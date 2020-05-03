# AttackVectors-Domain-List
A Pi-Hole friendly domain list based on this ublock filter: https://github.com/MassMove/AttackVectors/blob/master/LocalJournals/sites-ublock-origin-filter.md

Since Pi-Hole does not support Ublock filters, this domain list has been made to be used in Pi-Hole.

# Installation
The easiest way is to use the Pi-Hole web Ui through the settings option.
Alternately, edit /etc/pihole/adlists.list and add the filter list. Make sure to use the unprocessed link i.e. raw.githubusercontent.com
otherwise Pi-Hole will not be able to process the domain list.
