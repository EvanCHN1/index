This repository teaches you step by step how to save your local obsidian vault on Github and generate a website using Netlify to share your ideas with the world.

How to make a website like this？

1. Create a new folder on your local device, then use Obsidian to make it a new vault
2. Create an index.md file in this vault
3. We need to add 2 community plugins to this Vault:
	- Webpage HTML Export
	- Git
4. Use Webpage HTML Export plugin to export the index.md file to an index.html file
5. Drag and drop the index.html file to Netlify and deploy , then you will get a [[URL]]
6. Use Github Desktop to upload the index.html folder to Github as a repo
7. In Netlify fill in the repo's url to connect with Github(this step could be before step 6)
8. In the Git plugin setting the repo's url to connect this Obsidian vault to Github
9. Now in Obsidian edit index.md and do step 4 again
10. Click Sync Remote button in the Plugin Ribbon (or use Github Desktop to push)