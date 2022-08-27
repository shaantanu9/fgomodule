## First Go Module Create to check How to build the module and Publish that on GitHub

### Creating Package is not that hard

- Initiate the Go Module with github url and repository name
- Start Writing the Code.

```Go
package packageNameinSmall

func FunctionName (){
// this function name should be in Capital letter
// as its the way go know and allows us to import export the function.
}

```

- Create the Git repository with same name and description
- Push the code into the repository
-Add the Github Tag

```
git tag "v1.0.0"
git push --tags
```

Done Package is ready to be used by Others