# soda
ScenariO Driven Automation

soda is automation testing framework written in Python, it is driven by scenario which is composed of events triggering and handling.

With webpage as GUI for test cases design and execution, tester who is responsible for running testcase  just need to select customized events to setup scenario for testing.

Test developer who is responsible for implementing test codes should be aware of below concept or rules:

1. Test is driven by scenario, and scenario is composed of events triggering and handling
2. Event could be registered or deregistered dynamically
3. Meta event is basic element to compose application level event
4. Event could carry data to distinguish itself from other event of the same kind
5. Event is the only element that could change scenario
6. Data must be shipped in some event if it could impact on scenario
7. Test data is input for testing which is some kind of requested URL, etc.
8. We should not expect that test data will always be up to date
9. We should find a way to maintain test data more easily
