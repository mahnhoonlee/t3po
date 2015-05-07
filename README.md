# t3po
TRU 3 Party Orchestrator (T3PO)

AngularJS has been used for 2-way data binding between Model and View. 
Simply speaking, an update in an input HTML element trigers the update in a related internal JavaScript variable, and
the related output HTML elements are updated. This 2-way data binding is supported using new ng-directives.

AngularJS has some advantages, but it also has negative voices. Here is the summary of disadvantages and negative voices.
- Slow initialization
- One directional two way data binding
- Poor modularization - mixed coding style
- No clear interaction between AngularJS and legacy JS
- No 3-way data binding
- Simply put, over complicated and poor performance

T3PO intends to provide a light way of 3-way data binding. Here are notable features in T3PO.
- Seperation of T3PO code from HTML
- Descriptive data binding
- No lagged initilialization
- Use of any event for triggering View-inputs
- 3-way data binding
- Simple interaction between T3PO and JS, eventually server-side code
- Easy use of JS variables and functions in T3PO
- Easy API
- Extendable

