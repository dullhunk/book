# Requirements for Computer Science jobs board

We are replacing moodle with a new web application to advertise jobs vacancies to students in Computer Science.

## Key Requirements (essential)

1. Authorised administrators can post new vacancies using an admin interface
2. Only students can search and browse vacancies, by using the Central Authentication Service (CAS) they use for [login.manchester.ac.uk](https://login.manchester.ac.uk)
3. Each job vacancy will have a unique URL that can be linked to e.g. (jobs.cs.manchester.ac.uk/some-identifier)[http://jobs.cs.manchester.ac.uk/some-identifier]
4. Students will be able to subscribe / unsubscribe to notifications (initially email) of new vacancies (making use of the newsagent API)
5. The application will work on mobile (e.g. tablet and smartphone, both macOS and Android), alongside a conventional desktop version

#### Administrator interface

1. Jobs entered to capture the following information.
    * Job title and description (to allow links and attachments mostly pdf/jpg )
    * Company / employer
    * Salary (if stated)
    * Location (e.g. London, Manchester etc)
    * Closing date (for applications)
    * Type of jobs
2. Several types of vacancy
    * Year long placement
    * Summer job
    * Part-time work
    * Undergraduate / Postgraduate
    * Graduate scheme / vacancy


## Project Milestones
