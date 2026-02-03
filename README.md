## Technical Stack
Python + pytest + SQLAlchemy + requests + Allure + jsonpath + YAML + Jenkins + Linux

## Project Description
This project is an online shopping e-commerce platform that includes core functionalities such as user registration, login, placing orders, listing/unlisting products, and payment processing. An API automation framework was built specifically for this website, which encapsulates HTTP requests, implements inter-API data correlation, response validation, and database assertions.

## Responsibilities
- Utilized the **pytest** testing framework to organize and manage test cases, and configured test execution rules via `pytest.ini` in combination with `conftest.py`.
- Adopted **jsonpath** as the JSON extractor and stored API configuration parameters in **YAML** files to decouple test data from test logic, enhancing maintainability and reusability.
- Implemented robust validations using Python’s `assert` keyword to verify API response content, HTTP status codes, and database states (via **SQLAlchemy**), ensuring test reliability and stability.
- Applied the **Page Object Model (POM)** design pattern to separate the test logic layer from the request driver layer, enabling end-to-end test coverage for user management and the complete product ordering workflow, significantly improving script compatibility and scalability.
- Constructed API requests (including URL, headers, request body, authentication tokens, etc.) using **YAML** templates, and leveraged `pytest.mark.parametrize` to dynamically load and inject test parameters into test cases.
