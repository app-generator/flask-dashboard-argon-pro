# Change Log

## [1.0.8] 2023-02-02
### Changes

- `Update Docker` Scripts
  - External port is now `5085`
- Update Documentation
  - [Flask Argon PRO](https://docs.appseed.us/products/flask-dashboards/argon-dashboard-pro/) - official docs
- Remove `HEROKU` Procfile   

## [1.0.7] 2022-04-01
### Fixes

- **Patch ImportError**: [cannot import name 'safe_str_cmp' from 'werkzeug.security'](https://docs.appseed.us/content/how-to-fix/importerror-cannot-import-name-safe_str_cmp-from-werkzeug.security)
  - `Werkzeug` deprecation of `safe_str_cmp` starting with version `2.1.0`
    - https://github.com/pallets/werkzeug/issues/2359

## [1.0.6] 2021-11-06
### Improvements

- Bump Codebase: [Flask Dashboard](https://github.com/app-generator/boilerplate-code-flask-dashboard) v2.0.0
  - Dependencies update (all packages) 
    - Flask==2.0.1 (latest stable version)
  - Better Code formatting
  - Improved Files organization
  - Optimize imports
  - Docker Scripts Update
  - Gulp Tooling  (SASS Compilation)
- Fixes:  
  - ImportError: cannot import name 'TextField' from 'wtforms'

## [1.0.5] 2021-05-16
### Dependencies Update

- Bump Codebase: [Flask Dashboard](https://github.com/app-generator/boilerplate-code-flask-dashboard) v1.0.6
- Freeze used versions in `requirements.txt`
    - jinja2 = 2.11.3

## [1.0.4] 2021-03-18
### Improvements

- Bump Codebase: [Flask Dashboard](https://github.com/app-generator/boilerplate-code-flask-dashboard) v1.0.5
- Freeze used versions in `requirements.txt`
    - flask_sqlalchemy = 2.4.4
    - sqlalchemy = 1.3.23

## [1.0.3] 2021-02-17
### Improvements

- UI: [Jinja Argon PRO](https://github.com/app-generator/jinja-argon-dashboard-pro) v1.0.2
- Codebase: [Flask Dashboard](https://github.com/app-generator/boilerplate-code-flask-dashboard) v1.0.4

## [1.0.2] 2020-12-29
### Improvements & Bug Fixes

- Bump Flask codebase - v1.0.2

## [1.0.1] 2020-06-14
### Improvements

- Bump UI Kit to the latest version - v1.2.0
- Update the code-base to the latest version - https://github.com/app-generator/boilerplate-code-flask-dashboard
- Improve 403 errors (access denied) flow
- Update Licensing information
- Add CHANGELOG.md to track all changes

## [1.0.0] 2020-02-07
### Initial Release
