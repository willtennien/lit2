
maplit2
======

Successor to maplit
-------------------

Maplit has stopped being updated, so this is the new home for maplit improvements.

Maplit
======

Container / collection literal macros for `HashMap <https://doc.rust-lang.org/beta/std/collections/struct.HashMap.html>`_, `HashSet <https://doc.rust-lang.org/beta/std/collections/struct.HashSet.html>`_, `BTreeMap <https://doc.rust-lang.org/beta/std/collections/struct.BTreeMap.html>`_, `BTreeSet <https://doc.rust-lang.org/beta/std/collections/struct.BTreeSet.html>`_.

You can use these for convenience. Using them has no other implications.

Please read the `API documentation here`__

__ https://docs.rs/maplit/

|build_status|_ |crates|_

.. |build_status| image:: https://travis-ci.org/bluss/maplit.svg?branch=master
.. _build_status: https://travis-ci.org/bluss/maplit2

.. |crates| image:: http://meritbadge.herokuapp.com/maplit2
.. _crates: https://crates.io/crates/maplit2


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
