# wp-volt
Volt integration for WordPress

The purpose of this package is to enable using the [Volt Template Engine](https://docs.phalconphp.com/en/latest/volt) from the Phalcon framework for WordPress themes.

**To Do:**
- [ ] Should this be a Theme or a Plugin?
- [ ] Check if Phalcon is installed on the server. Fail gracefuly if it isn't.
- [ ] Have a way to render a simple template with Volt syntax (e.g. `{{ '<h1>Hello<h1>' }}`).
- [ ] Identify the global variables commonly used in themes, and make sure they are available to the Volt templates as variables with the appropriate scope.
- [ ] Have a way to pass any variable to the template (to allow support for 3rd party plugins and custom logic).
