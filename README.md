# icedcoffeesort
algorithm for sorting people holding iced coffees on a subway car

- quickly scan subway car for people holding iced coffees
- note median-milkyness
- perform secondary scan grouping coffees into `lighter` and `darker` than median-milkyness buckets
- apply mental quicksort separately to each bucket
- if there are black iced coffees, sort from icy/diluted to dark sludge and append to list
