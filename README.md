# Hooks for `pre-commit`

> This repository is a collection of hooks for use with [pre-commit](https://pre-commit.com).

## Table of Contents

- [Requirements](#requirements)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Author Information](#author-information)
- [License](#license)

## Requirements

This repository requires `pre-commit` version `1.15` or newer.

## Dependencies

This repository provides a number of different hooks, all with their own dependencies.

- `standard` requires the [standard](https://standardjs.com/index.html#install) package to be (globally) installed

## Usage

The hooks in this repository can be used by adding the following stub to your `.pre-commit-config.yaml` file:

```yaml
  -
    repo: https://github.com/operatehappy/pre-commit-hooks
    rev: 1.0.0
    hooks:
      - id: standard
```

For a full list of hooks supported by this repository, see [.pre-commit-hooks.yaml](https://github.com/operatehappy/pre-commit-hooks/blob/master/.pre-commit-hooks-yaml)

## Author Information

This repository is maintained by the contributors listed on [GitHub](https://github.com/operatehappy/loop-and-crash/graphs/contributors)

Development of this module was sponsored by [Operate Happy](https://github.com/operatehappy).

## License

Licensed under the Apache License, Version 2.0 (the "License").

You may obtain a copy of the License at [apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an _"AS IS"_ basis, without WARRANTIES or conditions of any kind, either express or implied.

See the License for the specific language governing permissions and limitations under the License.
