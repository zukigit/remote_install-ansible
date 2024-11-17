## How to install jobarranger server
` $ ansible-playbook install_jobarg_server.yml -i ../hosts.ini --extra-vars "rpm_el9=YOUR_EL9_RPM_FILE_PATH"`

## How to install jobarranger agent
` $ ansible-playbook install_jobarg_agent.yml -i ../hosts.ini --extra-vars "rpm_el9=YOUR_EL9_RPM_FILE_PATH"`

## How to install jobarranger manager
` $ ansible-playbook install_jobarg_manager.yml -i ../hosts.ini --extra-vars "rpm_el9=YOUR_EL9_RPM_FILE_PATH"`

## Variables
- **rpm_el9**: Redhat 9 rpm filepath.
- **rpm_el8**: Redhat 8 rpm filepath.
- **rpm_el7**: Redhat 7 rpm filepath.
- **rpm_el6**: Redhat 6 rpm filepath.