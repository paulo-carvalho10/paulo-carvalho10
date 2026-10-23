<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,55:1f6feb,100:2ea043&height=190&section=header&text=Paulo%20Carvalho&fontSize=46&fontColor=ffffff&fontAlignY=34&desc=Full%20Stack%20%C2%B7%20Python%20e%20TypeScript&descSize=17&descAlignY=56" width="100%" alt="Paulo Carvalho"/>

<p>
<a href="https://github.com/paulo-carvalho10"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1200&color=2EA043&center=true&vCenter=true&width=620&lines=Estudante+de+Ci%C3%AAncia+da+Computa%C3%A7%C3%A3o+na+UFU;Back-end+em+Python%2C+front+em+React+e+Next.js;Projetos+no+ar%2C+com+testes+de+verdade;Medir+antes+de+afirmar" alt="Estudante de Ciência da Computação na UFU"/></a>
</p>

<br/>

<p>
<img src="https://custom-icon-badges.demolab.com/badge/Uberl%C3%A2ndia-MG-1f6feb?style=flat-square&logo=location&logoColor=white" alt="Uberlândia, MG"/>
<img src="https://custom-icon-badges.demolab.com/badge/Ci%C3%AAncia_da_Computa%C3%A7%C3%A3o-UFU-2ea043?style=flat-square&logo=mortar-board&logoColor=white" alt="Ciência da Computação, UFU"/>
<img src="https://custom-icon-badges.demolab.com/badge/aberto_a-est%C3%A1gio-E39842?style=flat-square&logo=briefcase&logoColor=white" alt="Aberto a estágio"/>
</p>

</div>

## <img src="https://custom-icon-badges.demolab.com/badge/-Sobre_mim-1f6feb?style=for-the-badge&logo=person&logoColor=white" alt="Sobre mim" height="28"/>

Estudo Ciência da Computação na **Universidade Federal de Uberlândia** e construo sistemas de ponta a ponta: o back-end em Python, o front em React e Next.js com TypeScript, o banco, o deploy e os testes.

- 🔭 Agora construo o **TraceFlow**, uma plataforma de observabilidade em tempo real.
- ⚽ Nas horas vagas, cuido do **PRANCHETA 11**, um jogo de técnico de futebol com um motor de simulação calibrado contra o futebol real.
- 🧪 Gosto de projeto que dá para conferir: o PRANCHETA 11 tem mais de 400 testes e o AgendaKi tem 137.
- 🌱 Estudando agora: sistemas distribuídos, filas e bancos de séries temporais.

## <img src="https://custom-icon-badges.demolab.com/badge/-Em_constru%C3%A7%C3%A3o-E39842?style=for-the-badge&logo=tools&logoColor=white" alt="Em construção" height="28"/>

### 📡 TraceFlow

Plataforma de observabilidade de aplicações: recebe traces pelo OpenTelemetry e mostra, ao vivo, as métricas de cada serviço, o mapa de dependências e os incidentes, com a causa provável e o raio de impacto. Um *playground* de caos injeta falhas para ver tudo acontecer. O pipeline é próprio, sem Prometheus nem Grafana:

```mermaid
flowchart LR
    A[App com<br/>OpenTelemetry] --> B[Ingestão<br/>FastAPI]
    B --> C[(Redis<br/>Streams)]
    C --> D[Processador<br/>asyncio]
    D --> E[(TimescaleDB)]
    D --> F[API e<br/>WebSocket]
    E --> F
    F --> G[Painel<br/>Next.js]
```

<p>
<img src="https://custom-icon-badges.demolab.com/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white" alt="OpenTelemetry"/>
<img src="https://custom-icon-badges.demolab.com/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
<img src="https://custom-icon-badges.demolab.com/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis"/>
<img src="https://custom-icon-badges.demolab.com/badge/TimescaleDB-FDB515?style=flat-square&logo=timescale&logoColor=black" alt="TimescaleDB"/>
<img src="https://custom-icon-badges.demolab.com/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
<img src="https://custom-icon-badges.demolab.com/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
<img src="https://custom-icon-badges.demolab.com/badge/repo_privado-por_enquanto-555555?style=flat-square&logo=lock&logoColor=white" alt="Repositório privado por enquanto"/>
</p>

## <img src="https://custom-icon-badges.demolab.com/badge/-Projetos-2ea043?style=for-the-badge&logo=repo&logoColor=white" alt="Projetos" height="28"/>

