# GeekyJudger
Judger with Docker.

GeekyJudger is leading a new age in judging user apps. This can be used in OI/ACM judging (strict mode), but also have a normal mode, which allows the user app run any command, even have the access to the network. (You can decide it) So this can be used in many other ways. Because we run the user app in a pure Linux container, you don't need to worry about security.

--------------------

* `images/judge/normal` The image of the judger container in normal mode. (User app have **root** access to the container and you can ch
* `images/judge/strict` The image of the judger container in strict mode. (User app do not have any permission to do any thing except calculating.)

License
-------
MIT.
