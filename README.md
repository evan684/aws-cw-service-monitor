# aws-cw-service-monitor

Use the CloudFormation Template 'aws-cw-service-monitor.yml' to launch the project.


Usage:

Two tags are required kick off services logging:

Key = MonitorWindowsServices, Value = Enabled

Key = Services, Value = Windows services to check the status of seperted by comma e.g. W3SVC,MSSQLSERVER.

