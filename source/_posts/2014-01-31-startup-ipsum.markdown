---
layout: post
title: "StartUp Ipsum"
author: "Alex Kestner"
date: 2014-01-31 00:45:20 -0500
comments: true
categories:
  - 'lorem ipsum'
  - python
  - 'test post'
---
##**Lorem lean**
startup ipsum product market fit customer development acquihire technical cofounder. User engagement A/B
testing shrink a market venture capital pitch deck. Social bookmarking group buying crowded market pivot onboarding
freemium prototype ping pong. Early stage disruptive ecosystem community outreach dynamic location based strategic
investor.
Accelerator photo sharing business school drop out ramen hustle crush it revenue traction platforms. Coworking viral
landing page user base minimum viable product <!-- more --> hackathon API mashup FB Connect. Main differentiators business model
micro economics marketplace equity augmented reality human computer interaction. Board members super angel preferred
stock.
Endless scroll recommendation engine cross platform responsive design OAuth.

```python
class CliArgs:
    def __init__(self, **cliargs):
        self.__dict__.update(cliargs)

    def __repr__(self):
        return """{!s}{!r}""".format(self.__class__, self.__dict__)


if __name__ == '__main__':
    #  init cross-platform colored output
    colorama.init()

    parser = argparse.ArgumentParser()
    subparsers = parser.add_subparsers()

    install_parser = subparsers.add_parser('install')
    install_parser.add_argument('install', nargs=argparse.ZERO_OR_MORE)

    install_parser = subparsers.add_parser('reinstall')
    install_parser.add_argument('reinstall', nargs=argparse.ZERO_OR_MORE)

    install_parser = subparsers.add_parser('uninstall')
    install_parser.add_argument('uninstall', nargs=argparse.ZERO_OR_MORE)

    list_parser = subparsers.add_parser('list')
    list_parser.add_argument('list', action='store_true')

    git_hooks = GitHooks(cliargs=CliArgs(**vars(parser.parse_args())))
```
___
*Tablet publishing HTML5 mobile first really simple syndication meetups white board walls. User experience iterate
algorithm gamification semantic web value add market research stealth. Rockstar developer internet of things bleeding
edge browser extension social capital. Sandboxing UDID content management system ruby on rails continuous deployment
big data infographic. Initial public offering financial model push notification mechanical turk bookmarklet. Term sheet
convertible note colluding bootstrapping. Cloud computing subscription model out of the box proactive solution.*

