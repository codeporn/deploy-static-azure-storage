# deploy-static-azure-storage

A GitHub Action to deploy static content to an Azure Storage Account.

## Background

This repository accompanies my blog post on deploying static files to Azure Storage using GitHub Actions. A detailed explanation of the architecture, required Azure resources, and the CDN purge workflow can be found here:
https://blog.wende.io/2023/04/13/deploy-static-files-to-azure-storage-with-github-actions/

Due to Azure CDN retirement announcements, I later migrated to a simplified, zero-cost architecture based on Azure Static Web Apps. The updated approach is documented here:
https://blog.wende.io/2026/02/04/from-azure-front-door-back-to-zero-cost-migrating-a-hexo-blog-to-azure-static-web-apps/
