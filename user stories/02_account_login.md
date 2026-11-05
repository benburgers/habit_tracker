# Account login

**Title:**
_As a user, I want to log in using my username and password, so that I can access my account and track my habits._

**Acceptance Criteria:**
1. _The user can enter their username and password._
2. _The user's username and password are checked with their known account._
3. _If the user's username and password are invalid, the user is informed. ([Error feedback on login](03_error_feedback_on_login.md))_
4. _If the user's username and password are valid, the user is granted access to their account._
5. _If the user's username and password are valid, the user is granted the ability to track their habits._

**Priority:** _High_

**Story Points:** _5_

**Notes:**
- The credentials are sent through a secure connection.
- The password must not be visible by default.
- Due to security constraints, the credentials are not saved in the browser cache but are removed once the user logs out.