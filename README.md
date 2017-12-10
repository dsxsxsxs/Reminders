# Reminders iOS

An iOS application written in Swift to demonstrate how to implement a Clean Architecture in iOS.

## Requirements

* macOS 10.13 or higher
* Xcode 9.2 or higher

## Installation

To compile/run the iOS application:
* open the Xcode Project "Reminders.xcodeproj"
* select the "Reminders" iOS scheme
* Run by pressing "Play" or by pressing [Cmd + R]

## Tests

We use [XCTest](https://developer.apple.com/documentation/xctest) for the Unit and UI tests.

To run the tests for the iOS application:
* open the Xcode Project "Reminders.xcodeproj"
* select the "Reminders" iOS scheme
* Run by pressing "Product" > "Test" or by pressing [Cmd + U]

## Possible Improvements

* Use a Mocking framework to remove Mocks and Spies in tests
* Use a Dependency Injection framework to improve ControllerFactory
* Test AppRouter routing by abstracting UIKit navigation
* Render AppRouter routing explicit
* Refactor RemindersEndToEndTest
* Refactor RemindersPresenterTest
* Refactor AddReminderPresenterTest
