# dhcpd.conf-generator

instructions:


1. generate a CSV file (follow vars.cvs convention)

2. convert into yaml:    "python csv_to_yaml.py vars.csv"

3. change "vars.csv.yml" name to "all.yml"

4. copy "all.yml" into /group_vars

5. run playbook:     ansible-playbook generate_dhcpd.yaml
