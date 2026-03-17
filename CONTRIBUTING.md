# Contributing

This site accepts blog post contributions through GitHub pull requests.

## Submit a blog post in GitHub

If you are comfortable using GitHub, the easiest route is to open a pull request with a new file in [_posts](./_posts).

1. Open [.github/blog-post-template.md](./.github/blog-post-template.md).
2. Copy the template contents.
3. Create a new branch in GitHub.
4. Add a new file in [_posts](./_posts) named `YYYY-MM-DD-short-title.md`.
5. Paste the template and fill in the details.
6. If your post uses an image, upload it to [images](./images) in the same branch.
7. Open a pull request.

All blog post pull requests are reviewed before merge.

## Blog post requirements

- The file must live in [_posts](./_posts).
- The filename must use the pattern `YYYY-MM-DD-short-title.md`.
- Front matter must include `title`, `author`, and `tags`.
- `author` should match a member slug from [_members](./_members) when possible, for example `gabrielle-davidson`.
- Add an excerpt between `<!-- excerpt start -->` and `<!-- excerpt end -->` so the blog index shows a clean summary.
- If you reference an image in front matter, the image file must be committed to the repository.

## Submit a draft without editing files

If you do not want to edit Markdown directly, or do not feel confident opening a PR, instead, open a GitHub issue using the Blog Post Submission form and provide the text and image there. A maintainer can turn that into a pull request for review.

## Review and merge policy

- Contributors should open pull requests against `main`.
- Pull requests for blog posts are intended for maintainer review.
