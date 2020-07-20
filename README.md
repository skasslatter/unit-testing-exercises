# Typescript

This block of your bootcamp will dive into the testing of your angular application with Karma.
In this block you will learn what Karma is, what to test and what not to test and ofcourse how to create the actual test.

Let's dive in!

## Contents

1. [An introduction to testing](testing-CH1-testing-introduction.md)
2. [Understanding the basic test file](testing-CH2-understanding-test-file.md)
3. [Mocking](testing-CH3-mocking.md)
4. [HTTP mocking](testing-CH4-http-mocking.md)
5. [Async Testing](testing-CH5-async.md)

## Assignments

#### App component:
- Create a `it` to check if the app has the title `testing-assignment`.
- Create a `it` to check if the title get rendered and contains `testing-assignment app is running!`.

#### City component
- Create the basic `.spec` file for the component.
- Provide the right declaration in the `configureTestingModule`.
- Create a `it` to check if the component gets created.
- Create a `it` to check if the city variable gets the right value from `ngOnInit`.
- Create a `it` where you set the city and check if it equal to your set name.
- Create a `it` to check if the city name get rendered on the page.

#### Person model:
- Study `person.model.ts` and create a test suite for it.
- Create a `beforeEach()` that creates a new `Person`.
- Create a `it` that check the output of the `sayHello()` function.
- Create a `AfterEach()` that makes person `null`.

#### Car model
- Study `car.model.ts` and create a test suite for it.
- Create a `beforeEach()` that creates a new `Car`.
- Create a 2 `it` that check the output of the both functions function.
- Create a `AfterEach()` that makes car `null`.

#### Car component:
- Study `car.component.ts` and create a test suite for it.
- Test if `this.cars[]` is constructed after initialisation. Expect the length of the array to be `2`.
- Test whether the `@Output()` event is called when clicking on a car.

#### Spy component
- Study `spy.component.ts` and create a test suite for it.
- Create a mock array for the `cities[]`.
- Create a `it` to check the array length.
- Create a `it` that adds a city and checks the length of the array.
- Create a `it` that deletes a city and checks the length of the array.
- Create a `it` that check if the right method is called when you click the delete button. 
  Use a spy to check if the method has been called.

#### Car service:
- Study `car.service.ts` and create a test to test all its methods

#### Post service:
- Study `post.service.ts` and mock the http GET request.
