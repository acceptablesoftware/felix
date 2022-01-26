Felix
=====

A small Docker container for deploying Python apps in production.

There is a second repo,
https://github.com/acceptablesoftware/felix-builder, which serves
as a counterpart to this one. ``felix-builder`` allows installation
of additional ``apk`` packages, while ``felix`` does not. This makes
``felix`` safe for deployment, while ``felix-builder`` is useful for
building apps which end up deployed in a ``felix`` image.
