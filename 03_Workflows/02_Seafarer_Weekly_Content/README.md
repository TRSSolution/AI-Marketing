# TeamSeafarers Weekly Seafarer Content Workflow

## Purpose

Generate reviewed weekly marketing content for Indian seafarers, create a realistic branded image, and create a Buffer draft.

## Source of Truth

The active workflow runs in local n8n.

`workflow.json` is the latest exported, reviewed and tested workflow backup.

## Workflow Audience

- Indian seafarers
- Maritime professionals
- Maritime students
- Maritime course seekers

This workflow is not for maritime institute marketing.

## Workflow Stages

Marketing Strategist
→ Topic Generator
→ Content Writer
→ Content Reviewer
→ SEO Analyst
→ Image Designer
→ Analytics Manager
→ Publisher
→ OpenAI Image Generation
→ Cloudinary Branding
→ Buffer Draft

## Verified URLs

- Website: https://teamseafarers.com/
- Android app: https://play.google.com/store/apps/details?id=com.teamseafarers.app&pcampaignid=web_share
- Contact: https://teamseafarers.com/contact-us

## Security

Never commit:

- API keys
- Access tokens
- Passwords
- Authentication headers
- Bearer tokens
- Credential secrets

Credential names and n8n credential references may remain in the workflow export.

## Change Process

1. Make changes in n8n.
2. Test one topic.
3. Export the successful workflow.
4. Replace `workflow.json`.
5. Review the Git diff.
6. Commit and push.