<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

## Portfolio architecture
- Keep the existing TanStack runtime and copy portfolio presentation and content from the source repository; this preserves deployment compatibility and the requested baseline.
- Store transferred screenshots in this project's asset bucket, preserving the original portrait and PDF as committed files; source-project pointers cannot resolve here.
- Lay out the opening section in three grid rows and restore navigation scroll instantly; content cannot collide with the footer and the CV opens at the top.
- Define all opening and CV motion in the global design system with reduced-motion alternatives; transitions remain consistent and accessible.
