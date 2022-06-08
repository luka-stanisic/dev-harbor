### To run site locally:
`hugo server`

### Publish website:
#### Commit all changes you have onto "main" branch
### Build site for publish (creates the public folder changes):
`hugo`
##### Switch to the "gh-pages" branch
`git checkout gh-pages`
#### Commit changes in "public" folder to gh-pages branch

---
##### FYI: checkout the specific file you wish to add to the gh-pages branch
`git checkout master -- <path/to/file/folders/on/master/branch>`

##### Commit and push