# code-review-resources

Guidelines
https://rules.sonarsource.com/

Resource
https://vladtoie.gitbook.io/secure-coding/

Tools
https://www.sonarqube.org/downloads/
https://deepsource.io/signup/
https://github.com/pyupio/safety
https://github.com/returntocorp/semgrep
https://github.com/WhaleShark-Team/cobra
https://github.com/mhaskar/Bughound

Find interesting strings
https://github.com/s0md3v/hardcodes
https://github.com/micha3lb3n/SourceWolf
https://libraries.io/pypi/detect-secrets

Tips
1.Important functions first
2.Follow user input
3.Hardcoded secrets and credentials
4.Use of dangerous functions and outdated dependencies
5.Developer comments, hidden debug functionalities, configuration files, and the .git directory
6.Hidden paths, deprecated endpoints, and endpoints in development
7.Weak cryptography or hashing algorithms
8.Missing security checks on user input and regex strength
9.Missing cookie flags
10.Unexpected behavior, conditionals, unnecessarily complex and verbose functions
