# RuleVisualization - released application versions 
------------------------------------------------
### Content
Each released version of the application (each [release](https://github.com/ruleLearn/RuleVisualization-release/releases)) is composed of:
- `server fat jar`, compiled from source files of [https://github.com/ruleLearn/RuleVisualization-server](https://github.com/ruleLearn/RuleVisualization-server) project,
- `demo data sets`,
- `client code` (HTML + JS + CSS), compiled from source files of [https://github.com/ruleLearn/RuleVisualization-client](https://github.com/ruleLearn/RuleVisualization-client) project,
- information concerning location of PDF user guide.

### Running downloaded release (after unpacking zip archive):
1. Run server by running batch script `./run-server.bat` or by running:
   `java -jar server/server.jar <port>`

   Default port is `8081`, if not specified.
2. Run client by loading web page `client/index.html` file or by using shortcut `./run-client.lnk` (on Windows OS; shortut may need to be adjusted first).

### User documentation
- [https://github.com/ruleLearn/RuleVisualization-documentation](https://github.com/ruleLearn/RuleVisualization-documentation) (tex files)
- [https://github.com/ruleLearn/RuleVisualization-documentation/releases](https://github.com/ruleLearn/RuleVisualization-documentation/releases) (pdf releases)