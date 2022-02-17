Naming for units:

 - Pytest search for file with name started like `test_` or ended with `_test` 
 - The test methods and functions must be named `test_<something>.`
 - Test classes must be named `Test<Something>`.

The test of a single unit is done with `::test_name`

The configuration files can be `pytest.ini`, `tox.ini` or `setup.cfg`

CLI commands for pytest:
1. Pytest help
>  pytest -help
2. Additional info about test proccess
>    -v --verbose
3. List of all tests
> --collect-only
4. Test only files with current expression
>  -k EXPRESSION
5. Running labeled tests using the @pytest.mark.<`expression`> decorator
> pytest -v -m <`expression`>
6. Stop, when find first fail test
>  -x, --exitfirst
7. Print stdout 
>  -s and --capture=method
8. Reduces the amount of information in the report
>  -q, --quiet