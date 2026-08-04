# Lifecycle declaration

**Lifecycle:** `frozen`  
**Decision date:** 2026-08-04  
**Maintenance mode:** preserve the historical geospatial tutorial

## Historical role

This repository preserves a tutorial and demonstration workflow for loading Boston open geospatial data, plotting GeoJSON, uploading layers to Mapbox Studio, and presenting interactive maps in HTML.

It is retained as evidence of a particular learning and prototyping workflow, not as a maintained mapping product.

## Preservation policy

- Preserve the notebooks, HTML examples, screenshots, and original instructions.
- Treat Boston data URLs, Mapbox APIs, tokens, layers, and hosted demos as period-specific dependencies.
- Do not refresh datasets, migrate mapping libraries, repair deployments, or modernize the tutorial by default.
- Do not claim that the linked interactive maps or external hosting remain online.

## Interpretation and security boundary

This repository is not a current Boston data portal, supported Mapbox integration, or production deployment. Any revival must use current Mapbox authentication guidance and must not recover or reuse historical tokens from notebooks, shell history, or configuration files.

## Revival rule

Revival requires a named teaching or mapping consumer and a bounded objective, such as reproducing one map from a specified Boston dataset. Record the data vintage, current API, credential handling, and expected local output before implementation.

A modern tutorial should normally be created separately and cite this repository as predecessor evidence.

## Verification status

This declaration was prepared from the current README and repository metadata. No notebook, Boston dataset, Mapbox upload, HTML map, or external demo URL was executed or verified.