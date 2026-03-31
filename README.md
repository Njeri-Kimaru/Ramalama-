# Table of contents
1. [What is ramalama](What-is-ramalama)
2. [Repo structure](Repo-structure)
3. [Installing ramalama](Installing-ramalama)
4. [Ollama](Ollama)
5. [Huggingface]()Huggingface
6. [modelscope](modelscope)
7. [OCI registries](OCI-registries)
8. [Why these transports](Why-these-transports)
9. [Comparing the different types of models amd transports.](Comparing-the-different-types-of-models-amd-transports.)
10. [Does ramalama make AI boring?](Does-ramalama-make-AI-boring?)
11. [Using AI](Using-AI)



# What is ramalama
[Ramalama](https://ramalama.ai/) is an open source command line tool that makes running AI models locally simple by treating them like containers.
Ramalama runs models with podman/docker and there's no config needed.
It is GPU optimizedand accelerates performance.
It is compatible with llama.cpp, openvino, vLLM, whisper.cpp and manymore.

## Repo structure
|--Screenshots
|--README.md

## Installing ramalama
Ramalama is easy to install.
After installing check the version you are using.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/tfalaol8rn6zay0lpkwr.png)

Ramalama supports multiple model registries(transports);
### 1. Ollama
It is the quickest and easiest registry.
Here are a few AI models i ran using ollama.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/kodanaa77q5ei0cm70nb.png)


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/yz2d215ai9bkc9d7p4hy.png)

### 2. Huggingface
Some hugging face model require one to login.
Here are some that don't require logging in:

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/5ulbhr6gpzj1lj79e8l8.png)


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/cascyyedeihsgbmb6jjd.png)

### 3. Modelscope
Model scope worked quite well too.
but I had to upgrade ramalama's version.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/8oz9h8y8onpduc1ax8rp.png)

Here are some of modelscope's model I used;

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/8htkg8xp4pzn9031mp1f.png)

## 4. OCI registries
I used the github container registry(ghcr.io)
In github I had to login first then get an authentication token.
Afterwards, I converted a model then accessed it using the ghcr.io
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/om5vi2ea2tvkkburyrig.png)

## Why these transports
- I used ollama because it is easy and quite fast.
- FOr hugging face I have used it previously in my projects and I wanted to see how it work with ramalama. However, the model am used to using could only be accesed with an authentication token so I chose other models.
- For the modelscope I found it online and I wanted to try it.
- I found that OCI registries are quite common and they follow certain specifications and standards so I wanted to try it too.

## Comparing the different types of models and transports.
#### 1. Ollama and the models I used using Ollama
In Ollama, I used granite model  

#### 2. Huggingface and models I used using huggingface

#### 3. MOdelscope and models I used using modelscope

#### 4. OCI registries and models used using OCI transport registry

## Does ramalama make AI boring?

# Using AI
