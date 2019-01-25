<!--
#
# Licensed to the Apache Software Foundation (ASF) under one or more
# contributor license agreements.  See the NOTICE file distributed with
# this work for additional information regarding copyright ownership.
# The ASF licenses this file to You under the Apache License, Version 2.0
# (the "License"); you may not use this file except in compliance with
# the License.  You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#
-->

## Apache 1.13.0-incubating (next release)
Changes:
  - Update version of PHP to 7.1.25

## 1.0.3
Changes:
  - Allow /run endpoint to accept more environment variables [#40](https://github.com/apache/incubator-openwhisk-runtime-php/pull/40)

## 1.0.2
Changes:
  - Disallow re-initialization of function.

## 1.0.1

- Change: Update PHP to 7.1.18
- Change: Update [guzzlehttp/guzzle](https://packagist.org/packages/guzzlehttp/guzzle) to 6.3.3
- Change: Update [ramsey/uuid](https://packagist.org/packages/ramsey/uuid) to 3.7.3

## 1.0.0
Initial release

- Added: PHP: 7.1.9
- Added: PHP extensions in addition to the standard ones:
    - bcmath
    - curl
    - gd
    - intl
    - mbstring
    - mysqli
    - pdo_mysql
    - pdo_pgsql
    - pdo_sqlite
    - soap
    - zip
- Added: Composer packages:
    - [guzzlehttp/guzzle](https://packagist.org/packages/guzzlehttp/guzzle): 6.3.0
    - [ramsey/uuid](https://packagist.org/packages/ramsey/uuid): 3.6.1