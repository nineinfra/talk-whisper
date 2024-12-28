问答模型
https://www.modelscope.cn/
llama3 gguf
https://www.modelscope.cn/models/LLM-Research/Meta-Llama-3-8B-Instruct-GGUF/files

语音转换模型
https://ggml.ggerganov.com/
ggml-model-whisper-base.bin

语音对话开源项目
https://github.com/ggerganov/whisper.cpp/releases

C++ 依赖库
// "-lOle32", Windows tts 文本转语音依赖库
// "-lsapi", Windows tts 文本转语音依赖库

调用命令行: 根据自己的文件路径进行设置
talk-llama.exe -mw ggml-model-whisper-base.bin -ml Meta-Llama-3-8B-Instruct.Q4_K_S.gguf -p Zira -s speaker_02.exe -sf speaker_01.txt -l en
