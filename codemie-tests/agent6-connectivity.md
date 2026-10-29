CodeMie Agent 6 Connectivity Test
This file verifies that Git-DevOps-Publisher-Agent can write and retrieve repository files using GitHub MCP.
Test scope:
Branch creation: verified previously
File creation: under test
File retrieval: under test
Pull request creation: not yet tested
Instructions:
Confirm the target branch exists.
Check whether the file already exists.
Create the file on the test branch if absent.
Read the file back using get_file_contents.
Verify that the retrieved content matches the submitted content.
Return the commit SHA, file path, and verification result.
This is an explicitly authorized connectivity test. Do not modify any other files, create a PR, or merge branches.
