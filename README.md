# SE-assignment2 : Learning basic GitHub commands and  Collaborating 
-----------------------------------------------------------------------------------------------------------------------------
# Project Overview : 
I created this repository for my Software Engineering assignment to help learn and understand  basic version control, branching strategies, and collaborative workflows utilizing  Git and GitHub. 
- Programming Language: Python
- Text Editor: Notepad
- Terminal: Git Bash


By using a simple text editor and the command line, I maintained full control over the git lifecycle, focusing on print statement iterations and branch merging.

# What are things to accomplished : 
- Repository Management: Initialized and configured a local Git environment through the git terminal.

- Branching Strategy: Managed three branches (Master, feature-1, and feature-2) to isolate development

- Pull Requests: Integrated code into the Master branch through Pull request and review processes

- Conflict Resolution: Identified and resolved a manual merge conflict in World.py during the integration of feature-2 into Master 

# Issue #1: Initial Script Creation
Description:Establish the baseline `World.py` file in the repository.
Resolution:Created the script on the `Master` branch and performed the initial commit to set the project foundation.

# Issue #2: Syntax Error Debugging
Description:During the development of `feature-2`, the script failed with a `SyntaxError: unterminated string literal`.
Resolution:Identified a missing closing quotation mark in the print statement via Git Bash. The code was corrected, tested locally, and committed.

# Issue #3: Merge Conflict Resolution & Collaboration
Description:Divergent changes between `Master` and `feature-2` caused a `(Master|MERGING)` conflict.
Resolution:Manually edited `World.py` to remove conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`). My contributor then reviewed the Pull Request and finalized the merge into the `Master` branch.

# Code Evolution:
1. Initial State: Basic "Hello, World" output.
2. Feature-1: Added an additional printout statement:
   `print("This is to test out a new Feature")`
3. Feature-2: Finalized the code with the updated statement:
   `print("This is to test out a new Feature-2")`

# Installation & Setup

To run this project locally:

1. Clone the repository:
git clone https://github.com/github username /SE-assignment2.git

2. Navigate to the directory:
cd SE-assignment2

3. Run the script:
python World.py


# Contributors
* Peace Amichoh - Peacefri
*  Noel - nmeko
