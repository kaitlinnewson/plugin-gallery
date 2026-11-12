<!--
Thank you for contributing to the Plugin Gallery! Before you submit, review the
release guide: https://docs.pkp.sfu.ca/dev/plugin-guide/en/release

PKP reviews every plugin and release before it is listed. New plugins and large
changes take longer to review, so please be patient and do not open duplicate
pull requests.

Plugins must be secure, follow PKP's coding conventions
(https://docs.pkp.sfu.ca/dev/documentation/en/), support translation, and be
transparent about what they do with users' data.

Pull requests that do not complete this template, or do not answer it
truthfully, may be closed without review. A plugin that is later found to have
security issues, or that does not behave as described here, may be removed.
-->

## Plugin

- **Plugin name:**
- **Source code repository:**
- **License:**
- **Organizational affiliation (if any):**

**Type of change** (check one):

- [ ] New plugin
- [ ] New release of a plugin in the gallery
- [ ] Compatibility update or correction to an existing entry

## About the plugin

<!-- New plugins only. What does the plugin do, and who is it for? If a plugin in the gallery or a feature of the application already does something similar, how is this one different? -->

## Releases

<!-- For each release: the version, the application versions you tested it on (e.g. OJS 3.5.0-5), and what changed since the last listed release. -->

## External services and data

Does the plugin send data to, or receive data from, any service outside the installation? (check one)

- [ ] No
- [ ] Yes. Describe the service, what data is sent, and when:

Does the plugin require an account, subscription or payment with a third party? (check one)

- [ ] No
- [ ] Yes:

## AI use

Did you use AI tools to write the plugin code or this pull request? See [PKP's policy on AI contributions](https://pkp.sfu.ca/pkp-policy-ai/). (check one)

- [ ] No
- [ ] Yes. Describe how:

## Checklist

- [ ] The plugin has a `LICENSE` file with a GPL-compatible open-source license (e.g. GPL, MIT, BSD, Apache 2.0), and its source code is public.
- [ ] The release package contains a single directory named after the plugin's `product`, with no tests, demos or development dependencies.
- [ ] The `<release>` in the package's `version.xml` matches the `version` in `plugins.xml`.
- [ ] The README describes what the plugin does, its requirements, how to configure it, and any data it sends outside the installation.
- [ ] Handlers and API endpoints check the user's role and access to the objects they request, and template output is escaped.
- [ ] The repository has a private way to report security issues, such as [GitHub's private vulnerability reporting](https://docs.github.com/en/code-security/how-tos/report-and-fix-vulnerabilities/configure-vulnerability-reporting/configure-for-a-repository).

## Anything else reviewers should know
