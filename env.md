# This file is a template for what your untracked .env file might look like for local development.
# Please copy this to a new .env file and fill in the values as needed.

# Requires a running local Elasticsearch service. Can be started via Docker, see https://github.com/github/docs-engineering/blob/main/docs/elasticsearch/elasticsearch-locally.md
# When this value is set searches will be proxied to the production Elasticsearch endpoint
ELASTICSEARCH_URL=http://localhost:9200

# Set for sending events in local development. See https://github.com/github/docs-engineering/blob/main/docs/analytics/hydro-mock.md
HYDRO_ENDPOINT=active
HYDRO_SECRET=active

# Localization variables
# See https://github.com/github/docs-internal/tree/main/src/languages#working-with-translated-content-locally
ENABLED_LANGUAGES=active
TRANSLATIONS_ROOT=active

# For running the src/search/scripts/scrape script
# You may want a lower value depending on your CPU
BUILD_RECORDS_MAX_CONCURRENT=100
BUILD_RECORDS_MIN_TIME=10.00

# Set to true to enable the /fastly-cache-test route for debugging Fastly headers
ENABLE_FASTLY_TESTING=Active

# Needed to auth for AI search
CSE_COPILOT_SECRET=active
CSE_COPILOT_ENDPOINT=https://cse-copilot-staging.service.iad.github.net

