# Simple Survey

## Provide plugin to create surveys to gather user experience information and backend plugin to view results.

### Getting started

* Install extension
* Include static TypoScript

### Administration

* Go to list module view
* Choose folder storage
* Create new survey record
    * Fill in survey fields
* On "Questions" tab add questions
* Each question has next options:
    * Type:
        * Radio button. Use in case if user should choose only one option
        * Checkboxes if multiple answer allowed
        * Free input field
    * Is question required
    * Free input field type
    * List of answers
* Create answers for each question
* Survey is ready

### Plugin usage

* Create page that'll contain plugin
* Add new content element, go to "Plugins" tab and choose "Simple survey"
    * Choose survey from storage
    * Choose plugin mode, either "show survey" or "survey results".
    * Show all questions at once - show questions step by step or all
    * Allow/Disallow user to take part in survey more than once
    * Protect with [reCAPTCHA](https://www.google.com/recaptcha/)
    * Add message displayed when user has finished survey


### Module usage

* In "Web" section choose "Survey Analysis" module
* Choose storage folder
* Find your survey and check analysis Data or export in CSV