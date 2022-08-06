
# Install the prerequisite applications, powertools and libmodplug

- https://github.com/computate-org/computate_powertools
- https://github.com/computate-org/computate_libmodplug

# Install the wxwidgets ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_wxwidgets

# Clone the wxwidgets ansible role. 
git clone git@github.com:computate-org/computate_wxwidgets.git ~/.ansible/roles/computate.computate_wxwidgets

# Change into the wxwidgets ansible role directory. 
cd ~/.ansible/roles/computate.computate_wxwidgets
```

# Run the wxwidgets ansible playbook to install wxwidgets locally. 

```bash
ansible-playbook install.yml
```

Christopher Tate
