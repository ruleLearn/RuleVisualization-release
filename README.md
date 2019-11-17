# RuleVisualization - released application versions 
------------------------------------------------

### What's new
- `version 1.1.1`:
  - modified data - RuleML file of embeded `windsor` data set changed to version containing also characteristics of decision rules, car data set added to drop list of embeded data sets, client application rebuild from sources after GUI update (see [RuleVisualization-client commit message](https://github.com/ruleLearn/RuleVisualization-client/commit/d748e3dbf33dc5998626cf4f12b0731ff5e333ab) for more details)
- `version 1.1.0`:
  - modified server application - added car data set, fixed handling of values of confirmation measure L (positive infinity is serialized as max double value), employed ruleLearn library in version 0.14.3 (allowing confirmation measure L to have value greater than 1), embeded user guide replaced  with PDF file linking to up-to-date user documentation available on-line, small corrections and style change of that user guide, client application left unchanged
- `version 1.0.0`:
  - original version of the application supplied by M.Sc. student Mateusz Lewandowski, employing ruleLearn library in version 0.14.2 and containing embeded user guide (PDF)

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