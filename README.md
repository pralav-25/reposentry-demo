# RepoSentry demo fixture

This repository is a small public test target for the RepoSentry class project. It contains deliberately outdated, exactly pinned Python and Maven dependencies so the scanner can demonstrate OSV advisory results.

## Scan it

Paste this URL into RepoSentry:

    https://github.com/pralav-25/reposentry-demo

RepoSentry reads `requirements.txt` and `pom.xml` as data. It does not install dependencies, build the Maven project, or execute repository code.

## Included fixtures

- Python: Django 2.2.0, Pillow 8.1.2, and Requests 2.19.1
- Maven: Commons Collections 3.2.1, Jackson Databind 2.9.8, and Log4j Core 2.14.1

These old versions are intentionally vulnerable test fixtures. Do not use them in an actual application.
