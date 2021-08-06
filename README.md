# mock
Mock is a charming repository collecting mock pages that the Curriculum team uses in their projects.
These mock pages are usually pages we link to in our project code, so they're nicely-styled, user-facing pages on a topic.

## how to use mock
### linking to existing pages
Before adding your own page, take a look around - maybe we already have what you need.
The base URL `https://mock.getmimo.com/` links to an "under construction" page. 
This is a frequent-usecase page that we add to our Mimo projects whenever we want users to link to something in their code, but we don't want to bother making custom pages.
To access a page in a directory, compose the URL as it follows:
- presuming your page is in the `temp` directory and is called `mypage.html`
- your URL will be `https://mock.getmimo.com/temp/mypage` where `https://mock.getmimo.com/` is the base, `temp` the directory, and `mypage` that specific .html document
- paste this URL in your project code, for example as an `href` attribute value: `href="https://mock.getmimo.com/temp/mypage"`
- click on it to check if it works, just in case

## adding new pages and/or folders
If you need a custom page for your project, you can either:
- add it into one of the existing directories, which means your page will be available at `https://mock.getmimo.com/some-existing-directory/mypage`
- create a new directory and add it there, which means your page will be available at `https://mock.getmimo.com/new-directory/mypage`

To add a file in a new directory, follow these steps:
- go to the repository's `Code` tab (where you can see the repo's file structure)
- on the top right of the file structure, there should be an `Add Code` button
- choose an option like `Create new file`
- on top of the new file window, you'll see a field where you can write your new file's name
- before writing the name, start writing a directory name, so that the path shown resembles `mock/your-directory-name/your-file-name.html`
- paste your code in the text editor below and commit changes
