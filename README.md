# 🎁 gitwrapped

> O **Spotify Wrapped** do seu repositório Git, direto no terminal.
> Zero dependências. Um único arquivo. Funciona em qualquer repo.

Descubra:

- 🔥 sua maior sequência de dias commitando
- 🦉 sua **persona de dev** (Coruja Noturna, Madrugador, Guerreiro de Fim de Semana...)
- 🗓️ um **mapa de calor** de dia da semana × hora
- 📂 os arquivos mais mexidos do projeto
- 🏷️ tipos de commit (`feat`, `fix`, `refactor`...)
- 💬 as palavras que você mais usa nas mensagens

## Instalação

```bash
git clone https://github.com/SEU-USUARIO/gitwrapped.git
cd gitwrapped
python gitwrapped.py /caminho/do/seu/repo
```

Requer apenas **Python 3.8+** e **git**.

## Exemplos

```bash
python gitwrapped.py                          # repo atual
python gitwrapped.py --since 2026-01-01       # só este ano
python gitwrapped.py --author "Maria"         # só os commits de uma pessoa
python gitwrapped.py --since "6 months ago"
```

## Como as personas funcionam

| Persona | Regra |
|---|---|
| 🦉 Coruja Noturna | mais de 25% dos commits entre 00h e 05h |
| 🏴‍☠️ Guerreiro de Fim de Semana | mais de 35% dos commits no sábado/domingo |
| 🐓 Madrugador | mais de 30% entre 05h e 10h |
| 👔 Profissional das 9 às 18 | mais de 60% em horário comercial |
| 🌀 Caótico Neutro | o resto |

## Ideias para contribuir

- [ ] Exportar o resultado como imagem/SVG para compartilhar
- [ ] Flag `--json`
- [ ] Comparar dois autores lado a lado
- [ ] Mais personas
- [ ] Tema de cores claro

PRs são muito bem-vindos! 💚

## Licença

MIT
