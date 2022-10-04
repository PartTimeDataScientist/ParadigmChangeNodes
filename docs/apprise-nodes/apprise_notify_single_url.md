# Apprise Notify Single URL
## Description
This is the most simple Node in the collection of the *Apprise Nodes*. It can be used to send a simple notification to a single service URL. For a list of [supported notifications](https://github.com/caronc/apprise#supported-notifications) see the [Apprise GitHub Page](https://github.com/caronc/apprise) or the more detailed descriptions in the [Apprise wiki](https://github.com/caronc/apprise/wiki)

## Configuration
The node has three configuration options
1. URL: The apprise URL defining the notification endpoint (see above)
2. Message Title: The title of the message to be sent
3. Message Body: The body of the message to be sent


!!! note 
    Due to the limitations of the Python based Node development it is currently not possible to define a larger input field for the body or allow attachments!

## Ports
This node has just a stub port to be able to connect the node to a workflow so that it can get executed.