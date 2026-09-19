Answer Key — Stacks & Queues Applied Quiz
==========================================

Q1: C
Q2: A
Q3: C
Q4: A
Q5: B
Q6: C
Q7: B
Q8: B
Q9: B
Q10: B

------------------------------------------
Rationale (for grading)

Q1 (C) Queue = FIFO. Serve order equals arrival order: Ana, Bo, Cy, Dee, Eli.
       The 3rd to leave is Cy.

Q2 (A) Stack = FILO. Placed bottom->top: Soup, Beans, Corn, Peas, so the pile
       top->bottom is Peas, Corn, Beans, Soup. Removing two takes Peas then
       Corn, leaving Soup and Beans.

Q3 (C) push A,B -> [A,B]; pop removes B -> [A]; push C,D -> [A,C,D];
       pop removes D -> [A,C]. Top = C.

Q4 (A) Queue is FIFO: first out = 1 (the first one added). Stack is FILO:
       first out = 5 (the last one added). So "1 and 5".

Q5 (B) The browser Back button is a stack of visited pages:
       [Home, News, Article, Photo]. Back pops Photo (viewing Article);
       Back again pops Article (viewing News).

Q6 (C) Undo is a stack. After typing: [the, cat, sat]. First Undo pops sat ->
       [the, cat]. Typing ran pushes it -> [the, cat, ran]. The second Undo
       pops the current top, which is ran.

Q7 (B) The call stack holds the most recent call on top. a() called b() called
       c(); paused in c(), so top->bottom is c, b, a.

Q8 (B) The call stack unwinds FILO: the top frame (c) returns first, then b,
       then a.

Q9 (B) A fair print server is a QUEUE (FIFO), not a stack. The first job sent
       (Report) prints first. The coworker wrongly called it a stack.

Q10 (B) A stack reverses a sequence: push items in one order, and popping
       returns them in the reverse of that order. A queue preserves order.
