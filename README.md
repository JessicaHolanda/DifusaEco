# DifusaEco

- uses: lowlighter/metrics@latest
  with:
    # ... other options
    template: classic
    user: repository-owner              # Optional if you're the owner of target repository
    query: '{"repo":"repository-name"}' # Use a JSON encoded object to pass your repository name in "repo" key
