## Pluto - Python based plug-in automation framework.

This is a python wireframe implementation of self discovering test automation framework which can be used by any developers to adopt and implement their own automation framework.

The framework uses python __subclasses__ method to auto discover the available implementations. The base class for all top lavel framework modules are defined as Abstract base class(abc.ABCMeta).

The framework provides complete abstraction for the application layer from the underlaying multiple implementations.

Scenarios where this framework will come handly are when you have one software/test suite
 - which need to be executed on multiple OS
 - which need to be executed on multiple HW platform
 - which need to switch between different implementations from execution to execution.

## Documentation
To be added

## Requirements
Python 3.4 plus

