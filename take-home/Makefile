# Arcane incantation to print all the other targets, from https://stackoverflow.com/a/26339924
help:
	@$(MAKE) -pRrq -f $(lastword $(MAKEFILE_LIST))

# Install exact Python and CUDA versions
env:
	conda env update --prune -f environment.yml
