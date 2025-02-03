# User Domain

This repository contains the user domain for a microservices-based application. The domain includes the `user-service` and optionally the `profile-service`. The `user-domain` focuses on managing user-related operations and data.

## Services

### user-service

The `user-service` manages user-related operations such as user creation, updating user information, retrieving user details, and deleting user accounts.

#### Endpoints

- **Create User**: Create a new user.
- **Get User**: Retrieve user details by user ID.
- **Update User**: Update user information.
- **Delete User**: Delete a user account.

#### Dependencies

- **Database**: PostgreSQL

### profile-service (optional)

The `profile-service` manages user profiles, including profile information, preferences, and user-specific settings.

#### Endpoints

- **Get Profile**: Retrieve a user's profile.
- **Update Profile**: Update a user's profile.
- **Delete Profile**: Delete a user's profile.

#### Dependencies

- **Database**: PostgreSQL

## Directory Structure

The repository is structured as follows:

