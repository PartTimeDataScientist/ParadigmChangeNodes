# Apprise Notify Multiple URLs
## Description
This is another rather simple Node in the collection of the *Apprise Nodes*. It can be used to send a simple notification to *up to five* service URLs. For a list of [supported notifications](https://github.com/caronc/apprise#supported-notifications) see the [Apprise GitHub Page](https://github.com/caronc/apprise) or the more detailed descriptions in the [Apprise wiki](https://github.com/caronc/apprise/wiki)

## Configuration
The node has three configuration options
1. URLs: The apprise URL defining the notification endpoint(s) (see above). Endpoints which are not to be used should contain `empty:` as URL.
2. Message Title: The title of the message to be sent
3. Message Body: The body of the message to be sent

!!! note 
    Due to the limitations of the Python based Node development it is currently not possible to define a larger input field for the body or allow attachments!

## Ports
This node has just a stub port to be able to connect the node to a workflow so that it can get executed.