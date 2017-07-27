# nodered-jira
Node-Red nodes for connecting to JIRA's REST API.

## Nodes
* JIRA Search node - Search for issues by using a JQL-query. 
  * msg.jql parameter accepted (0.0.2)
  * msg n'est pas effacer comme dans la version original. (0.0.2)
* JIRA Issue Update node - Update fields of an issue.
* JIRA Issue get node - Get a JIRA issue by its key.
* JIRA Issue Create - Create a new Issue.
* JIRA Comment Add - Add a comment to an existing issue.
* JIRA Comment Update - Update an existing JIRA comment.

## TODO
* JIRA Transition node - Permet de faire avancé le billet JIRA dans le workflow.
