# Knowledge-Vault
Track, organize, and save obtained knowledge with ease! A terminal-based, interactive, CLI toolset that automates the information you choose to save to have quick and easy access to it  by just typing a few simple commands. Loaded with personalization options and a beginner-friendly approach for max efficiency while using the command line.  

## Current State
The knowledge-Vault is currently being developed, and so far, it is only the bare minimum. Below is a list of the features it contains at this very moment.

1. Automates a log entry preformatted with a simple, yet professional structure on demand.
2. Automatically recognizes and stores tags and links them to the file
3. Comes stocked with a set of curated custom commands and aliases for certain ones.
4. Adds a timestamp to each entry title.
5. Comes with a project folder for making new directories for different projects
6. Cleans and rebuilds the entry log and tags log with one command
7. Groups related files automatically by recognizing keywords between files and linking them together.

## The Foundation 
The main folder is called Vault (with a capitol V.)  Inside of the Vault folder, there is 3 folders and 3 files which all of them are nessecarey for the Knowledge-Vault to fuction correctly. Here is how theses apps stack up and what each one does:

  #### The Knowledge-Vault
  - **Vault:** The main folder that contains everything but the the main script.
    #### Sub-Directories
    - **Entries:** This is where the quick entries are automatically save to.
    - **Tags:** A tag file is made for every tag that lists each Entry with that tag in it here.
    - **Projects:** A directory for subdirectories to keep certain info categorized. (in testing mode.)
    #### System Files
    - **entrytemplate.txt:** The template that the script copys and pastes to each new entry.
    - **index.txt:** The file that each entry gets logged in and allows for searching for entries.
    - **namingrules.txt:** This file is just a reminder for the format which files get named.

## Commands
___________________________________
**COMMAND**|**ALIAS**|**PURPOSE**
___________________________________
- fresh|f|create new entry
- tags|t|browse tags
- c-log|(none)|list entries
- key-lookup|key|search by keyword
- del-tag|x|delete tag
- tag|T|show entries under a tag
- tag-cleanup|(none)|clean tag files
- cure|c|edit entry
- rid|d|delete entry
- ch-name|(none)|rename entry
- date-lookup|d^|lookup by date
- stats|s|show stats
- recent|(none)|recent entries
- up-index|(none)|rebuild index
- up-tag|(none)|rebuild tag files
- tweak-up|do|run all maintenance
- help|(none)|help

