# Use the official Lean 4 image as a base
FROM ghcr.io/leanprover/lean4:latest

# Install additional dependencies if needed
# For example, to install Python:
# RUN apt-get update && apt-get install -y python3 python3-pip

# Set the working directory
WORKDIR /workspaces/lean-gym

# Copy the current repository into the container
COPY . /workspaces/lean-gym

# Run the setup script to install lean-gym dependencies
RUN bash ./scripts/setup.sh

