# Blogs for SRE Mastery
Site Reliability Engineering (SRE) Mastery blogs source-code.

Learn how to be a master in SRE and get into any SRE/Devops role easily.

### Instructions
- `src/posts` folder contains all the posts.
- `src/_data` folder contains hardcoded data.
- `src/static` folder contains all static (img, css, js files).

### How to create a new post
- Make sure to create folder in `src/posts` folder with proper naming.
- Inside the folder an `index.md` file should be there as it represents the root file.
- Every markdown file should have this on top.
  ```markdown
  ---
  title: Title of the article
  description: Description of the article
  date: 2025-01-30T15:13:13.021Z (Time in ISO 8601 format).
  author: Author Name
  tags: tag1, tag2
  poster: '/static/img/poster/aks.png' (Poster image)
  layout: posts
  ---
  ```
- Make a PR request, and will be reviewed & merged by the owner.