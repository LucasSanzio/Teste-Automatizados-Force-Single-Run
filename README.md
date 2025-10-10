# 🖥️ Janela OpenGL 3.3 com GLFW

Este projeto em Python cria uma janela simples utilizando **GLFW** e **OpenGL 3.3 Core Profile**.  
O código inicializa o contexto gráfico, define uma cor de fundo personalizada e mantém a janela aberta por **5 segundos** antes de encerrá-la automaticamente.

---

## 🚀 Como funciona

1. Inicializa o **GLFW** e configura o contexto para **OpenGL 3.3 Core Profile**.  
2. Cria uma janela de **800x600 pixels** com o título `"Janela(OpenGL 3,3 Core)"`.  
3. Define a **cor de fundo** da tela com `glClearColor()`.  
4. Renderiza a janela, processa eventos e a mantém aberta por 5 segundos.  
5. Finaliza o GLFW e encerra o programa.

---

## 🎨 Como alterar as cores

A cor de fundo da janela é configurada nesta linha:

```python
glClearColor(0.1, 0.1, 0.1, 1.0)
```

Os quatro valores representam:

```python
glClearColor(R, G, B, A)
```

- **R** → Vermelho (0.0 a 1.0)  
- **G** → Verde (0.0 a 1.0)  
- **B** → Azul (0.0 a 1.0)  
- **A** → Opacidade (1.0 = opaco)

### 🔹 Exemplo de alteração

Para mudar o fundo para azul:

```python
glClearColor(0.0, 0.0, 1.0, 1.0)
```

---

## 🧩 Requisitos e execução

Antes de rodar o código, instale as bibliotecas necessárias:

```bash
pip install glfw PyOpenGL
```

Em seguida, execute o script no terminal:

```bash
python nome_do_arquivo.py
```

---

