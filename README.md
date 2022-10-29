# jira

## Description

Easily open an issue on Atlassian's Jira issue tracker from the CLI.

## Installation

```shell
$ brew tap thoran/tap
$ brew install jira
```

## Setup

Ensure that the Atlassian subdomain for your project is configured in ~/.config/jira.rb like so:

```ruby
SUBDOMAIN = 'subdomain'
```

## Usage

a. If the branch name begins with the Jira issue id one may simply do:

```shell
$ jira
```

b. Or, if the branch name doesn't begin with the Jira issue id or one is on a different branch one may specify the issue id thusly:

```shell
$ jira <ticket_id>
```

## Contributing

1. Fork it... `https://github.com/thoran/jira/fork`
2. Create your feature branch... `git checkout -b my-new-feature`
3. Commit your changes... `git commit -am 'Add some feature'`
4. Push to the branch... `git push origin my-new-feature`
5. Create a new pull request
