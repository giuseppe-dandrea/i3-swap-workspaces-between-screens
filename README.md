# i3 swap workspaces between screens

## About
Simple script that swaps the workspaces between 2 screens. It technically rotates the workspace to the right, so in a 3 or more monitor setup, it will have a different behaviour.

## Dependencies
1. i3ipc-python <https://github.com/acrisci/i3ipc-python>

## Installation
1. Clone the repo
2. Install i3ipc-python: `pip install i3ipc`
3. Add to your i3 config: `bindsym $mod+Shift+s exec /parent/path/i3-swap-workspace-between-screens.py`
4. Reload i3