This repository centralizes issue tracking for Mee

# Intro
## Want to report an issue?
1. Make sure the problem has not been reported yet. Duplicates cost valuable time from development, uxer experience and customer success;
1. Make sure you can reproduce the problem and include the steps necessary to do so;
1. Then open the issue, following the rules below:
    1. Add a label. Most used are "bug" and "enhancement";
    1. Include the URL: the text that was on your's [browser's address bar](https://en.wikipedia.org/wiki/Address_bar) when the issue happened;
    1. Add the [environment](#Environments) and release you're in to the title. e.g.: "[test][1.0.0-alpha.1] Error message for failed login toast not internacionalized";
    1. Include the device used along its Operational Sytem version. e.g.: "Laptop, Windows 10" or "iPhone XR, iOS 13.4.1";
    1. Include the browser used and browser version. e.g.: "Chrome, Versão 81.0.4044.138 (Versão oficial) 64 bits";
    1. Add screenshots if you think it will help to explain the issue;
    1. Make sure what you have written down is put in a way that others can understand too. The reader will be in another context!

## Is it your first issue on GitHub?
Please, spare at least 30 minutes of your time and read:

1. [This guide on mastering GitHub issues](https://guides.github.com/features/issues/);
1. [This guide on formating content on GitHub](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet);
1. [This best practices](https://www.zenhub.com/blog/best-practices-for-github-issues/).

## You're a developer and want to reference an issue?
Read this wuote from [Creating an issues-only repository](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-an-issues-only-repository):
> For example, if you pushed a commit to the private repository's default branch with a message that read Fixes organization/public-repo#12, the issue would be closed, but only users with the proper permissions would see the cross-repository reference indicating the commit that closed the issue. Without the permissions, a reference still appears, but the details are omitted.


# Environments

## production
This the environment people use to do business with Mee:
- Web Client: https://mee.cc
- Documentation: http://read.mee.cc
- API: https://api.mee.cc/prod

## staging
Environment for release quality assurance:
- Web Client: https://staging.mee.cc
- API: https://api.mee.cc/staging

## test
Environment for release and feature testing:
- Web Client: https://test.mee.cc
- API: https://api.mee.cc/test

## development
Developers only environment:
- Web Client: https://dev.mee.cc
- API: https://api.mee.cc/dev

