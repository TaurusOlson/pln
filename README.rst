PLN
===

pln is a Python library to apply successive operations on your data::


    data = Pipeline("pipeline")                               # "pipeline"
    result = data >> select_consonants >> set >> join_chars   
    print result.value                                        # "pln"



Usage
-----

::

    from pln import Pipeline

    p = Pipeline(data)
    p >> func1 >> func2


Installation
------------

::

    pip install pln

