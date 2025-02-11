Breniac login infrastructure
----------------------------

Direct login using SSH is possible to all login infrastructure.

.. note::

   Only users involced in an active Tier-1 project have access to the
   infrastructure.

Two types of login nodes are available:

- a classic login node, i.e., SSH access.

  - ``login1-tier1.hpc.kuleuven.be``
  - ``login2-tier1.hpc.kuleuven.be``

- a login node that provides a desktop environment that can be used for,
  e.g., visualization, see the :ref:`NX clients section <NX start guide>`:

  - ``nx-tier1.hpc.kuleuven.be``

    .. warning::

       This node *should not* be accessed using terminal SSH, it serves only
       as a gateway to the actual login nodes your NX sessions will be running
       on.

    The NX login node will start a session on a login node that has a GPU, i.e.,
    ``login2-tier1.hpc.kuleuven.be``.
