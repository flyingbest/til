# MVC (Model-View-Controller) pattern

Model–view–controller (MVC) is a software design pattern for implementing user interfaces on computers. It divides a given application into three interconnected parts in order to separate internal representations of information from the ways that information is presented to and accepted from the user.

### Components

The *model* is the central component of the pattern. It expresses the application's behavior in terms of the problem domain, independent of the user interface. It directly manages the data, logic and rules of the application.  

A *view* can be any output representation of information, such as a chart or a diagram. Multiple views of the same information are possible, such as a bar chart for management and a tabular view for accountants.  

The third part, the *controller*, accepts input and converts it to commands for the model or view.

### Interactions

In addition to dividing the application into three kinds of components, the model–view–controller design defines the interactions between them.  
 - A *model* stores data that is retrieved according to commands from the controller and displayed in the view.
 - A *view* generates new output to the user based on changes in the model.
 - A *controller* can send commands to the model to update the model's state (e.g., editing a document). It can also send commands to its associated view to change the view's presentation of the model (e.g., scrolling through a document).

### MVC pattern in every Framework.

**MUST know about the Rule.** You need to know exactly which function names and Rules are connected each other.
