# nixos-meta
 
Some meta information for NixOS work

<a href="https://flattr.com/submit/auto?fid=01v5oy&url=https%3A%2F%2Fgithub.com%2Fsheenobu%2Fnixos-meta%2F" target="_blank"><img width="90px" src="https://button.flattr.com/flattr-badge-large.png" alt="Flattr this" title="Flattr this" border="0"></a>
<br/>
<a href="https://liberapay.com/sheenobu/donate"><img width="90px" src="https://liberapay.com/assets/widgets/donate.svg">

## Management
 
 * [Trello - NixOS](https://trello.com/b/oW6JbCi6)

## Code

 * [NixOS configurations](https://github.com/sheenobu/rcfiles/tree/master/nixos)
 * [NixOS shortcuts](https://github.com/sheenobu/rcfiles/tree/master/bashrc/os/nix)

## Blog

 * [NixOS Recipes: ELK Stack](https://sheenobu.net/nixos-recipes/elk.html)
 * [NixOS Recipes: vscode backport to 16.03](https://sheenobu.net/nixos-recipes/vscode.html)

## Useful commands

Building/testing a package:

    nix-build -I folder-containing-nixpkgs '<nixpkgs>' -A packageExpression

Installing a custom package:

    nix-env -f nixpkgs/ ...
