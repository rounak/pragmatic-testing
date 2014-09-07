A Pragmatic Approach to Testing
===============

An ebook about pragmatic testing strategies. You can grab the [epub here](https://github.com/orta/pragmatic-testing/blob/master/pragmatic_testing.epub?raw=true) - it's usually up to date.

##### Prospective Pages

* What & Why of the book
* What is XCTest, how does it work?
* How can I be pragmatic with my testing?

* Types of Testing
  * Unit Testing
  * Behavior Testing
  * Integration Testing

* Useful terminology
  * Testing Terminology
    * DI
    * Stubs / Mocks
    * Fakes ( + protocols )

* Tooling for the types of testing
  * Unit Testing ( Specta / Kiwi )
  * Mocking / Stubbing ( OCMock / OCMockito )
    * Network Stubbing ( OHTTP / VCRURLConnection )

* Getting Setup
* Introducing tests into an existing application

* Techniques for keeping testing code sane
  * Nested Before / After usage
  * Creation of app-centric `it` blocks
  * Fixtures / Factories

* Techniques for getting around Async Testing
  * Networking in View Controllers ( Network Models )
  * Animations
  * Dispatch Asyncs ( ar_dispatch etc )
  * `will` / `XCTest 6`

* Techniques for testing different aspects of the app
  * Views ( Snapshots )
    * Scroll Views
  * User interactions
  * iPad / iPhone

* Core Data
  * Assert on accessing main context
  * Testing Migrations
  * Stubbed Core Data Contexts

* Making libraries to get annoying tests out of your app
* Using Xcode pragmatically
* Improving Xcode
* Expanding on Specta / Expecta
* Test Driven Development
* Swift
* Recommended
  * Books
  * Websites
  * Twitter Follows

* OSS Testing in iOS
  * RestKit + AFNetworking
  * Moya / Eidolon

##### Existing Pages

| Topics | Last Updated |
| -------|--------------|
|[Core-Data-Migrations](Core-Data-Migrations.md)|07 Sep|
|[Getting Setup](getting_setup.md)|06 Sep|
|[How Can_i_be_pragmatic](how_can_I_be_pragmatic.md)|06 Sep|
|[Recommended Websites](recommended_websites.md)|06 Sep|
|[What And_why](what_and_why.md)|06 Sep|
|[What Is_xctest](what_is_xctest.md)|06 Sep|

##### Generating the ebook

The latest epub copy can be generated by running `ruby generate.rb`
