# Install
Before installation, be sure to have tmux-themepack installed:

    $ git clone https://github.com/jimeh/tmux-themepack.git ~/.tmux-themepack

And powerline fonts installed:

    $ sudo apt install fonts-powerline

Then copy paste the configuration:

    $ cp tmux.conf ~/.tmux.conf

# Usage
I'm actually using tmux with gnome-therminal/mate-terminal. Add the following
startup command:

    tmux attach

The terminal will start with the currently running tmux session.