<table>
<tr>
<td width="50%" valign="top">

<h3>⚽ PRANCHETA 11</h3>

Jogo de técnico de futebol no navegador. O motor de simulação em Python é calibrado contra o futebol real: 40 divisões, 706 clubes, copas, seleções e multijogador em rede.

<p>
<img src="https://custom-icon-badges.demolab.com/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://custom-icon-badges.demolab.com/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/>
<img src="https://custom-icon-badges.demolab.com/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
<img src="https://custom-icon-badges.demolab.com/badge/testes-400%2B-2ea043?style=flat-square&logo=check-circle-fill&logoColor=white" alt="Mais de 400 testes"/>
</p>

<p>
<a href="https://paulo-carvalho10.github.io/football-manager/"><img src="https://custom-icon-badges.demolab.com/badge/Ver_site-2ea043?style=for-the-badge&logo=link-external&logoColor=white" alt="Ver site"/></a>
<a href="https://github.com/paulo-carvalho10/football-manager"><img src="https://custom-icon-badges.demolab.com/badge/C%C3%B3digo-24292f?style=for-the-badge&logo=code&logoColor=white" alt="Código"/></a>
</p>

</td>
<td width="50%" valign="top">

<h3>🤖 ResolveAI</h3>

Help desk com IA: classifica e encaminha os chamados sozinho e sugere soluções com RAG, buscando casos parecidos no pgvector.

<p>
<img src="https://custom-icon-badges.demolab.com/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
<img src="https://custom-icon-badges.demolab.com/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
<img src="https://custom-icon-badges.demolab.com/badge/pgvector-336791?style=flat-square&logo=database&logoColor=white" alt="pgvector"/>
<img src="https://custom-icon-badges.demolab.com/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
</p>

<p>
<a href="https://resolveai-silk.vercel.app"><img src="https://custom-icon-badges.demolab.com/badge/Ver_site-2ea043?style=for-the-badge&logo=link-external&logoColor=white" alt="Ver site"/></a>
<a href="https://github.com/paulo-carvalho10/resolveai"><img src="https://custom-icon-badges.demolab.com/badge/C%C3%B3digo-24292f?style=for-the-badge&logo=code&logoColor=white" alt="Código"/></a>
</p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3>📅 AgendaKi</h3>

Agendamento online para barbearias e salões: página do cliente, painel do dono, vários profissionais e avisos no celular.

<p>
<img src="https://custom-icon-badges.demolab.com/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
<img src="https://custom-icon-badges.demolab.com/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://custom-icon-badges.demolab.com/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
<img src="https://custom-icon-badges.demolab.com/badge/testes-137-2ea043?style=flat-square&logo=check-circle-fill&logoColor=white" alt="137 testes"/>
</p>

<p>
<a href="https://paulo-carvalho10.github.io/agendaki/"><img src="https://custom-icon-badges.demolab.com/badge/Ver_site-2ea043?style=for-the-badge&logo=link-external&logoColor=white" alt="Ver site"/></a>
<a href="https://github.com/paulo-carvalho10/agendaki"><img src="https://custom-icon-badges.demolab.com/badge/C%C3%B3digo-24292f?style=for-the-badge&logo=code&logoColor=white" alt="Código"/></a>
</p>

</td>
<td width="50%" valign="top">

<h3>💸 PixCerto</h3>

Gera e confere cobranças Pix (BR Code) inteiramente no navegador. Não há back-end: a chave Pix nunca sai do aparelho.

<p>
<img src="https://custom-icon-badges.demolab.com/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://custom-icon-badges.demolab.com/badge/Pix-32BCAD?style=flat-square&logo=pix&logoColor=white" alt="Pix"/>
<img src="https://custom-icon-badges.demolab.com/badge/zero-back--end-555555?style=flat-square&logo=shield-check&logoColor=white" alt="Zero back-end"/>
</p>

<p>
<a href="https://paulo-carvalho10.github.io/pixcerto/"><img src="https://custom-icon-badges.demolab.com/badge/Ver_site-2ea043?style=for-the-badge&logo=link-external&logoColor=white" alt="Ver site"/></a>
<a href="https://github.com/paulo-carvalho10/pixcerto"><img src="https://custom-icon-badges.demolab.com/badge/C%C3%B3digo-24292f?style=for-the-badge&logo=code&logoColor=white" alt="Código"/></a>
</p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3>🔧 OS Fácil</h3>

