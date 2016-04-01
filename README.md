maven-download
=========

Modified version of maven_artifact re-downloading snapshot versions.

Example Playbook
----------------

    - hosts: servers
      roles:
         - maven-download
      tasks:
         - maven_download: group_id=commons-cli artifact_id=commons-cli version=1.4-SNAPSHOT repository_url=https://repository.apache.org/snapshots/ dest=./commons-cli-1.4-SNAPSHOT.jar

License
-------

BSD
