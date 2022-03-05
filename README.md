# Golden-Boy-Productions

## Operational Notes

### Local Development

Install dependencies:

```bash
pnpm install
```

| COMMAND                  | DESCRIPTION                                       |
|:-------------------------|:--------------------------------------------------|
| `pnpm run dev`           | Run the site locally                              |
| `pnpm run img`           | Convert all JPG images to Avif and WebP           |
| `pnpm run lint`          | Check for linting errors                          |
| `pnpm run lint -- --fix` | Attempt to fix linting errors                     |


### Deployment

Deploys automatically to Netlify on push to `main` branch.

![Status](https://api.netlify.com/api/v1/badges/df5ae10d-632d-44ed-a0ce-03184d814493/deploy-status)
