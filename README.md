# Uncommon Firebase Errors

This repository contains examples of uncommon errors that can occur when using the Firebase SDK, along with their solutions.

## Errors

* **Invalid Data Format:** The Firebase SDK might throw an error if the provided data is not in the correct format. For example, if you are trying to add a document to Firestore, and the data you are providing is not a valid JSON object, you might get an error like "Error: Invalid data. Data must be an object, but it was: undefined".
* **Authentication Errors:** Another error you may encounter when working with Firebase is the "auth/user-not-found" error. This happens when the authentication method being used cannot locate a user account that matches the credentials that were submitted. This typically happens when an invalid email or password is provided.

## Solutions

The solutions to these errors are included in the respective files in this repository.