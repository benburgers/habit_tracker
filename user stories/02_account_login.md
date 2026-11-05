# Account login

**Title:**
_As a user, I want to log in using my username and password, so that I can access my account and track my habits._

**Acceptance Criteria:**
1. The user can enter their username and password.
2. The user's username and password are checked with their known account.
3. If the user's username and password are invalid, the user is informed. ([Error feedback on login](03_error_feedback_on_login.md))
4. If the user's username and password are valid, the user is granted access to their account.
5. If the user's username and password are valid, the user is granted the ability to track their habits.

**Priority:** _High_

**Story Points:** _5_

**Notes:**
- The credentials are sent through a secure connection.
- The password must not be visible by default.
- Due to security constraints, the credentials are not saved in the browser cache but are removed once the user logs out.