# 🐯 Tigerfetch

Um mini script Python inspirado no Neofetch, focado em exibir informações da CPU. É o desenvolvimento para aplicativos CLI para o [Conteiner do TigerOS](https://github.com/selrahcsan/Conteiner-TigerOS)

## 🔧 O que ele faz no momento

Exibe:

* Frequência máxima da CPU (em GHz, com 2 casas decimais)
* Número total de núcleos lógicos disponíveis

### 📦 Exemplo de saída

```bash
CPU     3.60 GHz (8 cores)
```

## 🚀 Como usar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/tigerfetch.git
cd tigerfetch
```

### 2. Instale a dependência

Requer o [`psutil`](https://pypi.org/project/psutil/):

```bash
sudo apt install python3-psutil  
```

### 3. Execute o script

```bash
python3 tigerfetch.py
```

## 📁 Estrutura do script

* `get_cpu_info()` – obtém frequência da CPU e núcleos lógicos
* `tigerfetch()` – imprime as informações

## ✨ Créditos

Projeto Inspirado no falecido [neofetch](https://github.com/dylanaraps/neofetch).
