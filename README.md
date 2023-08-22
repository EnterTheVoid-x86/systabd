# systabd
Systabd is a bash script that allows you to replace getty with another program/script on a specific tty, kinda like /etc/inittab.

## Install
Download the repo with git clone, and install:

``./install``

## Usage

``sudo inittab tty_to_replace replacement_program``

### Example:

``sudo inittab tty5 htop``
