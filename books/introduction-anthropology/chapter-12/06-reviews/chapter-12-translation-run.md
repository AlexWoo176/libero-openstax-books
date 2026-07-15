# Translation Run Report (Provider: gemini-api): Chapter 12

- **Book:** introduction-anthropology
- **Run Time:** 2026-07-15 03:12:52 UTC
- **Provider:** gemini-api
- **Engine/Model:** gemma-4-31b-it
- **Batch Size:** 50
- **Resume Mode:** True
- **Resulting Status:** TRANSLATION_BLOCKED

## Summary Details

| File Name | Status | Blocks | Details / Errors |
|---|---|---|---|
| `12-1-sex-gender-and-sexuality-in-anthropology.html` | SKIPPED | 0 | Already exists, resume mode skips. |
| `12-2-performing-gender-categories.html` | SKIPPED | 0 | Already exists, resume mode skips. |
| `12-4-sexuality-and-queer-anthropology.html` | SKIPPED | 0 | Already exists, resume mode skips. |
| `12-bibliography.html` | SKIPPED | 0 | Already exists, resume mode skips. |
| `12-critical-thinking-questions.html` | SKIPPED | 0 | Already exists, resume mode skips. |
| `12-introduction.html` | SKIPPED | 0 | Already exists, resume mode skips. |
| `12-key-terms.html` | SKIPPED | 0 | Already exists, resume mode skips. |
| `12-summary.html` | SKIPPED | 0 | Already exists, resume mode skips. |
| `12-3-the-power-of-gender-patriarchy-and-matriarchy.html` | FAILED / IN_PROGRESS | 0 | Unrecoverable translation failure on item item-2 (both primary and backup models failed): Max retries exceeded for Gemini API call. Last error: Status 429: {
  "error": {
    "code": 429,
    "message": "You exceeded your current quota, please check your plan and billing details. For more information on this error, head to: https://ai.google.dev/gemini-api/docs/rate-limits. To monitor your current usage, head to: https://ai.dev/rate-limit. \n* Quota exceeded for metric: generativelanguage.googleapis.com/generate_content_free_tier_input_token_count, limit: 16000, model: gemma-4-31b\nPlease retry in 14.389133285s.",
    "status": "RESOURCE_EXHAUSTED",
    "details": [
      {
        "@type": "type.googleapis.com/google.rpc.Help",
        "links": [
          {
            "description": "Learn more about Gemini API quotas",
            "url": "https://ai.google.dev/gemini-api/docs/rate-limits"
          }
        ]
      },
      {
        "@type": "type.googleapis.com/google.rpc.QuotaFailure",
        "violations": [
          {
            "quotaMetric": "generativelanguage.googleapis.com/generate_content_free_tier_input_token_count",
            "quotaId": "GenerateContentInputTokensPerModelPerMinute-FreeTier",
            "quotaDimensions": {
              "location": "global",
              "model": "gemma-4-31b"
            },
            "quotaValue": "16000"
          }
        ]
      },
      {
        "@type": "type.googleapis.com/google.rpc.RetryInfo",
        "retryDelay": "14s"
      }
    ]
  }
}
 |
