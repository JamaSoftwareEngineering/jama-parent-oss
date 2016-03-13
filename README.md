# Public Parent Project (OSS)

The `jama-parent-oss` is a public parent project that is meant to prescribe a small number of best practices for (Maven)
builds.

It should not contain the world, since that would be useless for most projects. It should also not contain a lot of
dependency management, since that's more up to child projects (think composition).

It should also not contain anything proprietary to Jama, there is a jama-parent for that which has stuff like references
to Jama's internal Maven repository, and different copyright notices, and you won't find in the open source space.

Things to expect here:

 - Meta data
 - License information
 - Source encoding
 - Plugin management
 - Default compiler level
 - Configuration of meta data in manifests (JAR, WAR)
 - Determining build number (Git ref, etc.)
 - Sorting POM files
 
There's nothing earth-shattering in `jama-parent-oss`. We are merely open sourcing this to be able to open source other
project, that were traditionally dependent on a similar but internal POM file (`jama-parent`) that contains some
internal references.

## License

This project is licensed under [the Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0.txt).

## About Jama

Jama is software for better, faster requirements definition, management, verification and validation, from inception to
production. Our Vision is of Modern Product Delivery. Building new products shouldn’t be frustrating and wasteful. It
ought to be enlightening and profitable. We make possible the impossible products of the future. Find more information
on [our web site](http://www.jamasoftware.com/). Jama Software is a fast-growing company, and we are
[hiring](http://www.jamasoftware.com/company/careers/).
