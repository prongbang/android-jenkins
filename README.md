# Android Jenkins Docker

## Run

```
docker-compose up -d
```

Image for service android-jenkins was built because it did not already exist. To rebuild this image you must use 
```
docker-compose build
```

or 

```
docker-compose up --build
```


## Jenkins initial setup

```
android-jenkins_1  | Jenkins initial setup is required. An admin user has been created and a password generated.
android-jenkins_1  | Please use the following password to proceed to installation:
android-jenkins_1  |
android-jenkins_1  | 50640addc04a462baxxxxxaa96fbaa02
android-jenkins_1  |
android-jenkins_1  | This may also be found at: /var/jenkins_home/secrets/initialAdminPassword
```

## Dockerfile from

https://github.com/futurice/android-jenkins-docker/blob/master/README.md