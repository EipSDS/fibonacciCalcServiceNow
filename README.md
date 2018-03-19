# fibonacciCalcServiceNow
ServiceNow REST Service and UI to retrieve the Fibonacci Sequence given a number.

Option 1:
Instructions,Testing, and Technical information are contained within the update set itself as a Knowledge article.
Upload update set sys_remote_update_set_96f736fadbf81300ce9059d0cf9619b7.xml to a ServiceNow Instance, Preview updates, Accept the two errors for missing Knowledge base value, and Click Commit.
Once the update set is commited, the UI can be used and Knowledge Article can be accessed within a ServiceNow instance. The Knowledge article number is KB0010004 - short description Fibonacci Calculator. Navigate to Fibonacci Calculator module https://myinstance.service-now.com/u_fibonacci_calulator.do?sys_id=-1&sysparm_stack=u_fibonacci_calulator_list.do within the Self Service application to test the UI and web service within ServiceNow.

Option 2:
Use any REST tool such as Postman or Google's  REST ARC and perform a simple GET request against https://dev24089.service-now.com/api/79385/v1/fibonacci?num=n providing 'n' as the parameter to invoke web service and view the results.

Also uploaded a .word file of the ServiceNow KB if working outside ServiceNow, although formatting is off coming from an HTML Knowledge article.


