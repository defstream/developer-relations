.PHONY: build test clean all run

all: clean build test

build:
	@echo "👷🏽‍♀️building rust project..."
	cargo build

test:
	@echo "👷🏽‍♀️running tests..."
	RUST_LOG=debug cargo test

clean:
	@echo "👷🏽‍♀️cleaning up..."
	cargo clean

run:
	@echo "👷🏽‍♀️running rust project..."
	RUST_LOG=debug cargo run