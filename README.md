# midterm-prep-2

Midterm preparatory work for Java 401d12

## Requirements

### Pitch

- Build RESTful API.
- At least 2 models.
- At least 2 controllers with CRUD.
- Recommend auth i.e. Spring Auth.

### Project - After Approval

- Add documentation of the application: Readme/overview and Trello.
- A live Heroku or similar hosting platform deployment.

## Ideation

Roger: StackFellows? (name TBD by team)

- Stack-overflow-esque website.
- Allow user registration.
- Specific to CodeFellows curriculum, students.
- Community-built, community driven!

Jason: BetterMe

- Self-development App.
- Motivational quotes.
- Broad 'best practices in life?' ideas
- Flex-webapp sized for phone/tablet use

Jon: Online chess/checkers game

- Users self-register.
- Join a game and play other online players?

Roger: Feedback survey.

- Stores data to db.
- Get idea about how students are feeling: overloaded? Not challenged enough?
- Aggregate info into graphs.

Jason: Morse Code Generator // chat app:

- Takes user input on webapp ui.
- Sends morse-code or other encrypted type messages to another registered user.
- Peer-to-peer or host-to-host chat?

Jason: Sign-language conversion utility:

- User enteres text OR...
- Goes to a website.
- App translates to animated sign language on-screen.

Jason: Astronomical coordinate conversion utility

Jon: Code Generator Plug-in for IntelliJ

- After some research this appears to be more difficult that I anticipated.
- Does not use Spring framework, however could use a database.

## Go Forward Plan

Prepare to pitch ideas to Alex on 8Jun22 afternoon.

### Summaries

#### First Choice: StackFellows

- Stack-overflow-esque website.
- Allow user registration.
- Specific to CodeFellows curriculum, students.
- Community-built, community driven!
- CRUD: Database operations for registration, login, creating/updating/reading posts.
- WebApp with UI for registration, logon, and posting board.
- Spring Auth manages user authentication and authorization, and maybe profiles.
- Core logic in Java JDK 17.

MVP:

- Register and login, logoff.
- Leave a post about a bug/problem.
- DB stores the post along with user profile.
- Another registered user could read the post or comment on it.

#### Backup: BetterMe WebApp

Tech design:

- Webapp designed for phone, tablet, laptop, larger devices like Smart TV.
- Spring Auth manages user registration, login/logout, profile maangement with user preferences??
- REST (WebApp) and CRUD operations to a database storing user reg/log/profile and other data.
- DB used as cache a list of motivational statements, images?, music? etc as part of the webapp "experience".
- Core logic in Java JDK 17.

MVP:

- Users can Register and login, logoff.
- Splash page that fits phone/normal PC displays single quote, no additional content.
- Registered users granted access to more than 1 or 2 quotes, additional content.
- User created journal to add favorite quotes to journal, stored to DB in their "profile".
