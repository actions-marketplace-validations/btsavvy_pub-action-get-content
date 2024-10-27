# pub-action-get-content
"This action fetches the content of the specified repository. The inputs are:

owner: The owner of the repository (required).

repo_name: The name of the repository (required).

branch_name: The branch name of the repository (required).

path_name: The path name (required).

placeholder_attributes: A list of attributes in the files to substitute, entered as ATTRIBUTE=VALUE or ATTRIBUTE:VALUE for {{{ATTRIBUTE}}}. Use commas to separate multiple attributes (optional).

token: The GitHub app token (required).

Output: The content is downloaded to the current directory.