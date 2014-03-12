firebase-import
===============

Import files are a new invention, so libraries like `firebase` do not yet provide them.

`firebase-import` is an intermediary that provides an import file for the `firebase` component. `firebase-import` depends on `firebase`.

Components that want to use `firebase` should depend on `firebase-import` to be safe from library duplication.