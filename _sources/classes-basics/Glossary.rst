..  Copyright (C)  Brad Miller, David Ranum, Jeffrey Elkner, Peter Wentworth, Allen B. Downey, Chris
    Meyers, and Dario Mitchell.  Permission is granted to copy, distribute
    and/or modify this document under the terms of the GNU Free Documentation
    License, Version 1.3 or any later version published by the Free Software
    Foundation; with Invariant Sections being Forward, Prefaces, and
    Contributor List, no Front-Cover Texts, and no Back-Cover Texts.  A copy of
    the license is included in the section entitled "GNU Free Documentation
    License".

Glossary
--------

.. glossary::

    k
    class attribute
        Data that the class keeps track of.  All objects of the class have access to this data.

    object attribute
        Data that an object keeps track of.

    class
        A class can be thought of as a
        template for the objects that are instances of it.
        It defines a data type.
        A class can be provided by the Python system or be user-defined.

    constructor
        Every class has a "factory", called by the same name as the class, for
        creating new instances.  If the class has an *initializer method*, this method
        is used to set the attributes (i.e. the state) of the new object.

    initializer method
        A special method in Python (called ``__init__``)
        that is invoked automatically to set a newly-created object's
        attributes to their initial (factory-default) state.

    instance
        An object whose type is of some class.  Instance and object are used
        interchangeably.

    instantiate
        To create an instance of a class, and to run its initializer.

    object method
        A function that is defined inside a class definition and is invoked on
        instances of that class.

    object
        A compound form of data that is often used to model a thing or concept in
        the real world.  It bundles together the data and the operations that
        are relevant for that thing or concept. It has the type of its defining class.
        Instance and object are used interchangeably.

    object-oriented programming
        A powerful style of programming in which data and the operations
        that manipulate it are organized into classes and methods.

    object-oriented language
        A language that provides features, such as user-defined classes and
        inheritance, that facilitate object-oriented programming.
