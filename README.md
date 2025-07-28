# HA
Blueprints

# paralelovirtual_multi

📘 Blueprint para [Home Assistant](https://www.home-assistant.io) que faz paralelo virtual.
📘 Sincroniza um interruptor principal e múltiplos interruptores virtuais com um input_boolean. Ao mudar o estado de qualquer um deles, os outros seguem o estado refletido no input_boolean. Esta versão evita loops com verificação de estado.

## 📋 Requisitos
- Entidades compatíveis (ex: `input_boolean`, `switch`, etc.)

## 🛠️ Instalação

1. Copie o conteúdo do arquivo `.yaml` e cole em `Configurações > Blueprints > Importar Blueprint`.
2. criar um input_boolean para cada paralelo virtual a ser criado na pasta homeassistant/input_booleans
3. Ou use o link de importação abaixo.

📥 [Importar este blueprint](https://github.com/andersoneloi/HA/blob/main/paralelovirtual_multi.yaml)

## 🧪 Exemplo de uso
- Input_boolean
<img width="289" height="120" alt="image" src="https://github.com/user-attachments/assets/eb8b5842-9b3e-4ae6-ac92-45d146ac5658" />

- Paralelo virtual
<img width="1062" height="564" alt="image" src="https://github.com/user-attachments/assets/67eb5f78-cbec-4df4-a419-012ed0ca32af" />

