# ai-product-site

## API Test (Hoppscotch) — GET + JSON Interpretation

**Tool:** Hoppscotch (REST)  
**Method:** GET  
**Endpoint:** https://api.github.com/repos/raveenamishra-prod/ai-product-site  
**Result:** 200 OK (JSON response)

### Screenshots
- screenshots/hoppscotch-200.png (GET + URL + 200 OK)
- screenshots/hoppscotch-json.png (JSON response body)

### Key JSON Fields (Interpretation)
- **id (1131125808):** GitHub’s internal numeric ID for the repository.
- **node_id (R_kgDOQ2ucMA):** Global GraphQL identifier for the repository.
- **name (ai-product-site):** Repository name.
- **full_name (raveenamishra-prod/ai-product-site):** Unique repo identifier = owner + repo.
- **private (false):** Repo visibility (public).
- **owner.login (raveenamishra-prod):** The GitHub account that owns the repo.
- **html_url:** Browser link to open the repo on GitHub.
- **description (null):** Repo description is not set yet (can be added in GitHub “About”).
- **url:** API URL for this repository (the endpoint used for programmatic access).
- **fork (false):** Repo is original, not forked from another repo.

> Optional (recommended): also mention `created_at`, `updated_at`, `default_branch`, and `homepage` (if present) by scrolling further in the JSON.
