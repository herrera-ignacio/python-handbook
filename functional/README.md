# Functional Programming

#### `map(function ,iterable, ...)`

Check [the example](./map.py)

Return an iterator that applies _function_ to every item of _iterable_, yielding the results.  if additional _iterable_ arguments are passed, _function_ must take that many arguments and is applied to the items from all iterables _in parallel_. With multiple iterables, the iterator stops when the shortest iterable is exausted.

For cases where the function inputs are already arranged into argument tuples, see `itertools.starmap()`.
