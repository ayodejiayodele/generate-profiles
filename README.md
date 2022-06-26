# Generate profiles based on GitHub handles

This app generates stylised profile page based on a list of GitHub handles. Metadata displayed include profile photo, name, location and a link to the handle.

## How does this work?

1. Update the [members.md](members.md) markdown file with the github handles you wish to display (each handle on a separate line).
1. Commit the changes to the repo and [a workflow](../../actions/workflows/generate-page.yml) build is kicked off using GitHub Actions.
1. Select the build with the name of your commit in **Step 1** above and download the generated page from the `Artifacts` section.