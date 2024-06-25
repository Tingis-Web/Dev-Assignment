<p align="center">
  <img src="../tw-logo.svg" alt="Tingis Web Logo" style="width:500px;">
</p>

### Project: Mini CRM Application

The purpose of this technical test is to give us an idea of how you interpret a technical problem and structure your code. The test is a mini CRM that connects a company with its employees. A company is created by an administrator, who can invite employees to join the company via email. After an employee joins, they can access and modify their data, as well as view their company's and colleagues' information. The application contains 2 spaces protected by an authentication layer:
* Super Admin space
* Employee space

## Super Admin Space:

* A super admin can log in to their space and create other super admins.
* A super admin can create, modify, or delete a company.
* Only companies without employees can be deleted.
* A super admin can invite employees to join a company via email.
* A super admin can search for a company or employee, or sort the list by name.
* A super admin can view the status of their invitations or cancel an invitation as long as it has not been confirmed.
* When a super admin invites an employee, the employee receives an email with a link to validate their profile.
* An employee can only be invited once.
* The super admin must specify the employee's name and email before sending the invitation.
* The employee's email field must be unique.

## Employee Space:

* After following the invitation link, the employee must set a password for their account and complete their profile (name, address, phone number, date of birth). Once the data is validated, the employee's account is considered verified.
* Until the employee has validated their profile, they cannot access their private space.
* An employee can only see their information and the information of their company and colleagues.
* Access to other companies' data and employees is prohibited.
* In their space, the employee can only modify their personal information on their profile page.

## History Module:

In the Administrator space, certain actions must be traceable and displayed on a History page to be consulted by other administrators. These actions should be grouped in a timeline format, containing the date of the action and a descriptive message.

These actions include:
* Sending an invitation
* Canceling an invitation
* Validating an invitation
* Confirming an employee's profile

Example of a descriptive message to be displayed on the History page:

* 12-08-2022 - 09:00 / Admin “John Doe” invited employee “Jack White” to join the company “Media LTD”
* 12-08-2022 - 10:00 / “Jack White” validated the invitation
* 12-08-2022 - 10:30 / “Jack White” confirmed his profile

## Notes:

   - Add a detailed README in the GitHub repository.
   - Include instructions on how to set up and run the application using Docker.
   - Document the API endpoints and their usage.
   - Include setup instructions for the database and WebSocket server.

## Additional Notes:

- Encourage clean, maintainable code with comments where necessary.
- Suggest best practices for commit messages and Git branching strategy.
- Emphasize the importance of writing unit tests for both frontend and backend code.

### Things that will be considered:

- Code quality and adherence to best practices.
- Completeness and correctness of the implemented features.
- Quality of the documentation.
- Effective use of Docker for containerization.
