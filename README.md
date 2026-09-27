# Estilos e Cinema: Seedance + Higgsfield v6.2

Curso gratuito com 9 aulas em 3 módulos. Estilo OSWork v6.2. Reconstruir: `python3 montar.py`. Fontes editoriais em `context/`.

As imagens são ilustrações Codex, não resultados de Seedance ou Cinema Studio. O aluno deve executar e revisar as práticas antes de declarar a produção concluída. Estimativa: 4–6 horas com produção, além das filas.

## English / Español

[English](https://inematds.github.io/curso-estilos-cinema-ia/en/) · [Español](https://inematds.github.io/curso-estilos-cinema-ia/es/)

Textos traduzidos com GPT-6 Luna por subagentes nativos da assinatura Codex, sem API externa. Ilustrações originais compartilhadas; progresso e anotações separados por idioma.

Após montar o português, reaplique os catálogos salvos:

```sh
python3 scripts/i18n_local.py build .
python3 scripts/verify_i18n.py .
node scripts/check_i18n_browser.cjs . /tmp/curso-i18n-checks
```

Requer Python/BeautifulSoup e os pacotes locais Babel/Playwright indicados nos scripts. A montagem não chama modelos nem redes. Mudanças na fonte PT exigem revisar os catálogos `i18n/`. O motor oficial `assets/curso.js` é preservado; a proteção de importação é gerada em `assets/curso-i18n.js` e nas edições traduzidas.

Evidências em `context/validacao-i18n.md`. Revisões por agentes são simuladas, não testes com alunos reais.
