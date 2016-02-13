# Make a To-Do app

### Step 1. Install bower components
Navigate to your folder in command prompt using `cd c:/wherever/it/is/located`.

Then, run `bower install`.  You should see a bower_components file in your project.

### Step 2. Setup your controller
Everything is already linked to the html and the Angular module is already set up, so all you have to do is go into `js/app.js` 
and setup a new controller, call it "MainController".

### Step 3. Build your HTML
The first thing you need to do in the HTML is hookup your module and controller.  Then, set your page up to have these elements:

- A div that you'll add an ng-repeat to later, so you can see all the todos that are added
- Some input boxes, e.g. "name of task", "date due"
- An add button with an ng-click to execute your function.

### Step 4. Make it all work
Now you'll want to go into your controller and create a variable for `$scope.tasks`(this should be an empty array so we can push 
objects to it later).  Next, you need to add a function called `$scope.addTask()`.  This function will push to the array and object filled
with whatever is typed into the input (using ng-model), e.g. `{task: $scope.myTaskName, date: $scope.myTaskDate}`.  Now, add an ng-click
to your button to execute the add function.  And it's time to test it out.  If it isn't working at this point, just let me know and I'll
help you figure it out.

### Step 5. Expand functionality
Add whatever you want to make this a fully functioning, good looking application.  I'd suggest at least a remove function.  Then upload
to your github and sent me a link.

### Step 6. Wash, Rinse, Ng-Repeat
Delete the project from your desktop and do it again.
Repeat until you can do it without the instructions.
for(var i = 0; i >= noInstructions.length; i++){
    todoApp();
}

### Step 7. There is no step 7
Congratulations, you've mastered Angular syntax.

