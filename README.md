# RSS Feed Aggregator 📡

A robust RSS feed aggregator built with Go. Fetches, parses, and stores RSS feeds from multiple sources, providing a unified API for accessing aggregated content.

## Features

- **Multi-feed support** - Aggregate multiple RSS feeds simultaneously
- **Automatic fetching** - Configurable intervals for feed updates
- **PostgreSQL storage** - Persistent storage with goose migrations
- **RESTful API** - Clean API for managing feeds and accessing posts
- **Docker support** - Easy deployment with containers

## Tech Stack

- **Language:** Go 1.21+
- **Database:** PostgreSQL
- **Migrations:** goose
- **Container:** Docker
- **API:** net/http (standard library)

## Prerequisites

- Go 1.21 or higher
- PostgreSQL 14+
- goose (for migrations)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/ndanilova/go-rss-feed-aggregator.git
cd go-rss-feed-aggregator