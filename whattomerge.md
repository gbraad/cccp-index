# Pull Requests Merge Guide
This document outlines the things to lookout for before merging any PRs to this index

## Primary Lookout Points

 1. Ensure that the sender of the PR has not been blacklisted
 2. The PR must only modify the cccp index.yaml file, unless it is from the maintainers of the index.
 3. The PR must come from a maintainer of a project looking out to be on the index or someone authorized / trusted by the maintainer(s) of the project such as having their PRs getting merged upstream.
 4. The project must be ready to have their code be visible, and must be legally distributable in the US.
 5. The change must not destroy existing entries in the index which are not of concern to the requester of the PR.
 6. A cccp.yml file must be present, and should have appropriate entries in it, especially the job id, which should match across, the index and cccp.yml.
 7. The entries in the cccp.yml and the index must be properly formatted and checked for errors, such as
  * mismatched job-id
  * mismatched git-url, git-branch and git-path.
  * Listed scripts such as test scripts being non-existent.

## What to do if there are errors in the PR

 1. Inform the sender of the PR about the exact errors.
 2. Give the sender enough time to act on these comments before closing the PR.
