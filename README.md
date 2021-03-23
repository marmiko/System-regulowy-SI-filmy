# movies-recommendation-system
This is a rules management system developed with JBoss Drools plugin for Java.  
* Maria Mikołajczak 141282
* Michał Mędzin 141279
## How to run the project in Eclipse
### Support for JavaFX is needed for the program to work. Eclipse is provides it with the e(fx)clipse plugin.
### Plugin installation:
1. Start Eclipse and select 'Help'> 'Eclipse Marketplace'.
2. Enter e(fx)clipse in the search field and confirm.
3. Select e(fx)clipse plugin and install it.
4. After installation is complete, Eclipse must be restarted.

### Additionally, the appropriate arguments for the Java virtual machine should be added:
1. Expand the project folder in Eclipse and right click on the src/main/Java/com.sample/Main.java class.
2. Select 'Run As'> 'Run Configurations ...' from the context menu.
3. Select 'Java Application' from the list and then select 'New launch configuration'.
4. On the 'Arguments' tab, in the' VM arguments' field, enter the following for Linux systems: '--module-path src / main / lib / linux / javafx-sdk-11.0.2 / lib --add-modules = javafx. controls, javafx.fxml 'and for Windows systems:' --module-path src \ main \ lib \ windows \ javafx-sdk-11.0.2 \ lib --add-modules = javafx.controls, javafx.fxml '
5. Confirm with the 'Apply' button.
