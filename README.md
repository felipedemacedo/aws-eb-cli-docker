# AWS EB CLI on Docker

Interface de linha de comando do Elastic Beanstalk (EB CLI).

# Usage

Just run the following commands on terminal and use EB CLI commands as you wish. For more information about EB CLI read the [References](https://github.com/felipedemacedo/aws-eb-cli-docker#references) section of this document.

```java
ACCESS_KEY_ID=Your_AWS_Access_Key_Id
SECRET_ACCESS_KEY=Your_AWS_Secret_Access_Key

sudo docker run \
-e AWS_ACCESS_KEY_ID="$ACCESS_KEY_ID" \
-e AWS_SECRET_ACCESS_KEY="$SECRET_ACCESS_KEY" \
felipederodrigues/aws-eb-cli sh -c "eb --help"
```

# Changelog

 - [01/04/2020] Updated the EB CLI version from version 3.10.2 to 3.17.0.

# References

https://docs.aws.amazon.com/pt_br/elasticbeanstalk/latest/dg/eb-cli3.html

# Credits

All credits goes to https://hub.docker.com/r/mini/eb-cli/dockerfile