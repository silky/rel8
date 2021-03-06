Welcome to Rel8!
================================

Welcome to Rel8! Rel8 is an API built on top of the
fantastic `Opaleye <https://hackage.haskell.org/package/opaleye>`_ library to
provide an easy and type-safe way to interact with relational databases.

The main objectives of Rel8 are:

* *Conciseness*: Users using Rel8 should not need to write boiler-plate code. By
  using expressive types, we can provide sufficient information for the compiler
  to infer code whenever possible.

* *Inferrable*: Despite using a lot of type level magic, it should never be a
  requirement that the user must provide a type signature to allow a program to
  compile.

* *Compatible*: Rel8 tries to use the existing Opaleye API as much as possible.

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   tutorial
   concepts
   differences


More Resources
==============

* The `Haskell API documentation <https://hackage.haskell.org/package/rel8>`_
  describes how individual functions are types are to be used.

* If you have a question about how to use Rel8, or have found a bug, please go
  ahead and open an issue on the `issue tracker
  <https://github.com/ocharles/rel8>`_. I am happy to take usage questions
  there.
