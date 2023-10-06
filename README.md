NvChad
Home • Install • Contribute • Support • Features

Neovim Minimum Version GitHub Issues Discord Matrix Telegram
Showcase

What is it?

    NvChad is a neovim config written in lua aiming to provide a base configuration with very beautiful UI and blazing fast startuptime (around 0.02 secs ~ 0.07 secs). We tweak UI plugins such as telescope, nvim-tree, bufferline etc well to provide an aesthetic UI experience.

    Lazy loading is done 93% of the time meaning that plugins will not be loaded by default, they will be loaded only when required also at specific commands, events etc. This lowers the startuptime and it was like 0.07~ secs tested on an old pentium machine 1.4ghz + 4gb ram & HDD.

    NvChad isn't a framework! It's supposed to be used as a "base" config, so users can tweak the defaults well, and also remove the things they don't like in the default config and build their config on top of it. Users can tweak the entire default config while staying in their custom config (lua/custom dir). This is the control center of the user's config and gitignored so the users can stay up-to-date with NvChad's latest config (main branch) while still controlling it with their chadrc (file that controls entire custom dir).

Theme Showcase
Images (Click to expand!)
UI related plugins used
Images (Click to expand!)
Plugins list

    Many beautiful themes, theme toggler by our base46 plugin
    Inbuilt terminal toggling & management with Nvterm
    Lightweight & performant ui plugin with NvChad UI It provides statusline modules, tabufline ( tabs + buffer manager) , beautiful cheatsheets, NvChad updater, hide & unhide terminal buffers, theme switcher and much more!
    File navigation with nvim-tree.lua
    Beautiful and configurable icons with nvim-web-devicons
    Git diffs and more with gitsigns.nvim
    NeoVim Lsp configuration with nvim-lspconfig and mason.nvim
    Autocompletion with nvim-cmp
    File searching, previewing image and text files and more with telescope.nvim.
    Syntax highlighting with nvim-treesitter
    Autoclosing braces and html tags with nvim-autopairs
    Indentlines with indent-blankline.nvim
    Useful snippets with friendly snippets + LuaSnip.
    Popup mappings keysheet whichkey.nvim

History

    I (@siduck i.e creator of NvChad) in my initial days of learning to program wanted a lightweight IDE for writing code, I had a very low end system which was like 1.4ghz pentium + 4gb ram & HDD. I was into web dev stuff so many suggested me to use vscode but that thing was very heavy on my system, It took more ram than my browser! ( minimal ungoogled chromium ) so I never tried it again, sublime text was nice but the fear of using proprietary software XD for a linux user bugged me a lot. Then I tried doom-emacs which looked pretty but it was slow and I was lost within its docs, I tried lunarvim but too lazy to read the docs. Doom-emacs and lunarvim inspired me to make a config which is the prettiest + very fast and simple.

    I'm decent at ricing i.e customizing system and making it look pretty so I posted my neovim rice on neovim subreddit, my neovim-dotfiles github repo blew up and then I had to come up with a name, I was amazed by the chad meme lol so I put NvChad as the name, the chad word in here doesnt literally mean the chad guy but in the sense such as chad linux vs windows i.e meaning superior, best etc. NvChad was made for my personal use but it gained some popularity which inspired me to make a public config i.e config usable by many and less hassle to update as everyone's going to use the same base config (NvChad) with their custom modifications (which are gitignored so that wont mess up), without the custom config stuff users would have to keep a track of every commit and copy paste git diffs to manually update nvchad.

💝 Support

If you like NvChad and would like to support & appreciate it via donation then I'll gladly accept it.

kofi paypal buymeacoffee patreon
Credits

    Elianiva helped me with NeoVim Lua related issues many times, NvChad wouldn't exist without his help at all as he helped me in my initial neovim journey!
    @lorvethe for making the beautiful NvChad logo.
