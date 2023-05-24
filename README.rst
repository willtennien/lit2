
maplit2 a.k.a. lit2
===================

Successor to maplit
------

Maplit has stopped being updated, so this is the new home for maplit improvement.

Maplit
======

Container / collection literal macros for `HashMap <https://doc.rust-lang.org/beta/std/collections/struct.HashMap.html>`_, `HashSet <https://doc.rust-lang.org/beta/std/collections/struct.HashSet.html>`_, `BTreeMap <https://doc.rust-lang.org/beta/std/collections/struct.BTreeMap.html>`_, `BTreeSet <https://doc.rust-lang.org/beta/std/collections/struct.BTreeSet.html>`_.

You can use these for convenience. Using them has no other implications.

Please read the `API documentation here`__

__ https://docs.rs/lit2/

|build_status|_ |crates|_

.. _crates: https://crates.io/crates/lit2
.. |crates| image:: https://badgers.space/crates/version/lit2

FAQ
---

**Question:** Very large maps take a long time to compile?

**Answer:** Rustc is very slow to compile big expressions with many literals
(including integers and float literals). Work around this by either
using explicitly typed literals, or explicitly typed conversions.
See https://github.com/bluss/maplit/issues/14 for more information.


License
-------

Dual-licensed to be compatible with the Rust project.

Licensed under the Apache License, Version 2.0
http://www.apache.org/licenses/LICENSE-2.0 or the MIT license
http://opensource.org/licenses/MIT, at your
option. This file may not be copied, modified, or distributed
except according to those terms.
