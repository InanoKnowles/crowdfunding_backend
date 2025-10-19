
# Project Description
Create a crowdfunding website

# Project Requirements

**Your crowdfunding project must:**
- [ ] Be separated into two distinct projects: an API built using the Django Rest Framework and a website built using React.
- [ ]  Have a cool name
- [ ]  Have a clear target audience.

- **[ ]  Have user accounts. A user should have at least the following attributes:**
  - [ ] Username
  - [ ]  Email address
  - [ ] Password

- [ ] **Ability to create a “fundraiser” to be crowdfunded which will include at least the following attributes:**

   - [ ] Title
   - [ ] Owner (a user)
   - [ ] Description
   - [ ] Image
   - [ ] Target amount to raise
   - [ ] Whether it is currently open to accepting new supporters or not

**When the fundraiser was created**

- [ ] **Ability to “pledge” to a fundraiser. A pledge should include at least the following attributes:**
    - [ ] An amount
    - [ ] The fundraiser the pledge is for
    - [ ] The supporter/user (i.e. who created the pledge)
    - [ ] Whether the pledge is anonymous or not
    - [ ] A comment to go along with the pledge
- [ ] Implement suitable update/delete functionality, e.g. should a fundraiser owner be allowed to update its description?
- [ ] Implement suitable permissions, e.g. who is allowed to delete a pledge?
- [ ] Return the relevant status codes for both successful and unsuccessful requests to the API.
- [ ] Handle failed requests gracefully (e.g. you should have a custom 404 page rather than the default error page).
- [ ] Use Token Authentication, including an endpoint to obtain a token along with the current user's details.
- [ ] Implement responsive design.



# Crowdfunding Back End
Inano Knowles

# Link to deployed project
To be added

## Planning:
### Crowdfunding Project: Cuppa
Buy a cuppa for your nearest parental figures

### Intended Audience/User Stories
Parenting communities

### Front End Pages/Functionality
- {{ A page on the front end }}
    - {{ A list of dot-points showing functionality is available on this page }}
    - {{ etc }}
    - {{ etc }}
- {{ A second page available on the front end }}
    - {{ Another list of dot-points showing functionality }}
    - {{ etc }}

### API Spec
{{ Fill out the table below to define your endpoints. An example of what this might look like is shown at the bottom of the page. 

It might look messy here in the PDF, but once it's rendered it looks very neat! 

It can be helpful to keep the markdown preview open in VS Code so that you can see what you're typing more easily. }}

| URL | HTTP Method | Purpose | Request Body | Success Response Code | Authentication/Authorisation |
| --- | ----------- | ------- | ------------ | --------------------- | ---------------------------- |
|     |             |         |              |                       |                              |

### DB Schema
![]( {{ ./relative/path/to/your/schema/image.png }} )

### Submission Checklist
- [ ]  A link to the deployed project.
- [ ]  A screenshot of Insomnia, demonstrating a successful GET method for any endpoint.
- [ ]  A screenshot of Insomnia, demonstrating a successful POST method for any endpoint.
- [ ]  A screenshot of Insomnia, demonstrating a token being returned.
- [ ]  Step by step instructions for how to register a new user and create a new fundraiser (i.e. endpoints and body data).
- [ ]  Your refined API specification and Database Schema.