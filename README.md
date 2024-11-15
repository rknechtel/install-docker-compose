# Install Docker Compose

GitHub Action which allows you install Docker Compose.

## Input variables

The required variables for it to work can be appreciated next.

| Variable | Descritpion | Example |
| -------- | ----------- | ------- |
| `dockercompose_version` | The version of Docker Compose to use | [v2.30.3]() |


## Usage

```yaml
- uses: rknechtel/installdockercompose@v1
  with:
    # Docker Compose Version
    dockercompose_version: v2.30.3   
```
