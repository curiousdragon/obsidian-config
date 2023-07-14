# obsidian-config

The `.obsidian` folder you would find in an Obsidian vault,
with some of my preferred configs.

## Setup

While keeping a copy of the existing `.obsidian` folder:

```bash
# Navigate to your vault folder
cd /path/to/your/obsidian/vault
# Keep a copy of your existing .obsidian folder just in case
cp -r .obsidian previous_obsidian_configs
# Clone this repo as the new .obsidian for your vault
git clone https://github.com/curiousdragon/obsidian-config.git .obsidian
```

*Without* making a copy of the existing`.obsidian` folder:

```bash
# Navigate to your vault folder
cd /path/to/your/obsidian/vault
# Delete the previous .obsidian folder
rm -r .obsidian
# Clone this repo as the new .obsidian for your vault
git clone https://github.com/curiousdragon/obsidian-config.git .obsidian
```
