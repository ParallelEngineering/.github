# Contributing Guidelines

## Formating
- Use Spaces instead of Tabs
- Github Actions Formatting on pull requests

## Comments
- Multiline comments with `/* */`
- Comments should be as short as possible and only over several lines if absolutely necessary
- First letter of each comment are upper case

## Branches
- Use Github Flow with aditional `sub-feature` branches
- Specific and proper naming, with this convention `feature/sub-feature`
- Sub-feature branches should have as little as possible commits
- both `main` and `feature` branches are protected and can only be reached by pull requests
```                                       
o main                            
|\                                       
| o feature-a                            
| |                                      
| o                                      
| |\                                     
| | o feature-a-sub                      
| | |                                    
| | |                                    
| | |                                    
| | o merged feature-a into feature-a-sub
| |/                                     
| o feature-a-sub merged into feature-a  
| |                                      
| o feature-a with future work on it     
|/                                       
o merge feature-a into main
```
## Commits
- Debuging features are only allowed in `sub-feature` branches

## Pull Requests
- If a `git squash` is performed, all contributors must be named as [co-authors](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/creating-a-commit-with-multiple-authors)

## Refactors
- Are made after reaching a milestone
