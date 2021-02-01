# redash
# Deploy redash into new host
# Will try to dump & restore actual database from main redash host
# In role affected: redash/defaults/main.yml(encrypted) redash/tasks/main.yml redash/templates/ redash/files/
# ansible-playbook -i hosts play_redash.yml --ask-vault-pass
# --tags "update_db" (Only updates current database from main Redash host, local data will be lost)
