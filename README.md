![0](https://user-images.githubusercontent.com/58392246/126057126-daf12185-3a3a-4cb9-b934-bed9dc329692.jpg)
![ggggggg](https://user-images.githubusercontent.com/58392246/126057127-4d033994-be59-449d-a86e-6226328f7c60.jpg)
![r](https://user-images.githubusercontent.com/58392246/126057128-63819f2a-2b94-4d64-a745-817a8f70845b.jpg)
![t](https://user-images.githubusercontent.com/58392246/126057129-d8ebbe75-3761-4d39-a840-b5c452c9b138.jpg)
# cli-cli
cli/cli
GitHub CLI
gh is GitHub on the command line. It brings pull requests, issues, and other GitHub concepts to the terminal next to where you are already working with git and your code.

screenshot of gh pr status

GitHub CLI is available for repositories hosted on GitHub.com and GitHub Enterprise Server 2.20+, and to install on macOS, Windows, and Linux.

Documentation
See the manual for setup and usage instructions.

Contributing
If anything feels off, or if you feel that some functionality is missing, please check out the contributing page. There you will find instructions for sharing your feedback, building the tool locally, and submitting pull requests to the project.

Installation
macOS
gh is available via Homebrew, MacPorts, Conda, and as a downloadable binary from the releases page.

Homebrew
Install:	Upgrade:
brew install gh	brew upgrade gh
MacPorts
Install:	Upgrade:
sudo port install gh	sudo port selfupdate && sudo port upgrade gh
Conda
Install:	Upgrade:
conda install gh --channel conda-forge	conda update gh --channel conda-forge
Additional Conda installation options available on the gh-feedstock page.

Linux
gh is available via Homebrew, Conda, and as downloadable binaries from the releases page.

For more information and distro-specific instructions, see the Linux installation docs.

Windows
gh is available via WinGet, scoop, Chocolatey, Conda, and as downloadable MSI.

WinGet
Install:	Upgrade:
winget install gh	winget upgrade gh
scoop
Install:	Upgrade:
scoop install gh	scoop update gh
Chocolatey
Install:	Upgrade:
choco install gh	choco upgrade gh
Signed MSI
MSI installers are available for download on the releases page.

GitHub Actions
GitHub CLI comes pre-installed in all GitHub-Hosted Runners.

Other platforms
Download packaged binaries from the releases page.

Build from source
See here on how to build GitHub CLI from source.

Comparison with hub
For many years, hub was the unofficial GitHub CLI tool. gh is a new project that helps us explore what an official GitHub CLI tool can look like with a fundamentally different design. While both tools bring GitHub to the terminal, hub behaves as a proxy to git, and gh is a standalone tool. Check out our more detailed explanation to learn more.
