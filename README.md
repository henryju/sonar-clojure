# SonarQube Clojure Plugin

This is a [SonarQube](https://www.sonarqube.org/) [plugin](https://docs.sonarqube.org/display/PLUG/Plugin+Library) 
that uses [Eastwood](https://github.com/jonase/eastwood) lint tool to analyze Clojure code.

## Current State

At the moment, SonarClojure is only capable of checking for lint rules that Eastwood can understand.


This plugin was inspired in the previous [SonarClojure](https://github.com/zmsp/sonar-clojure) that at
this moment is not under development anymore and doesn't support SonarQube 6.7. Since the changes to port
the old plugin were very extensive, I decided to start from scratch and use the old plugin as reference.


## Running it

Copy the jar file to the SonarQube plugins directory (`/opt/sonarqube/extensions/plugins/`) folder and restart 
the SonarQube server.

### Compatibility

We support SonarQube 6.7.

## Building from source
 
 `mvn clean package`
 
 That will generate an artifact under the folder *target*.


## License

SonarClojure is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).