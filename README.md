Bash Grader
Overview
The Bash Grader project is a CSV file manager and interpreter designed using Bash scripting to handle student examination records. It combines several functionalities, including file management, grade calculation, version control (Git-like features), and statistical analysis of student performance.

Features
CSV File Management: The script allows the combining, updating, and calculating total marks for students from multiple CSV files.
Git-like Version Control: The script includes a version control system with commands such as git_init, git_commit, git_checkout, git_branch, and git_log to manage different versions of the project.

Statistical Analysis: Displays statistics like mean, median, and standard deviation for exam results, with optional graphical visualizations.
Error Handling: Provides robust error-checking and friendly messages for invalid commands, missing files, and incorrect inputs.

Functionality
combine: Merges multiple CSV files (containing student data) into one main CSV file.
upload: Uploads new CSV files into the project directory.
total: Adds a column for total marks to the main CSV file by summing up marks from individual exams.
update: Updates the marks of individual students in the CSV files.
stats: Displays statistical information (e.g., mean, median, standard deviation) for the exams. Optionally, generates graphs using Python scripts.
Git-Like Commands: Version control commands include:
git_init: Initializes a remote directory for version tracking.
git_commit: Commits current changes to the remote directory.
git_checkout: Reverts to a previous version using commit hash or message.
git_branch: Creates branches at specific commits.
git_log: Displays commit history.

Command Help: Displays available commands with descriptions.

Usage
Run the Bash script submission.sh using the following commands:

Combine CSV Files:
bash
bash submission.sh combine

Upload New CSV Files:
bash
bash submission.sh upload <file_path>

Calculate Total Marks:
bash submission.sh total

Update Student Marks:
bash submission.sh update

Display Statistics:
bash submission.sh stats

Git-like Commands:
Initialize the version control system:
bash submission.sh git_init <remote_repo_path>

Commit changes:
bash submission.sh git_commit -m "commit_message"

Checkout to a previous commit:
bash submission.sh git_checkout <commit_hash>

View commit log:
bash submission.sh git_log

Error Handling
The script provides user-friendly error messages for:
