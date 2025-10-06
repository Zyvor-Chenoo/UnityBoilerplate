# Unreal Engine

WebGL published here (Zyvor-Chenoo!) https://github.com/Zyvor-Chenoo/UnityBoilerplate

# Setup Steps:

- [ ] I understand FERPA laws. If I make the repository public, I will remove any student information, or I am waiving the requirement to remove student information. Otherwise, I am making the repository private;
- [ ] I have forked the repository to my own GitHub account;
- [ ] I have edited the README.md file to include my own information on the url for the web build;
- [ ] I have followed the instructions to activate my personal licence here: https://game.ci/docs/github/activation/ ;
    - [ ] If I choose to make the repository private, I will follow this guide to add the instructor as a collaborator. https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-user-account/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository and set up the keys here https://game.ci/docs/github/builder/#private-github-repositories
- [ ] I changed the `Settings` > `Actions` > `General` > `Workflow Permissions` to `Read and write permissions for actions`;
- [ ] I cloned the repository to my local machine and opened the project in Unity and made changes to the project;
- [ ] I have committed and pushed the changes to the `main` or `master` branch of the repository;
- [ ] I understand that every time I push to the `main` or `master` branch, the project will be built and deployed to the `gh-pages` branch;
## Install Unreal Engine 4.23:
- [ ] Download and install the Epic Games Launcher.
- [ ]  Through the launcher, install Unreal Engine version 4.23.
- [ ] During installation, ensure the "HTML5" target platform is selected under "Installation Options." Deselecting other platforms can reduce installation size.
- [ ] Create or Open Your Project:
- [ ] Launch Unreal Engine 4.23.
- [ ] Create a new project or open an existing one that you wish to deploy to the web.
- [ ] Consider using a template like the Twin Stick Shooter for a quick test.
## Prepare for Packaging:
- [ ] Project Settings: Navigate to Edit > Project Settings.
- [ ] Packaging Settings: In the "Packaging" section, ensure "Full Rebuild" is selected and "For Distribution" is checked if you intend to deploy it publicly.
- [ ] HTML5 Platform Settings: Adjust any necessary settings specific to HTML5 if required for your project.
## Package the Project:
- [ ] Go to File > Package Project > HTML5.
- [ ] Choose a location on your computer to save the packaged build.
- [ ] Unreal Engine will then compile and package your project for HTML5. This process can take a significant amount of time depending on your project's complexity and your system specifications.
## Test Locally (Optional):
- [ ] After packaging, navigate to the build folder you specified.
- [ ] Locate the HTML5LaunchHelper.exe file within the build directory.
- [ ] Run this helper, and it will typically open a local web server.
- [ ] Open your web browser and navigate to http://localhost:8000 (or the address provided by the helper) to test your game in the browser.
## Deploy to a Web Server:
- [ ] The packaged build folder contains all the necessary files to host your game on a web server.
- [ ] Upload the contents of this folder to your chosen web hosting service.
- [ ] Ensure your web server is configured to serve the .html and associated files correctly.
- [ ] I saw the GitHub Actions build the project;
- [ ] I changed the `Settings` > `Pages` > `Source` to `gh-pages` branch;
- [ ] I saw the GitHub Actions deploy the project to the `gh-pages` branch;
- [ ] I can open the web build in the browser at the url: https://YOUR_GH_USERNAME.github.io/YOUR_REPO_NAME/
- [ ] I have read the https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow and understand the Gitflow workflow;
- [ ] I understand that I should create a new branch for each feature or fix I am working on;
- [ ] I have read the `.github/workflows/main.yml` file and understand how the GitHub Actions are working;
- [ ] If I want to customize my build, I will read the https://game.ci/docs/github/builder/ documentation; 
- [ ] I have read Semantic Versioning https://semver.org/ and understand how to version my project;
- [ ] I have read how Semantic versioning would work for unity here https://game.ci/docs/github/builder/#versioning 
- [ ] I have set my first git tag to `0.1.0` to my latest commit on the `main` or `master` branch;
