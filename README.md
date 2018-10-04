# Version Control Infos for Administartion Console

This extensions adds a "Version Information" tab to the hybris administration console.

The displayed properties (`hacvcsinfo/resources/hacvcsinfo/vcs.properties`) are generated in `buildcallbacks.xml`, and contain:

- commit hash
- tag
- branch name

of the current git HEAD.

Feel free to adjust the callback to include any other information you need, the new tab displays all properties without
any filter.