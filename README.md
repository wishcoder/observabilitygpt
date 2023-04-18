# Observability GPT

![Observability GPT](https://github.com/wishcoder/observabilitygpt/blob/main/images/Observability-GPT-Small.png)

Observability GPT is a ChatGPT plugin for Reliability Engineering Observability using [OpenAPI](https://openai.com/blog/openai-api) and [LangChain](https://blog.langchain.dev/). LangChain loader is used to load [Google Cloud Platform k8s-config-connector](https://github.com/GoogleCloudPlatform/k8s-config-connector/) (KCC) files, split it up into documents, get vectors for those documents as [OpenAI Emeddings](https://platform.openai.com/docs/guides/embeddings), then ask a question about how to create KCC ymal for k8 deployment type. 

Important: This is work inprogress.

# python modules and steps

* py -m pip install --user [virtualenv](https://virtualenv.pypa.io/en/latest/)
* python -m virtualenv observabilitygpt
* source ./observabilitygpt/Scripts/activate
* pip install [GitPython](https://gitpython.readthedocs.io/en/stable/)
* pip install [poetry](https://python-poetry.org/)
* poetry install
* pip install [unstructured](https://pypi.org/project/unstructured/)
* pip install [python-magic-bin](https://pypi.org/project/python-magic-bin/)
* pip install [chromadb](https://pypi.org/project/chromadb/)
* pip install [nltk](https://www.nltk.org/)
* pip install [langchain\[all\]](https://python.langchain.com/en/latest/index.html)
* pip install --upgrade langchain
* pip install [pyyaml](https://pypi.org/project/PyYAML/)
* pip install [blobfile](https://pypi.org/project/blobfile/)
* pip install [cffi](https://cffi.readthedocs.io/en/latest/)
* pip install [cryptography](https://cryptography.io/en/latest/)
* pip install [protobuf](https://github.com/protocolbuffers/protobuf)
* pip install [h2](https://pypi.org/project/h2/)
* pip install [iniconfig](https://pypi.org/project/iniconfig/)
* pip install [pluggy](https://pluggy.readthedocs.io/en/stable/)
* pip install [pyproject_hooks](https://github.com/pypa/pyproject-hooks)
* pip install [tzdata](https://pypi.org/project/tzdata/)
* pip install [win32-setctime](https://pypi.org/project/win32-setctime/)
* pip install [XlsxWriter](https://pypi.org/project/XlsxWriter/)



