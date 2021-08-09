
# Get all plugins available

ansible-doc -t lookup -l

#Samples

    env
    url
    file
    ini
    password
    random_choice
    indexed_items
    lines
    pipe
    fileglob
    first_found
    sequence
    vars

# Call a plugin

  vars:
    file_contents: "{{lookup('file', 'file.txt', wantlist=True)}}"


