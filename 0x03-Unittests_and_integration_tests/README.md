
# Unittests and Integration Tests

This project focuses on writing various unit tests and integration tests to ensure the reliability and correctness of Python code, particularly for a utility library and a simple client for GitHub organizations. The tasks involve using the `unittest` framework, parameterizing tests, mocking external calls, and integration testing with fixtures.

## Tasks

### 0. Parameterize a unit test

- **Description**: Write a unit test for `utils.access_nested_map` to ensure it returns the correct output for given inputs.
- **File**: `test_utils.py`

### 1. Parameterize a unit test (Exception Handling)

- **Description**: Implement a test to check that `utils.access_nested_map` raises a `KeyError` with specific inputs.
- **File**: `test_utils.py`

### 2. Mock HTTP calls

- **Description**: Test the `utils.get_json` function without making actual HTTP calls by mocking `requests.get`.
- **File**: `test_utils.py`

### 3. Parameterize and patch

- **Description**: Write a test for the `utils.memoize` decorator to ensure it caches the output of a method properly.
- **File**: `test_utils.py`

### 4. Parameterize and patch as decorators

- **Description**: Test `client.GithubOrgClient.org` method using patching and parameterization to ensure it returns the correct value.
- **File**: `test_client.py`

### 5. Mocking a property

- **Description**: Unit-test `GithubOrgClient._public_repos_url` method by mocking the `org` property.
- **File**: `test_client.py`

### 6. More patching

- **Description**: Test the `GithubOrgClient.public_repos` method by mocking dependent methods and properties.
- **File**: `test_client.py`

### 7. Parameterize

- **Description**: Parameterize tests for `GithubOrgClient.has_license` to ensure it correctly identifies repositories with a specific license.
- **File**: `test_client.py`

### 8. Integration test: fixtures

- **Description**: Implement integration tests for `GithubOrgClient.public_repos` using fixtures for mocking external requests.
- **File**: `test_client.py`

### 9. Integration tests

- **Description**: Further integration tests for `GithubOrgClient.public_repos` with emphasis on testing with the `license` argument.
- **Advanced Task**
- **File**: `test_client.py`