Ordens de serviço para assistências técnicas e oficinas. Funciona offline com IndexedDB e sincroniza com o Supabase.

<p>
<img src="https://custom-icon-badges.demolab.com/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
<img src="https://custom-icon-badges.demolab.com/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://custom-icon-badges.demolab.com/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase"/>
</p>

<p>
<a href="https://paulo-carvalho10.github.io/os-facil/"><img src="https://custom-icon-badges.demolab.com/badge/Ver_site-2ea043?style=for-the-badge&logo=link-external&logoColor=white" alt="Ver site"/></a>
<a href="https://github.com/paulo-carvalho10/os-facil"><img src="https://custom-icon-badges.demolab.com/badge/C%C3%B3digo-24292f?style=for-the-badge&logo=code&logoColor=white" alt="Código"/></a>
</p>

</td>
<td width="50%" valign="top">

<h3>🎥 Análise de jogadas</h3>

Visão computacional aplicada ao futebol: detecção e rastreamento de jogadores em vídeo. Feito para a seleção da Iniciação Científica X,Y Soccer IA.

<p>
<img src="https://custom-icon-badges.demolab.com/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://custom-icon-badges.demolab.com/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/>
<img src="https://custom-icon-badges.demolab.com/badge/YOLO-Ultralytics-111F68?style=flat-square&logo=eye&logoColor=white" alt="YOLO Ultralytics"/>
<img src="https://custom-icon-badges.demolab.com/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"/>
</p>

<p>
<a href="https://github.com/paulo-carvalho10/an-lise-futebol"><img src="https://custom-icon-badges.demolab.com/badge/C%C3%B3digo-24292f?style=for-the-badge&logo=code&logoColor=white" alt="Código"/></a>
</p>

</td>
</tr>
</table>

## <img src="https://custom-icon-badges.demolab.com/badge/-Ferramentas-8957e5?style=for-the-badge&logo=tools&logoColor=white" alt="Ferramentas" height="28"/>

**Linguagens**

<p>
<img src="https://custom-icon-badges.demolab.com/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://custom-icon-badges.demolab.com/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://custom-icon-badges.demolab.com/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
<img src="https://custom-icon-badges.demolab.com/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
<img src="https://custom-icon-badges.demolab.com/badge/SQL-336791?style=for-the-badge&logo=database&logoColor=white" alt="SQL"/>
</p>

**Back-end e dados**

<p>
<img src="https://custom-icon-badges.demolab.com/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
<img src="https://custom-icon-badges.demolab.com/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
<img src="https://custom-icon-badges.demolab.com/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
<img src="https://custom-icon-badges.demolab.com/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase"/>
<img src="https://custom-icon-badges.demolab.com/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
<img src="https://custom-icon-badges.demolab.com/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
</p>

**Front-end**

<p>
<img src="https://custom-icon-badges.demolab.com/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
<img src="https://custom-icon-badges.demolab.com/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/>
<img src="https://custom-icon-badges.demolab.com/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
<img src="https://custom-icon-badges.demolab.com/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
<img src="https://custom-icon-badges.demolab.com/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
</p>

**Infra e testes**

<p>
<img src="https://custom-icon-badges.demolab.com/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
<img src="https://custom-icon-badges.demolab.com/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel"/>
<img src="https://custom-icon-badges.demolab.com/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
<img src="https://custom-icon-badges.demolab.com/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest"/>
<img src="https://custom-icon-badges.demolab.com/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" alt="Vitest"/>
<img src="https://custom-icon-badges.demolab.com/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" alt="Playwright"/>
</p>

## <img src="https://custom-icon-badges.demolab.com/badge/-No_GitHub-24292f?style=for-the-badge&logo=graph&logoColor=white" alt="No GitHub" height="28"/>

<div align="center">

<p>
<img src="https://streak-stats.demolab.com?user=paulo-carvalho10&theme=github-dark-blue&hide_border=true&locale=pt_BR&date_format=j%20M%5B%20Y%5D&hide_current_streak=true&hide_longest_streak=true" alt="Total de contribuições no GitHub"/>
</p>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2ea043,45:1f6feb,100:0d1117&height=110&section=footer" width="100%" alt=""/>
