UPGRADE FROM 3.X to 4.0
=======================

### Own implementation of the Slugify was removed

* NativeSlugify class was removed
* Twig filter `sonata_slugify` was removed

Install `cocur/slugify` and enable `CocurSlugifyBundle` https://github.com/cocur/slugify#symfony2 for using `slugify` filter and service.

### Deprecations in forms

The translator in ``DateRangeType``, ``DateTimeRangeType``, ``EqualType`` has been deprecated. 
