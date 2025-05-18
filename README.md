gbraad's Dotfiles `machine` action
==================================

Use dotfiles' `machine`-command to start virtual machines

### Usage

```yaml
      - name: Setup environment
        uses: gbraad-dotfiles/install-action@main
        
      - name: Run machine command
        uses: gbraad-dotfiles/machine-action@main
        with:
          prefix: dotfedora
          command: download   # start, stop, etc
```

Have a look here for an [example workflows](https://github.com/gbraad-dotfiles/actions-test/blob/main/.github/workflows/test-machine.yml).
