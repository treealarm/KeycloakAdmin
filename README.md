# KeycloakAdmin

## Releasing

A push to `main` only builds. To publish to nuget.org, bump `<Version>` in
`KeycloakAdmin.csproj`, commit, and push a tag naming it:

```bash
git tag v1.1.1 && git push origin v1.1.1
```

The release fails if the tag and `<Version>` disagree, or if that version is already on
nuget.org.
