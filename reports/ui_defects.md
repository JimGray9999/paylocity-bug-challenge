# UI Defects

1. "Dependants" is mispelled, should be "Dependents"

2. Selecting Edit Employee icon shows "Add Employee" header, 
    - "Edit Employee" or "Update Employee" may be more appropriate

![Mispelled](../screenshots/defect_1.png)

3. Allowed to enter a numerical value for a first and last name
    - Recommend adding a block to certain non-alpha values

4. The minimum and maximum number of dependents allowed (0 to 32) is not displayed in the UI when attempting a  
    value outside of this range. 
    - Can find this by checking the API response in DevTools or in Postman.

5. Able to add a user with a blank dependent field, it assumes 0.

6. No error message displayed when entering First OR Last Name as blank

7. Last Name and First Name headers are reversed
![Reversed Headers](../screenshots/defect_2.png)

8. When the application has timed out, no indication this has happened
    - only when you try to attempt any action, and there's no response

9.  At a breakpoint size of 972px wide, the display shows a line thru Net Pay
![Line Display](../screenshots/line_display.png)

10. Can reach the dashboard page without authentication, recommended design would be to re-direct to the login 
    page if not authenticated: 
    -  https://wmxrwq14uc.execute-api.us-east-1.amazonaws.com/Prod/Benefits

![Unauthenticated](../screenshots/unauthenticated_page.png)