# Writing Awesome Release Notes!

## What are Release Notes?

Release notes provide an inventory of changes (that a user would notice/care about) from one published release to another.

Release Notes are developed for a given release throughout a given release cycle using the work items that are assigned to the release. Work items are evaluated throughout the release to determine which of them would require a release note. Accordingly, the best approach id to write and review Releases Notes throughout the duration of the release cycle. Release Notes should not be written at the end of the release.

## Types of Release Notes

### New Features

This category includes description of new features being added for a release. Release Notes must be written for all new features in a release to let users know what new is available in a release.

>**Format: When writing a release note in this category, indicate what is new followed by the purpose of the feature.**

### Enhancements

This category includes enhancements or changes to existing features. Though it’s important to document changes to existing features, a writer should avoid documenting minor UI or other changes. Such changes should be just updated in the help. Also, changes not visible to users (like code clean up) should not be documented unless the code change results in behavior change in the product.

>**Format: When writing a release note in this category, indicate purpose of the change followed by what has changed.**

### Resolved Issues

This category includes bug or issue fixes. The issues listed in this category exist in an already released version of the product. The work item requiring a resolved issue release note would meet one of the conditions:

- Raised by the user
- Critical or high severity
- A known issue was written in a previous release but has been fixed in this release

>**Format: When writing a release note in this category, start with past tense as the issue had occurred in past. Indicate what was the issue followed by a clear statement indicating that the issue has been fixed. If the fix is complicated or might lead to a noticeable change for the user, describe the new behavior in present tense.**

### Obsolete Features

This category includes features that have been deprecated or discontinued in a release. An issue must be documented as an Obsolete Issue if it becomes obsolete in a specific version due to the code changes in that version. This happens particularly when a module or feature has been entirely redesigned, causing some of the previously known issues to become obsolete. I have also observed that in certain cases, a new feature has rendered an existing functionality/button obsolete.

>**Format: When writing a release note in this category, specify what has been removed/deprecated, and then specify the purpose. If the removed feature has been replaced with another feature, include that information.**

### Known Issues

This category includes issues that will exist in an outgoing release. Usually, the critical and high severity issues that are not fixed make their way to this category. If a workaround is available, include that in the release note.

>**Format: When writing a release note in this category, write the issue in present tense, followed by a workaround (if available).**

## Considerations when Writing Release Notes

- Release Notes are provided in conjunction with the help documentation. When writing a release note, always consider whether any documentation needs to be revised, and whether any new documentation needs to be added.
- Release notes should conform to the writing standards used throughout documentation.
- Always match the references/terms in release notes with references/terms used in the corresponding feature in the help documentation. It is not a standalone document but part of the overall product help documentation. Users will see the highlights here and then find details in the product help documentation. Therefore, it is essential that consistent terms are used in Release Notes and product documentation.