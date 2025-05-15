A package that bundles aicm with pirate-coding as a dependency.

## Usage

create a config file `aicm.json`

```json
{
  "ides": ["cursor"],
  "presets": ["pirate-coding"]
}
```

Run the following command

```bash
npx aicm-wrapper-cli-test
```

Expected results, aicm will be able to pick up the pirate-coding package from the dependencies
