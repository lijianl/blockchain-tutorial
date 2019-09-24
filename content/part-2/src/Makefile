BINARY := blockchain

all: build run

build:
	@echo "==> Go build"
	@go build -o $(BINARY)

run:
	@echo "==> Run"
	@./$(BINARY)


clean:
	rm ./$(BINARY)

.PHONY: build run
