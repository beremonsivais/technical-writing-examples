# Contributions to open source projects

## Github Docs

### Example #1

- **Issue:**
The example in "[Example usage of the vars context](https://docs.github.com/en/actions/learn-github-actions/contexts#example-usage-of-the-vars-context)" states that configuration variables at the environment level are automatically available. The example fails if the environment is not declared by the runner before using the configuration variables in the `vars` context.

- **Achievements:**
Replicated the test runs documented in the issue. Understood and implemented the resolution given by the SME (subject matter expert). Added a [note](https://docs.github.com/en/actions/learn-github-actions/contexts#example-usage-of-the-vars-context) to the section "[Example usage of the vars context](https://docs.github.com/en/actions/learn-github-actions/contexts#example-usage-of-the-vars-context)" to warn users of the correct usage of configuration variables at the environment level in the `vars` context.

- **Pull Request:** https://github.com/github/docs/pull/34510/

### Example #2

- **Issue:**
In the section "[Event object common properties](https://docs.github.com/en/rest/using-the-rest-api/github-event-types?apiVersion=2022-11-28#event-object-common-properties)", the Event API attribute name `id` describes the relative types of the objects `repo`, `actor` and `org`  as string instead of integer.

- **Achievements:**
Edited the original file to show the correct data types for the mentioned objects. 

- **Pull Request:** https://github.com/github/docs/pull/34496/

## Github Open Source Guides

- **Issue:**
Typographical errors in the Spanish version of [Starting an Open Source Project](https://opensource.guide/es/starting-a-project/).

- **Achievements:**
Identified the typographical errors in Spanish and edited the original file. Read the English version to understand the objetive of the text.

- **Pull Request:** https://github.com/github/opensource.guide/pull/3291/

