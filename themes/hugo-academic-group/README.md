# MMCAL
An academic group website theme for Hugo.
https://pkummcal.github.io/

## Installation
1. Install [Hugo](https://gohugo.io/).
2. Navigate to the root directory of your website and run the Hugo server:
```bash
hugo server --watch
```
Then, open [localhost:1313](localhost:1313) in your browser, and you should be able to view your website.

## Modification Guide
**Note**: Modifying files within the `/public` directory is ineffective. Once you redeploy the website using the `hugo` command, all content in this directory will be updated.

### /content Directory
This directory primarily stores textual content.
```
/member: Each student's personal information, including portrait, name, and research interests, will be automatically updated on the laboratory homepage.
/post: Content for the News section.
/publications: Content for the Publications section.
about.md & joinus.md: Correspond to the "About" and "Join us" sections in the navigation bar respectively.
patent-standardization.md: Located under the "Patent & Standardization" item in the Publications section of the navigation bar.
codes.md, /datasets.md, /approach.md: These files are now deprecated.
```

### /themes/hugo-academic-groups Directory
```
/archetypes & /exampleSite: These contain the original template content. It is recommended not to modify them.
/layout/partials/index: Controls the specific content of the page. The content corresponding to the "News" section on the homepage is defined in the post.html file.
Other directories generally do not require modification.
``` 