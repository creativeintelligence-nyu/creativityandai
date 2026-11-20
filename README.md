# Creativity and AI: course website

A [Just the Docs](https://github.com/just-the-docs/just-the-docs) site for *Creativity and Artificial Intelligence* (EDCT-UE 1042, NYU ALT/ECT, Spring 2026).

## Publish on GitHub Pages

1. Create a GitHub repository and push the contents of this folder to it.
2. In the repository, go to **Settings > Pages**, choose **Deploy from a branch**, and select `main` and `/ (root)`.
3. If the site lives at `https://<user>.github.io/<repo>`, set `baseurl: "/<repo>"` in `_config.yml`.

## Preview locally

```
bundle install
bundle exec jekyll serve
```

## Structure

- `index.md`: home
- `schedule.md`: weekly schedule and key deadlines
- `weeks/`: one page per week (`week-01.md` to `week-14.md`)
- `assignments.md`: assignments, project milestones, reading reflections
- `course-info.md`: expectations, grading, outcomes, evaluation criteria
- `policies.md`: academic integrity, accessibility, privacy, wellness
- `resources.md`: technology requirements, support, logistics

Internal links use Jekyll's `link` tag, so a broken internal link fails the build.
