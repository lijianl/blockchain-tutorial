
# 规则定义
#target: 依赖(依赖下面的依赖)
#	command 



# 定义变量
BINARY := blockchain


# 默认执行
all: build run


# make 指令
build:
	@echo "==> Go build"
	# 变量取值
	@go build -o $(BINARY)

run:
	@echo "==> Running"
	@./$(BINARY)

clean:
	rm ./$(BINARY)

.PHONY: build run
