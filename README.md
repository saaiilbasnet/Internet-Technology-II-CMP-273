# Internet Technology II - CMP 273

PHP practicals and mini-projects from Saaiil Basnet's Internet Technology
II coursework, reclassified by unit into readable, one-problem-per-file
solutions. Files that used generic names like `index1.1.php` were
renamed to describe the problem they solve; files that were already
descriptively named (Unit-IV onward) were left as-is.

## Unit-I-Basics - PHP basics: variables, constants, operators
- `name_age_city_intro.php` - variables + string interpolation
- `arithmetic_operations.php` - sum/difference/product/quotient of two numbers
- `var_dump_types.php` - var_dump on string/int/float/boolean
- `constants_demo.php` - defining and echoing constants
- `rectangle_area.php` - area of a rectangle
- `modulus_remainder.php` - modulus operator
- `compound_assignment_score.php` - compound assignment operators (+=, -=)
- `celsius_to_fahrenheit.php` - temperature conversion
- `logical_operators_var_dump.php` - && / || with var_dump
- `full_name_concat.php` - string concatenation
- `operators_demo.php` - arithmetic, assignment, logical operators, null coalescing (`??`)
- `dynamic_content_intro.php` - mixing PHP output with HTML, `date()`

## Unit-II-ControlStructures - control structures & loops
- `number_greater_than_100.php` - if statement
- `even_odd_check.php` - if-else
- `grade_calculator.php` - if-elseif-else grading
- `ternary_operator_demo.php` - ternary operator
- `day_of_week_switch.php` - switch-case
- `for_loop_1_to_10.php` - for loop
- `dice_roll_while.php` - while loop (roll until a 6)
- `do_while_demo.php` - do-while loop
- `foreach_array_demo.php` - foreach over an array
- `break_loop_demo.php` - break
- `continue_loop_demo.php` - continue
- `loopdemo.php` - all four loop types side by side

## Unit-III-ArraysStringsFunctions - arrays, strings, functions, dates
- `associative_array_product.php` - associative arrays
- `foreach_keys_values.php` - foreach with keys and values
- `nested_array_lookup.php` - array of associative arrays
- `string_length_uppercase.php` - strlen / strtoupper
- `htmlspecialchars_demo.php` - securely displaying HTML output
- `explode_implode_demo.php` - explode / implode
- `rand_and_round_demo.php` - rand() and round()
- `number_format_demo.php` - number_format()
- `date_format_demo.php` - date() formatting
- `datetime_add_days.php` - DateTime + date arithmetic
- `array_sort_demo.php` - sort() / ksort()
- `in_array_count_demo.php` - in_array() / count()
- `calculate_vat_function.php` - a VAT-calculating function
- `function_scope_demo.php` - variable scope inside functions
- `generate_button_function.php` - a function that outputs HTML
- `arrayFunctions.php` - count/sort/rsort/implode built-ins
- `myArray.php` - indexed vs. dynamically-built arrays
- `userDefineFunction.php` - a basic user-defined function

## Unit-IV-FormsFileHandlingEmail - forms, validation, file handling, email
- `simplephpform.php` - a basic HTML form processed by PHP
- `stickyFormDemo.php` - a form that retains submitted values
- `typebasedvalidation.php` - validating input by expected type
- `registeruser.php` - a registration form
- `handle_form.php` - form submission handler
- `fileHandlingForm.php` - uploading a file via a form
- `PHPMailerDemo.php` - sending email with the vendored PHPMailer library (`PHPMailer/`)

## Unit-V-SessionsCookiesAuth - sessions, cookies, file access, auth
- `start.php`, `cookie.php`, `read_cookie.php` - setting/reading cookies
- `list_file.php`, `read_file.php`, `delete_file.php`, `securely_upload.php` - server-side file operations
- `dashboard.php`, `index.php` - a small session-driven page, using `includes/header.php` and `includes/functions.php`
- `Auth/login.php`, `Auth/logout.php`, `Auth/dashboard.php`, `Auth/user.php` - a minimal login/session auth flow

## Unit-VI-MySQL - MySQL integration
- `database-connection.php` - the shared DB connection
- `create-operation.php`, `retrieve-operation.php`, `update-operation.php`, `delete-operation.php` - CRUD against MySQL
- `login.php`, `login-operation.php` - a login form backed by the database
- `login-sqlinj-prevention.php` - the same login, rewritten with prepared statements to prevent SQL injection
- `register-user.php` - a registration form backed by the database

## Unit-VII-OOP - OOP in PHP
- `inheritance.php` - class inheritance
- `abstraction.php` - abstract classes
- `encapsulation.php` - private properties with getters/setters

## MVC Pattern
A minimal Model-View-Controller example: `Models/productModel.php`,
`Views/productView.php`, `Controllers/productController.php`.

## Small-Projects
- `calculator.php` - a styled POST-based calculator
- `usernameGenerator.php` - generates a username from a first/last name
- `RegistrationForm.php`, `myRegForm.php` - registration form variations
