Encrypting files 
----------------

|     Comments  | Command | 
|    :---:     |     :---:   |
| Create Encrypted File  | $ ansible-vault create file.yaml |
| Edit Encrypted File   | $ ansible-vault edit file.txt | 
| View Encrypted File  | $ ansible-vault view filename.yml | 
| Rekey Password  | $ ansible-vault rekey filename.txt |
| Encrypt Unencrypted File | $ ansible-vault encrypt filename.txt |
| Decrypt Encrypted File | $ ansible-vault decrypt filename.txt |
| Decrypt Encrypted File | $ ansible-vault decrypt filename.txt |
| Encrypt string   | $ ansible-vault encrypt_string 'string' --name 'variable_name' |
| Decrypting Encrypted File During Ansible Runtime  | $ ansible-playbook launch.yml --ask-vault-pass | 
