c:
	conda activate m3mlx

cd_mlx_lm:
	cd llms/mlx_lm

run:
	mlx_lm.server --model mlx-community/Qwen2.5-Coder-14B-Instruct-8bit --trust-remote-code --port 8722

k:
	./kill.sh

w:
	curl -X GET "http://127.0.0.1:9000/api/ai/WriteBlogRandomlyWithLLM?model=MLXLMServerO1" -H  "Request-Origion:SwaggerBootstrapUi" -H  "accept:*/*"

