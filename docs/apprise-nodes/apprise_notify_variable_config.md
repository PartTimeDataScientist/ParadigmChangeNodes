# Apprise Notify Variable Config
## Description
This node can be used to send out Apprise notifications to a list of URLs defined in a flow variable 'apprise_config'. The flow variable is split at the newline ("\n") character and everey row is added as an Apprise target URL. For a list of [supported notifications](https://github.com/caronc/apprise#supported-notifications) see the [Apprise GitHub Page](https://github.com/caronc/apprise) or the more detailed descriptions in the [Apprise wiki](https://github.com/caronc/apprise/wiki)

## Configuration
The node has two configuration options
1. Message Title: The title of the message to be sent
2. Message Body: The body of the message to be sent

## Ports
This node has a single port where it expects to find a flow variable '*apprise_config*'