# Use qmcgaw/latexdevcontainer as the base image
FROM qmcgaw/latexdevcontainer

# Update the package lists
RUN apt-get update && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

# Install texlive-full in a separate layer
RUN apt-get update && \
    apt-get install -y texlive-full && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*
