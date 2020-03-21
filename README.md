Backend
![https://gitlab.com/recipe-cookbook/backend/pipelines](https://gitlab.com/recipe-cookbook/backend/badges/master/pipeline.svg) ![https://gitlab.com/recipe-cookbook/backend](https://gitlab.com/recipe-cookbook/backend/badges/master/coverage.svg)

Frontend
![https://gitlab.com/recipe-cookbook/frontend/pipelines](https://gitlab.com/recipe-cookbook/frontend/badges/master/pipeline.svg) ![https://gitlab.com/recipe-cookbook/frontend](https://gitlab.com/recipe-cookbook/frontend/badges/master/coverage.svg)

A modern, React+GraphQL _cooking_ Cookbook. I was not satisfied with any other existing private recipe/cookbook solutions out there, so I brewed my own. Documentation is sparse, open an issue if you want to try to set this up for yourself and are having issues.

# Quickstart

This repository contains the necessary submodules. All development is housed on Gitlab, this Github repository is for convienience.

Be sure to get the submodules: `git submodule update --init --recursive`

## Common

Common has the code that generates bindings from the backend for the frontend. Run `npm run generate-gql` in `common/` any time you change the graphql structure on the backend to keep it in sync.

## Backend

Primsa2-based. No documentation at this time.

## Frontend

React-based. No documentation at this time.
