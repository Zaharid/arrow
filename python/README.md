<!---
  Licensed under the Apache License, Version 2.0 (the "License");
  you may not use this file except in compliance with the License.
  You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License. See accompanying LICENSE file.
-->

## Python library for Apache Arrow

This library provides a Pythonic API wrapper for the reference Arrow C++
implementation, along with tools for interoperability with pandas, NumPy, and
other traditional Python scientific computing packages.

## Installing

Across platforms, you can install a recent version of pyarrow with the conda
package manager:

```shell
conda install pyarrow -c conda-forge
```

On Linux, you can also install binary wheels from PyPI with pip:

```shell
pip install pyarrow
```

### Development details

See the [Development][2] page in the documentation.

### Building the documentation

```bash
pip install -r doc/requirements.txt
python setup.py build_sphinx -s doc/source
```

[1]: https://github.com/apache/parquet-cpp
[2]: https://github.com/apache/arrow/blob/master/python/doc/source/development.rst