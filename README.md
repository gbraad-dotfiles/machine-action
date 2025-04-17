Dotfiles machine-action
=======================


Use dotfiles' `machine`-command to start virtual machines

```yaml
      - name: Setup environment
        uses: gbraad-dotfiles/install-action@main
        
      - name: Run machine command
        uses: gbraad-dotfiles/machine-action@main
        with:
          prefix: dotfedora
          command: download   # start, stop, etc
```
