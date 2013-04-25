# As part of the rename of the JBoss Application Server project to WildFly, the jboss-as git repo has been moved to <http://github.com/wildfly/wildfly>.

Please use this location for all purposes from now on.

Follow these steps to update your repo:

1. Create a new fork of the linked wildfly repo into your own copy
2. In your local checkout execute the following commands (assuming you have an origin and an upstream)

> git remote set-url origin git@github.com:[username]/wildfly.git

> git remote set-url upstream git://github.com/wildfly/wildfly.git

NOTE: After these steps you can rename your jboss-as directory to wildfly (optional)
