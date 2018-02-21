Chain of Responsbility Pattern
  3.1.1 A Conventional Chain
  3.2.2 A Coroutine-Based Chain
  
  a) Designed to decouple the sender of a request from the recipient that processes the request
  b) Instead of a function directly calling another, the first function sends a request to a chain of receivers. Each receiver has an option to handle the request and terminate the chain or pass on the request to next receiver in the chain.
  c) Last receiver has an option to discard the request or raise an exception.
  d) Applications: User Interface where some events come from user(e.g: mouse and key events) and some come from the system (e.g: timer events)
  e) Two approaches :
      (i) A Conventional Chain Approach
      (ii) A Co-routine Based Chain Approach
