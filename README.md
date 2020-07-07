# Transfused

A friendly and inclusive fork of [this](https://gitlab.com/cscs/transfuse) small script to backup, compress, and restore your plasma desktop user configurations

### Download:

```shell
git clone https://github.com/kurobeats/transfused.git
```
### Enter the directory:

```shell
cd transfuse
```

### Mark Executable:

```shell
chmod +x transfused
```

### How to use:

```shell
######################################################################
#                                                                    #
#   TRANSFUSE - a Script to Backup and Restore Plasma User Configs   #
#                                                                    #
#   transfused [option] [USER/PATIENT]                             #
#                                                                    #
#   options:                                                         #
#   help, -h, --help                               show brief help   #
#   backup, -b, --backup USER                  backup USER configs   #
#   backuproot, -BR, --backuproot              backup root configs   #
#   copy, -C, --copy USER                 copy but do not compress   #
#   compress, -c, --compress               compress copied configs   #
#   pkglists, -p, --pkglists     create list of installed packages** #
#   pkgrestore, -pr, --pkgrestore         reinstall from a pkglist** #
#   restore, -r, --restore PATIENT    restore configs /to/ PATIENT   #
#                                                                    #
#                            **NOTES**                               #
#  pkg* options depnd on pacman package manager                      #
#  CHARTS=1 environment variable will provide more verbose output    #
#                                                                    #
######################################################################

Example usage:

./transfused -b manjaroo
```
