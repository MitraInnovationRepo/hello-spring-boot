# hello-spring-boot
Sample application from Springboot - Integrate with AWS CodeBuild, AWS Deploy and AWS CodePipeline

- `appspec.yml` - configuration file for `AWS CodeDeploy`.
- `scripts/start_server.sh` and `scripts/stop_server.sh` - for `AWS CodeDeploy` to start and stop the JAVA application.
- `buildspec.yml` - `AWS CodeBuild` to compile and run unit tests. 
- Simple controller with responding `"Hello {name}!"`.