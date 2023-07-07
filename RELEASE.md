#### Update version

`mvn org.eclipse.tycho:tycho-versions-plugin:2.7.5:set-version -DnewVersion="1.0.2-SNPASHOT"`


#### Deploy p2 Repository

Create a tag `v1.0.1` and push it. GH Action will create a p2 repository and publish it to GH Pages.

