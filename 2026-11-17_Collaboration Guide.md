# Working together on the SYD website

The published GitHub Pages preview comes from `main`. Treat that branch as the shared review version and avoid editing it directly.

## Propose a content change

1. Start from the latest `main` and create a descriptive working branch.
2. Edit `Version 4/2026-11-06_SYD Website.html` and include any assets needed by the change. Keep the existing filenames and paths unless a rename has been approved.
3. Commit the change with a clear description and open a pull request against `main`.
4. Review the proposed changes together. Merge only when the changes are ready to appear in the public preview.

The `collaboration` branch is a starting point for the workflow; create a separate branch for each proposed change. Coordinate edits to the same content to reduce conflicts. Git history records changes and can be used to recover earlier content.

## Preview and privacy

The current GitHub Pages site is public. A branch does not automatically have its own website preview. To review visually before merging, open the branch's files locally with their assets or arrange a separate preview. Check the published page after merging.

The HubSpot form is an external embed. Its display and submission behavior should be checked in the published environment; avoid submitting real personal data as a test without agreement. The chat remains a preview until its integration is supplied.

The site currently stores content, styles, and behavior in the HTML file. Keep edits focused and preserve existing snapshots. Ask before renaming or removing files.