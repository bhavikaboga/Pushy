 # Java Install
- JDK: http://www.oracle.com/technetwork/java/javase/downloads/index.html
# Android Studio Install
- Android Studio: https://developer.android.com/studio/index.html
# Andriod SDK Setup
- Go to `Tools\SDK Manager`, go to `SDK Tools`
	- Make sure the following are installed:
		- Android SDK Build-Tools 28-rc1
		- Android Emulator
		- Android SDK Platform-Tools
		- Android SDK Tools
		- Google Play Services
		- Instant App Development SDK
# Android Emulator Setup
- Under `AVD Mangager`, Click `Create Virtual Device`
	- Click `Next`
	- Go to `x86 Images` and download `Relase Name- Lollipop, API Level- 21, ABI- x86_64`
# Git Setup
- Install Git: https://git-scm.com/downloads
- Go to `Files\Settings\Version Control\Git`
    - Make sure `Path to Git Executable` points to where git is installed 
# Start the Project
- In Android Studio, go to `Files\New\Project From Version Control\Git`
- Clone respository: https://github.com/bhavikaboga/Pushy.git

# Git Commands
- In the directory of the project, use the following commands <br>
	- `git init` \\ starts a local git repository <br>
	-`git status` \\ shows what files are up to date and what are not on your local repository <br>
- To update your local repository <br>
	-`git add -A` \\ adds all changed files <br>
	-`git commit -m "commit message"` \\ commits the changed files to your local repository <br>
- To share all your changes <br>
	-`git push` \\ pushes changed files to remote repository <br>
