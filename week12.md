# Week 12 Reflections
[Towards a Domain-Specific Language for Geospatial Data Visualization Maps with Big Data Sets](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7507178)

This week I looked at a paper on the creation of a new domain-specific language for geospatial data. One use case of
such a language mentioned in the paper would be making it easier to share climate change data. We have many
research initiatives collecting data from around the world, but without a unified way of storing and managing that
data, it can be difficult to combine and interact with arbitrary data in a concise way. This proposed domain-specific
language works to tell a system how it can read and interpret a moderately arbitrary dataset. I say moderately though
since it still may require some additional help in the form of an adapter when interfacing with a system such as the
necessary drivers and api information of a database connection or a file which uses a previously unseen storage
approach. Other than that though it seems like it could be quite helpful to make the sharing of data easier. If it were
to see more widespread adoption it would allow researchers to include or create a short DSL file to allow easier 
interfacing with their data. It also had an interesting approach for minor filtering or processing of data reminiscent
of a database query to allow for a DSL file to point to a specific part of a group's data instead of the entire dataset.
