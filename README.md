# Ansible-URI-module-example</br>
## Specific host conditions
  1. Print task on specific host usin `when` variable.
  
  2. Run task on specific host and print it using `delegate_to` module and `when` variable.</br>

## Why not using delegate_to alone?
  If you use `delegate_to` module alone, it will run the task in specified host but if you print it without using `when` variable, it will run on all hosts. This is
  because the print task is seperate and will run on all hosts unless specified.
