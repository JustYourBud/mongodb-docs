All |single-modification-operation-names| operations for a sharded
collection that specify the |single-modification-operation-option|
option must include the :term:`shard key` *or* the ``_id`` field in
the query specification.

|single-modification-operation-names| operations specifying
|single-modification-operation-option| in a sharded collection which do
not contain either the :term:`shard key` or the ``_id`` field return an
error.

