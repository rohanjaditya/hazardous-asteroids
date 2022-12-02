# Detection of Potentially Hazardous Near-Earth Asteroids
The goal of this project is to classify near-Earth asteroids into one oftwo categories:
- Potentially hazardous
- Not potentially hazardous

I tried different feature extraction methods and different classifiers and examined the performance of different combination of classifier and feature selection. </br>

## Dataset Description
The dataset was obtained from the [Small-Body Database Query](https://ssd.jpl.nasa.gov/tools/sbdb_query.html) from the JetPropulsion Laboratory managed by the California Institute of Technology and funded by NASA. </br>

The asteroid orbit classes used for the query are:
- Atira: An asteroid orbit contained entirely within the orbit of the Earth (Interior Earth Object).
- Aten: Near-Earth asteroid orbits similar to that of 2062 Aten.
- Apollo: Near-Earth asteroid orbits which crosses the Earth’s orbit similar to that of 1862 Apollo.
- Amor: Near-Earth asteroid orbits similar to that of 1221 Amor. </br>

The types of objects used for the query were:
- Object Group: All objects
- Object Kind: Asteroids
- Numbered State: All objects
- Exclude Comet Fragments: Yes
- Include only objects with at least one known (or suspected) satellite: No </br>

The dataset contains information about near-Earth asteroids. It has a total of 42 features and 28198 data points. </br>
