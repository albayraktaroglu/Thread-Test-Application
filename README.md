# Thread-Test-Application
Desktop Application to test multiple threads accessing same elements ( Java, Swing ) 

![](https://github.com/albayraktaroglu/Thread-Test-Application/blob/master/Question.JPG)


Requirements

- Create a Swing form in Eclipse ( includes 4 progress bars and their current percentages and sum of that percentages )
- Create a thread class that will accept as parameters:
  - Progress bar
  - Thread total label
  - Grand total label 
  - Interval in ms to be used in a thread safe manner GUI display 
- Create a critical section within a thread to update " grand total " label value. Critical section has sleep(50). The only access to grand total should be through text property of " grand total label " ( do not keep any additional variable to store it )
- When pressing 'start' button start 4 instances of a thread class with different intervals able to view their progress 
- Implement 'Pause' and 'Resume' buttons
- Use proper way to update Swing GUI components from within a thread
