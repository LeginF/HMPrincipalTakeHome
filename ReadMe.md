# Principal Take Home

This is a single-page web application to search GitHub by topic. The user provides a GitHub [authentication token](https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/creating-a-personal-access-token) and topic to search for.  

Once the user clicks the Search button, the application queries GitHub for projects matching the search criteria and provides a list of projects, a description, tags associated with the project, and contributors to the project. A contributor can be clicked to visit their GitHub page.

## Requirements

- [.Net 5.0](https://dotnet.microsoft.com/download/dotnet/5.0)

## Running

1. From the project root directory (where SLN file resides), run:
`
dotnet run
`
1. Open a browser to https://localhost:5000

## Testing

TBD
