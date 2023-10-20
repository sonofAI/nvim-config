customization for nvchad.

nvim --version > 0.8
```
rm -rf ~/.local/share/nvim/
rm -rf ~/.config/nvim/
git clone https://github.com/NvChad/NvChad ~/.config/nvim --depth 1
rm -rf ~/.config/nvim/
git clone https://github.com/sonofAI/nvim-config.git
cd nvim-config
rm -rf ~/.config/nvim/
cp * ~/.config/nvim/
```
uncomment lines 15-18 in `lua/plugins/init.lua` to enable codeium - free copilot alternative.
