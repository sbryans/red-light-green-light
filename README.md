# Purpose

The purpose of this repo is purely comical; it’s used in a scraping daemon I wrote living in a private network to bypass NAT and open a secure backdoor into the network in an "open-closed" manner. While many companies spend a lot on software to achieve the same goal, securing a connection into a private network without a VPN is simpler than you might think— it just takes a bit of architectural finesse & some brain power! This one for example comes with a sprinkle of RBAC. Message me for more details.

# Why GitHub Actions May Take a Few Minutes to Build

GitHub Actions is a powerful automation tool that allows you to define workflows for tasks such as continuous integration (CI), continuous deployment (CD), and much more. However, sometimes these workflows may take **a few minutes** to complete, especially during the build process. In this document, we'll explore why that happens and what factors contribute to the time it takes.

## Why GitHub Actions Take Time?

GitHub Actions builds involve multiple steps that can vary in complexity depending on the workflow you've defined however, even simple workflows can take in the upper 7 minutes to fully deploy.
