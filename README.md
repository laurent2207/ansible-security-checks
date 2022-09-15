# ansible-security-checks

Yaml file to be used with Ansible, for multiple hosts simultaniously. 
Includes some basic linux commands to do some security checks:

- Check if there are no users with an empty passwd
- Make sure non-root accounts do not have an uid of 0
- Make sure non-root accounts do not have an gid of 0
- Verify ownership of /etc/shadow, /etc/passwd, /etc/group, /etc/fstab
- Verify permissions of /etc/shadow, /etc/passwd, /etc/group, /etc/fstab
- Check for world writable directories
- Check for files with no owner
