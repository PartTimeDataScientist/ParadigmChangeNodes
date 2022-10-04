# Apprise Notify Table Rows
## Description
This node can be used to send out a series of notifications defined in a table. It expects a table with at least three columns, one containing the notification URL and the other two with the message titles and message bodies. It can e.g. be used to notify the whole team about an issue with everyone receiving the notification on his or her preferred service. For a list of [supported notifications](https://github.com/caronc/apprise#supported-notifications) see the [Apprise GitHub Page](https://github.com/caronc/apprise) or the more detailed descriptions in the [Apprise wiki](https://github.com/caronc/apprise/wiki)

## Configuration
The node has three configuration options
1. URL-Column: The column containing the Apprise notification URLs (see above)
2. Title-Column: The column containing the message titles of the messages to be sent
3. Body-Column: The column contining the message bodies of the messages to be sent

## Ports
This node has a single port where it expects the table with the configuration columns