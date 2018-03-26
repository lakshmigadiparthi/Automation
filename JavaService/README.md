===Overview===

This is Basic Ansible Repository for Auto Deploying a Java Application from Nexus into targeted Servers in different environments.

hosts file is inventory of hosts which contains IP’s of targeted servers. We are grouping some list of IP’s under some category. If we have different groups of servers like dev, QA, alpha, beta and prod

In JavaServiceDeployment.yml hosts can be specified or we can pass the hosts dynamically. For passing hosts dynamically we can use hosts: “{{ variable_host | default(‘Group1}}”

The configurations needed for all groups can be specified in file named “all” and if they are specific to particular group like group1 or group2 they can be specified in file named DC2 and D5.
