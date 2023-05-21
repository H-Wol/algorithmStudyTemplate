# OverView

This project is a template project to help solve various algorithm problems.

## Beakjoon

- Auto commit
- Auto Notion post

### Setup

1. Fork this repository
2. From your new fork, go to Settings > Secrets
3. Add the following secret using the New secret button:
   - **NOTION_TOKEN:** Token for using Notion API
   - **DATABASE_ID:** The database ID of the Notion to record the problem solving.
   - **NOTION_SELF_ID:** The personal ID of the Notion to record the problem solving.
4. Go to the **Actions** tab of your fork and click the "enable" button
5. Check the "Read and write permissions" in Settings > Actions > General > Workflow permissions

### How to Use

#### Auto commit

1. After solving the beakjoon problem, save the code inside the beakjoon folder.
2. Set the file name to the name that contains the problem number.
3. Run "python autoCommit.py"
4. Check the commit history.

#### Auto Notion post

1. After SetUp, this workflow runs only when the push event that commits the file is in the "beakjoon" folder.
2. Check Notion

<img src ="https://raw.githubusercontent.com/H-Wol/algorithmStudyTemplate/main/images/notion_screenshot.png">
