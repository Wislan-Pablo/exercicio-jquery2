### Exercício Módulo 10 - Plugins jQuery

## CORREÇÕES FEITAS POR MIM
- No seu index.html, o seletor estava incorreto: #carousel quando o correto é #carousel-imagens
- Correção da ordem de carregamento dos scripts que estava incorreta
- Correção dos scripts que estavam sendo chamados duas vezes, em ordens conflitantes
- O jQuery plugin só executa depois que o jQuery carregar na página.
-  Correção dos nomes dos campos no JS que não coincidiam com o atributo name="..." no HTML

- Validação com jQuery Validate e máscaras:
  - No main.js, os métodos e nomes dos campos estavam com erros:
  - mascara() não existe — o correto é .mask(), conforme o plugin jquery.mask.min.js.
  - requerido não é válido — o correto é required
  - O seletor ('form') deveria ser ('#form'), para evitar conflitos.
  - Os campos devem ser validados conforme os name dos <input>, e não só pelo id.

