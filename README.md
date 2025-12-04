# OpenFloodForecasting.github.io

The official website for the OpenFloodForecasting initiative, an open source effort in flood forecasting data archiving, modelling, and visualizing.

## Local Development

To run this website locally, you will need **Ruby** and **Bundler** installed.

### Prerequisites

1.  **Install Ruby**: Ensure you have a compatible version of Ruby installed (e.g., via `rbenv` or `rvm`).
2.  **Install Bundler**:
    ```bash
    gem install bundler
    ```

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/OpenFloodForecasting/OpenFloodForecasting.github.io.git
    cd OpenFloodForecasting.github.io
    ```

2.  Install dependencies:
    ```bash
    bundle install --path vendor/bundle
    ```

### Running the Website

1.  Start the local Jekyll server:
    ```bash
    bundle exec jekyll serve
    ```

2.  Open your browser and navigate to:
    ```
    http://localhost:4000
    ```

The site will automatically reload when you make changes to the files.
