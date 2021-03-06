## Spy 0.4.0 (May 8, 2013) ##

*   Allow `Spy#have_received_with` to accept a block
*   Add automatic test integration for TestUnit, Minitest and Rspec
*   Fix a few rubinius tests

## Spy 0.3.1 (March 13, 2013) ##

*   Fix Agency recruiting of mock

## Spy 0.3.0 (March 12, 2013) ##

*   Added Mock

    Example:

        book = Spy.mock(Book, author: "John Steinbeck")

*   Deprecate Double and use Mock instead
*   Fix Exceptions so they can have custom messages

## Spy 0.2.5 (March 9, 2013) ##

*   Add custom exception classes

## Spy 0.2.4 (February 28, 2013) ##

*   Fix airty checking of Spy::Subroutine#and_return

## Spy 0.2.3 (February 28, 2013) ##

*   Fix marshal dumping
*   Add Docs
*   Make error messages clearer

## Spy 0.2.2 (February 26, 2013) ##

*   Make compatible with ruby 2.0.0

## Spy 0.2.1 (February 25, 2013) ##

* fix missing CallLog

## Spy 0.2.0 (February 22, 2013) ##

*   Add CallLog
*   Fix constant stubbing
*   Ensure spy is logging all calls even if an error is raised
*   add Spy::Subroutine#called_with

## Spy 0.1.0 (February 20, 2013) ##

*   add Spy#and_raise
*   add Spy#and_throw
*   add Spy#and_yield
*   add Constant stubbing
*   fix private method lookups

## Spy 0.0.1 (February 5, 2013) ##

*   Stub objects

    Example:

        Spy.on(book, :title).and_return("East of Eden")

*   Create Doubles

    Example:

        Spy.double("Double Name", stub: :method)
