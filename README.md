# Algoritmos-de-cifrado
Algoritmos de cifrado desarrollados durante el periodo 2026/2 para la optativa de Introduction to Cryptography de la Escuela Superior de Cómputo (ESCOM-IPN) con la profesora Díaz Santiago Sandra.

## Algoritmos implementados
- [AES cipher](src/aes_cipher/)
- [AES cipher v2](src/aes_cipher_2/)
- [Affin cipher](src/affin_cipher/)
- [DES cipher](src/block_cipher/)
- [Hill cipher](src/hill_cipher/)
- [Permutation cipher](src/permutation_cipher/)
- [Shift cipher](src/shift_cipher/)

## 📁 Estructura del proyecto
```
Algoritmos-de-cifrado
├── data/
├── docs/
│   ├── lab11_introcrypto_20260528.pdf
│   ├── _lab01_introcrypto_20260219.pdf
│   ├── _lab02_introcrypto_20260226 1.pdf
│   ├── _lab03_introcrypto_20260305.pdf
│   └── _lab04_introcrypto_20260312.pdf
├── src/
│   ├── aes_cipher/
│   │   ├── aes_cipher.py
│   │   ├── README.md
│   │   └── __init__.py     
│   ├── aes_cipher_2/
│   │   ├── aes_cipher_2.py
│   │   ├── README.md
│   │   └── __init__.py     
│   ├── affin_cipher/
│   │   ├── affin_cipher.py
│   │   ├── README.md
│   │   └── __init__.py     
│   ├── block_cipher/
│   │   ├── block_cipher.py
│   │   ├── README.md
│   │   ├── tests.py
│   │   └── __init__.py     
│   ├── config/
│   │   ├── config.py
│   │   └── __init__.py     
│   ├── decorators/
│   │   ├── decorators.py
│   │   └── __init__.py     
│   ├── hill_cipher/
│   │   ├── hill_cipher.py
│   │   ├── README.md
│   │   └── __init__.py     
│   ├── permutation_cipher/
│   │   ├── permutation_cipher.py
│   │   ├── README.md
│   │   └── __init__.py     
│   ├── shift_cipher/
│   │   ├── README.md
│   │   ├── shift_cipher.py
│   │   └── __init__.py     
│   ├── utils/
│   │   ├── colors.py
│   │   ├── utils.py
│   │   └── __init__.py
│   └── main.py
├── .gitignore
├── Makefile
├── README.md
└── requirements.txt                
```

## 🚀 Uso del proyecto
- Descargar dependencias
```
mingw32-make install
```
- Correr el programa (se crea la carpeta `/data` y dentro los archivos `plaintext.txt` y `ciphertext.txt`)
```
mingw32-make run
```
- Generar archivo `requirements.txt`
```
mingw32-make freeze
```
- Guardar estructura del programa
```
mingw32-make tree
```
