# Use the leanprovercommunity/lean image as a base
FROM leanprovercommunity/lean:latest

# Set the working directory
WORKDIR /workspaces/lean-gym

# Copy the current repository into the container
COPY . /workspaces/lean-gym

# Install additional dependencies if needed
# For example, to install Python:
# RUN apt-get update && apt-get install -y python3 python3-pip

# Run the setup script to install lean-gym dependencies
RUN bash ./scripts/setup.sh

