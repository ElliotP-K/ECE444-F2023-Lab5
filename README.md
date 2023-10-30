# ECE444-F2023-Lab5

Unit test:

https://github.com/ECE444-2023Fall/project-1-web-application-design-group3-bugbusters/blob/develop/flask-server/test/unit/test_event_service.py#L48-L66


Test-Driven Development Pros and Cons:

Pros:

TDD leads to overall better quality of code. By writing tests as specifications before coding,  specific behaviour of the system will be enforced. Additionally, TDD can help identify bugs in code during the development phase that couldve been missed and shipped off to the user without TDD. 
 
By breaking down code features into different tests, the system becomes more modular and is less suseptable to breaking or regressing when refactoring or changing features. It gives the developers a clear idea of what their changes effect within the system and makes identifying these issues easier as well as making the code base cleaner and healthier.

Cons:

TDD does have some issues associated with it. If system behaviour is subject to change or unclear, writing tests to enforce that behaviour would be increasing technical debt for if/when the desired behaviour changes. Additionally, writing tests for every feature increases the time it takes to develop the feature, this could hinder efficiency.

In conclusion, when considering using TDD there a certain factors that must be accounted for such as specifications of the project as well as the development style of the team implementing it. TDD offers many benefits in terms of bug detection, code clarity, and confidence in system behaviours, however, it requires meticulous design of tests and features.