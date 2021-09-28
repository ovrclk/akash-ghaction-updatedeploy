# Update Akash Deploy

Updates an existing deployment on Akash, using the DSEQ and `deploy.yml` file that is specified.

## Inputs

### `AKASH_DSEQ`

**Required** akash deployment sequence

### `AKASH_PROVIDER`

**Required** the provider address to target

### `SDL_PATH`

**Optional** The path of the SDL file to send to the provider

## Example usage

```yaml
- name: Akash on Github Actions Update Deploy
  uses: ovrclk/akash-ghaction-updatedeploy
  with:
    AKASH_DSEQ: 12345
    AKASH_PROVIDER: akash1234
    SDL_PATH: deploy.yml
```
