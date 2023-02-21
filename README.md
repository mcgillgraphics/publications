# Lab Publications

## Instructions 
To add a new publication, follow these steps:

1) Clone the [`publications`](https://github.com/mcgillgraphics/publications) repository, or update it if this is not your first time.
1) Duplicate `papers/.2023-author-acronym.md` and rename accordingly with main author's last name and publication acronym. Remove leading `.` to make it visible to Jekyll main build.
2) Modify the file by replacing relevant fields for the new paper. By default, the template have most fields filled to give a sense of what is expected, although most fields are optional.
3) Add hyperlinks to media files on remote servers or in `assets/2023-author-acronym/`. Create subdirectory if necessary.
3) When done, delete unused field data by leaving the tag empty or with a comment symbol (e.g., `file: #`).
4) Push change onto main branch.

If done correctly, an admin will pull your changes into the main website repo and your paper will be automatically formatted and visible at `{{site.url}}/publications/acronym`.
