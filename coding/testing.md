# Testing Standards

Durring review follow the standards that are first set in the repository. If there are conventions that exits already, those should be taken as the direction. If there are no written standards then follow this skill to determine what is or is not worth bringing up.


# All Project Scope

1. All code should be written with the mind set of K.I.S.S. (Keep it stupid simple)
2. Assume work will be tested by the human - do not ask for verification.
3. When writing unit tests perfer mocking or small fakes and creating fixures for shared tests.
4. ALWAYS consider things such as conftest.py for testing where you can share fixtures across the test suite.
5. Never add a argument or flag for a script simply for the purpose of testing.


# Business scope

Follow this set of rules for specifically business scoped work.

1. Consider the scope of work. If the work expands multiple scopes define them well and suggest creating multiple pull requests or merge requests for each
2. Is coverage sufficient?
3. Are all edge cases considered?
4. Is the acceptance criteria clear given the tests?


# Personal Scope

Follow this set of rules for specifically personal project scoped work

1. Keep testing lean, do not create large amounts of test or a test for every change.
2. Testing should be left to purely unit tests and manual testing using tools. Integration, end-to-end, contracts, smoke tests, ext. should be excluded.
3. keep unit tests fast and efficient - long running tests should be considered bad
