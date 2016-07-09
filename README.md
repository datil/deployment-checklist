# Deployment Checklist

Important things to check before pushing the red button

## Front-end

- [ ] Run your tests. Yes, front-ends should have tests too.
- [ ] Run it on every device possible (phone, tablet, PC, Mac, small screens, big screens, etc.) and be sure that it works. If you feel fancy, try something like [Browserstack](https://www.browserstack.com/).
- [ ] Proofread entire application for grammar and spelling mistakes.
- [ ] Remove all Lorem Ipsum.
- [ ] If applicable, ensure links or contact information is entered correctly (social links, email, phone numbers, etc).
- [ ] Ensure that all required licenses are valid for necessary plugins, fonts and other related components.
- [ ] Ensure that Google Analytics or other related keys are correctly configured.
- [ ] Ensure all reference to static resources (internal and external) are using TLS

## Back-end

- [ ] Run your tests.
- [ ] Protect all endpoints against CSRF.
- [ ] Don't log sensitive data from forms.

## General

- [ ] Ensure no prod/staging/test environment settings are committed to version control.
- [ ] Ensure dependencies are up to date.
- [ ] Notify the change to everyone.

## Post Deployment

- [ ] Monitor application stats (RPM, logs, CPU and Memory usage) for at least an hour after the release.
- [ ] Monitor database performance.
- [ ] Check the logs.
