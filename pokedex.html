<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pokédex ✨</title>
  <link href="https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700;800;900&display=swap" rel="stylesheet" />
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --pink-50: #fff0f6;
      --pink-100: #ffd6e7;
      --pink-200: #ffadd2;
      --pink-300: #ff85c2;
      --pink-400: #f759ab;
      --pink-500: #eb2f96;
      --pink-light: #fff5f8;
      --card-bg: #fff8fb;
      --border: #ffc0dd;
      --text-dark: #6b2d4e;
      --text-mid: #a0537a;
      --text-light: #d48aaa;
      --shadow: 0 4px 20px rgba(247,89,171,0.12);
      --r: 16px;
    }

    body {
      font-family: 'Nunito', sans-serif;
      background: #fff5f9;
      color: var(--text-dark);
      min-height: 100vh;
      display: flex;
      justify-content: center;
      padding: 2rem 1rem;
    }

    .pokedex { max-width: 680px; width: 100%; }

    /* ── Header ── */
    .header { text-align: center; margin-bottom: 1.5rem; }
    .header h1 { font-size: 32px; font-weight: 900; color: var(--pink-400); letter-spacing: -0.5px; }
    .header p { font-size: 14px; color: var(--text-light); margin-top: 4px; }

    /* ── Search bar ── */
    .search-bar { display: flex; gap: 8px; margin-bottom: 1.2rem; }
    .search-bar input {
      flex: 1; padding: 10px 16px; border: 1.5px solid var(--border);
      border-radius: 50px; font-family: 'Nunito', sans-serif; font-size: 14px;
      background: var(--pink-50); color: var(--text-dark); outline: none;
      transition: border-color 0.2s;
    }
    .search-bar input:focus { border-color: var(--pink-400); }
    .search-bar input::placeholder { color: var(--text-light); }
    .search-bar button {
      padding: 10px 20px; background: var(--pink-400); color: white;
      border: none; border-radius: 50px; font-family: 'Nunito', sans-serif;
      font-size: 14px; font-weight: 700; cursor: pointer; transition: background 0.2s;
    }
    .search-bar button:hover { background: var(--pink-500); }

    /* ── Quick chips ── */
    .quick-list { display: flex; flex-wrap: wrap; gap: 6px; margin-bottom: 1.4rem; }
    .chip {
      padding: 4px 12px; border-radius: 50px; font-size: 12px; font-weight: 700;
      background: var(--pink-100); color: var(--text-mid); border: 1px solid var(--border);
      cursor: pointer; transition: background 0.15s; text-transform: capitalize;
    }
    .chip:hover { background: var(--pink-200); }

    /* ── Pokémon detail card ── */
    .pokemon-card {
      background: var(--card-bg); border: 1.5px solid var(--border);
      border-radius: var(--r); padding: 1.4rem; box-shadow: var(--shadow);
      animation: fadeIn 0.3s ease;
    }
    @keyframes fadeIn { from { opacity: 0; transform: translateY(8px); } to { opacity: 1; transform: none; } }

    .poke-header { display: flex; gap: 1.2rem; align-items: center; margin-bottom: 1.2rem; }
    .poke-img-wrap {
      width: 110px; height: 110px; flex-shrink: 0;
      background: linear-gradient(135deg, var(--pink-100), var(--pink-50));
      border-radius: 50%; display: flex; align-items: center; justify-content: center;
      border: 2px solid var(--pink-200);
    }
    .poke-img-wrap img { width: 90px; height: 90px; image-rendering: pixelated; }
    .poke-info { flex: 1; }
    .poke-num { font-size: 12px; color: var(--text-light); font-weight: 700; }
    .poke-name { font-size: 24px; font-weight: 900; text-transform: capitalize; color: var(--text-dark); line-height: 1.1; }
    .types { display: flex; gap: 6px; margin-top: 6px; flex-wrap: wrap; }
    .type-badge {
      padding: 3px 10px; border-radius: 50px; font-size: 11px; font-weight: 800;
      text-transform: uppercase; letter-spacing: 0.5px;
    }

    /* ── Type color map ── */
    .type-fire     { background: #ffe8d6; color: #c9440c; }
    .type-water    { background: #ddefff; color: #1a6eb5; }
    .type-grass    { background: #e0f5d8; color: #3a7d24; }
    .type-electric { background: #fff8d4; color: #a38000; }
    .type-psychic  { background: #ffe0f0; color: #b8005a; }
    .type-normal   { background: #efefef; color: #6b6b6b; }
    .type-poison   { background: #f0e0ff; color: #7a1fb5; }
    .type-fighting { background: #ffddd4; color: #a33a20; }
    .type-rock     { background: #f0ede0; color: #7a6a30; }
    .type-ground   { background: #f5ecd4; color: #9a7230; }
    .type-flying   { background: #e8eeff; color: #2040b0; }
    .type-bug      { background: #e8f5d4; color: #4a7a10; }
    .type-ghost    { background: #e8e0f5; color: #5c3090; }
    .type-steel    { background: #e8f0f5; color: #3060a0; }
    .type-ice      { background: #d8f4ff; color: #1a7a9a; }
    .type-dragon   { background: #e0e8ff; color: #2020b0; }
    .type-dark     { background: #e0dcd8; color: #402810; }
    .type-fairy    { background: #ffe0f5; color: #c0408a; }
    .type-default  { background: var(--pink-100); color: var(--text-mid); }

    /* ── Flavor text ── */
    .poke-flavor {
      font-size: 13px; color: var(--text-mid); font-style: italic;
      margin-bottom: 1.2rem; line-height: 1.5;
      background: var(--pink-50); border-radius: 10px;
      padding: 10px 12px; border-left: 3px solid var(--pink-200);
    }

    /* ── Section title ── */
    .section-title {
      font-size: 13px; font-weight: 800; color: var(--text-light);
      text-transform: uppercase; letter-spacing: 1px; margin-bottom: 10px;
    }

    /* ── Info grid (height / weight / exp) ── */
    .info-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 8px; margin-bottom: 1.2rem; }
    .info-cell { background: var(--pink-50); border: 1px solid var(--border); border-radius: 10px; padding: 8px 10px; text-align: center; }
    .info-cell .val { font-size: 15px; font-weight: 800; color: var(--text-dark); }
    .info-cell .lbl { font-size: 11px; color: var(--text-light); font-weight: 700; text-transform: uppercase; letter-spacing: 0.4px; margin-top: 1px; }

    /* ── Abilities ── */
    .abilities-row { display: flex; flex-wrap: wrap; gap: 6px; margin-bottom: 1.2rem; }
    .ability-chip {
      padding: 4px 12px; background: var(--pink-100); border: 1px solid var(--border);
      border-radius: 50px; font-size: 12px; font-weight: 700; color: var(--text-mid);
      text-transform: capitalize;
    }
    .ability-chip.hidden { background: #fff0ff; border-color: #d8aaee; color: #8040a0; }

    /* ── Base stats ── */
    .stats-list { margin-bottom: 1.2rem; }
    .stat-row { display: flex; align-items: center; gap: 10px; margin-bottom: 7px; }
    .stat-name { font-size: 12px; font-weight: 700; color: var(--text-light); text-transform: uppercase; letter-spacing: 0.4px; min-width: 52px; }
    .stat-val { font-size: 13px; font-weight: 800; color: var(--text-dark); min-width: 30px; text-align: right; }
    .stat-bar-wrap { flex: 1; height: 7px; background: var(--pink-100); border-radius: 4px; overflow: hidden; }
    .stat-bar { height: 100%; border-radius: 4px; background: linear-gradient(90deg, var(--pink-300), var(--pink-400)); transition: width 0.6s ease; }
    .stat-bar.high { background: linear-gradient(90deg, #73d893, #2da855); }
    .stat-bar.med  { background: linear-gradient(90deg, #ffd97d, #e6a500); }

    /* ── Evolution chain ── */
    .evo-chain { display: flex; align-items: center; flex-wrap: wrap; gap: 4px; justify-content: center; }
    .evo-step {
      display: flex; flex-direction: column; align-items: center;
      cursor: pointer; padding: 8px; border-radius: 12px;
      transition: background 0.15s; border: 1.5px solid transparent;
    }
    .evo-step:hover { background: var(--pink-100); border-color: var(--border); }
    .evo-step.current { background: var(--pink-100); border-color: var(--pink-300); }
    .evo-img-wrap {
      width: 56px; height: 56px; background: var(--pink-50); border-radius: 50%;
      display: flex; align-items: center; justify-content: center;
      border: 1.5px solid var(--pink-200); margin-bottom: 4px;
    }
    .evo-img-wrap img { width: 44px; height: 44px; image-rendering: pixelated; }
    .evo-name { font-size: 11px; font-weight: 800; color: var(--text-mid); text-transform: capitalize; }
    .evo-arrow { font-size: 20px; color: var(--pink-300); margin: 0 2px; }

    /* ── Grid view ── */
    .grid-view { display: grid; grid-template-columns: repeat(auto-fill, minmax(100px, 1fr)); gap: 10px; }
    .grid-card {
      background: var(--card-bg); border: 1.5px solid var(--border); border-radius: 12px;
      padding: 10px 6px; text-align: center; cursor: pointer;
      transition: transform 0.15s, box-shadow 0.15s; box-shadow: var(--shadow);
    }
    .grid-card:hover { transform: translateY(-3px); box-shadow: 0 8px 24px rgba(247,89,171,0.18); }
    .grid-card img { width: 60px; height: 60px; image-rendering: pixelated; }
    .grid-card .gc-num  { font-size: 10px; color: var(--text-light); font-weight: 700; }
    .grid-card .gc-name { font-size: 12px; font-weight: 800; color: var(--text-dark); text-transform: capitalize; margin-top: 2px; }

    /* ── Misc ── */
    .loading   { text-align: center; padding: 2rem; color: var(--text-light); font-size: 14px; font-weight: 700; }
    .error-msg { background: #fff0f3; border: 1px solid #ffb3c6; border-radius: 10px; padding: 10px 14px; color: #c0305a; font-size: 13px; font-weight: 700; text-align: center; }
    .back-btn  {
      display: inline-flex; align-items: center; gap: 6px; padding: 6px 14px;
      background: var(--pink-50); border: 1.5px solid var(--border); border-radius: 50px;
      font-family: 'Nunito', sans-serif; font-size: 13px; font-weight: 700; color: var(--text-mid);
      cursor: pointer; margin-bottom: 1rem; transition: background 0.15s;
    }
    .back-btn:hover { background: var(--pink-100); }
  </style>
</head>
<body>

<div class="pokedex">
  <div class="header">
    <h1>✨ Pokédex</h1>
    <p>Busque qualquer Pokémon e explore seus detalhes</p>
  </div>

  <!-- Search bar -->
  <div class="search-bar">
    <input type="text" id="searchInput" placeholder="Nome ou número (ex: pikachu, 25)" />
    <button onclick="searchPokemon()">Buscar</button>
  </div>

  <!-- Popular quick-access chips -->
  <div class="quick-list" id="quickList"></div>

  <!-- Dynamic content area -->
  <div id="mainContent">
    <div class="loading">Carregando lista de Pokémon...</div>
  </div>
</div>

<script>
  /* ── Constants ── */
  const POPULAR = [
    'pikachu','eevee','charmander','bulbasaur','squirtle',
    'mewtwo','gengar','snorlax','lucario','garchomp',
    'sylveon','umbreon','espeon','glaceon','jolteon'
  ];

  let allPokemon = [];   // list of { name, id } for the grid

  /* ── Helpers ── */

  /** Map a type name to its CSS class */
  function typeClass(t) {
    const known = ['fire','water','grass','electric','psychic','normal','poison',
                   'fighting','rock','ground','flying','bug','ghost','steel',
                   'ice','dragon','dark','fairy'];
    return known.includes(t) ? 'type-' + t : 'type-default';
  }

  /** Return stat bar color class */
  function statColor(val) {
    if (val >= 100) return 'high';
    if (val >= 60)  return 'med';
    return '';
  }

  /** Stat bar width as percentage (max 255) */
  function statWidth(val) { return Math.min(100, Math.round((val / 255) * 100)); }

  /** dm → metres */
  function formatHeight(dm) { return (dm / 10).toFixed(1) + ' m'; }

  /** hg → kilograms */
  function formatWeight(hg) { return (hg / 10).toFixed(1) + ' kg'; }

  /** Fetch JSON and throw on non-ok responses */
  async function fetchJSON(url) {
    const r = await fetch(url);
    if (!r.ok) throw new Error('Não encontrado');
    return r.json();
  }

  /** Extract an English flavor text entry from a species resource */
  async function getFlavorText(species) {
    try {
      const entries = species.flavor_text_entries.filter(e => e.language.name === 'en');
      if (entries.length)
        return entries[entries.length - 1].flavor_text.replace(/\f/g, ' ');
    } catch (e) {}
    return '';
  }

  /** Walk an evolution chain and return an ordered list of species names */
  async function getEvolutionChain(species) {
    try {
      const evo = await fetchJSON(species.evolution_chain.url);
      const chain = [];
      let node = evo.chain;
      while (node) {
        chain.push(node.species.name);
        node = node.evolves_to && node.evolves_to[0];
      }
      return chain;
    } catch (e) { return []; }
  }

  /** Fetch sprite + id for each name in an evolution chain */
  async function fetchEvoImages(names) {
    return Promise.all(names.map(async name => {
      try {
        const d = await fetchJSON(`https://pokeapi.co/api/v2/pokemon/${name}`);
        return {
          name,
          id:  d.id,
          img: d.sprites.other['official-artwork'].front_default || d.sprites.front_default
        };
      } catch (e) { return { name, id: null, img: null }; }
    }));
  }

  /** Abbreviate stat names for compact display */
  function renderStatName(s) {
    const map = {
      hp: 'HP', attack: 'ATK', defense: 'DEF',
      'special-attack': 'SP.ATK', 'special-defense': 'SP.DEF', speed: 'VEL'
    };
    return map[s] || s.toUpperCase();
  }

  /* ── Main Pokémon detail view ── */

  async function showPokemon(nameOrId) {
    const el = document.getElementById('mainContent');
    el.innerHTML = '<div class="loading">Carregando...</div>';

    try {
      /* 1. Base data */
      const data    = await fetchJSON(`https://pokeapi.co/api/v2/pokemon/${nameOrId}`);
      /* 2. Species (for flavor text + evo chain URL) */
      const species = await fetchJSON(data.species.url);
      /* 3. Flavor text */
      const flavor  = await getFlavorText(species);
      /* 4. Evolution chain names */
      const evoNames = await getEvolutionChain(species);
      /* 5. Evolution sprites (only if chain has > 1 stage) */
      const evoData  = evoNames.length > 1 ? await fetchEvoImages(evoNames) : [];

      /* Derived values */
      const img       = data.sprites.other['official-artwork'].front_default || data.sprites.front_default;
      const types     = data.types.map(t => t.type.name);
      const abilities = data.abilities.map(a => ({ name: a.ability.name, hidden: a.is_hidden }));
      const stats     = data.stats.map(s => ({ name: s.stat.name, val: s.base_stat }));

      /* Evolution chain HTML */
      let evoHTML = '';
      if (evoData.length > 1) {
        evoHTML = `<div class="section-title">Cadeia evolutiva</div><div class="evo-chain">`;
        evoData.forEach((e, i) => {
          if (i > 0) evoHTML += `<span class="evo-arrow">→</span>`;
          const isCurrent = (e.name === data.name);
          evoHTML += `
            <div class="evo-step${isCurrent ? ' current' : ''}" onclick="showPokemon('${e.name}')">
              <div class="evo-img-wrap">
                ${e.img
                  ? `<img src="${e.img}" alt="${e.name}">`
                  : '?'}
              </div>
              <div class="evo-name">${e.name}</div>
            </div>`;
        });
        evoHTML += `</div>`;
      }

      /* Render */
      el.innerHTML = `
        <button class="back-btn" onclick="showGrid()">← Voltar</button>
        <div class="pokemon-card">

          <!-- Header: image + name + types -->
          <div class="poke-header">
            <div class="poke-img-wrap">
              <img
                src="${img}"
                alt="${data.name}"
                onerror="this.src='https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/${data.id}.png'"
              >
            </div>
            <div class="poke-info">
              <div class="poke-num">#${String(data.id).padStart(3, '0')}</div>
              <div class="poke-name">${data.name}</div>
              <div class="types">
                ${types.map(t => `<span class="type-badge ${typeClass(t)}">${t}</span>`).join('')}
              </div>
            </div>
          </div>

          <!-- Flavor text -->
          ${flavor ? `<div class="poke-flavor">"${flavor}"</div>` : ''}

          <!-- Quick stats -->
          <div class="info-grid">
            <div class="info-cell"><div class="val">${formatHeight(data.height)}</div><div class="lbl">Altura</div></div>
            <div class="info-cell"><div class="val">${formatWeight(data.weight)}</div><div class="lbl">Peso</div></div>
            <div class="info-cell"><div class="val">${data.base_experience || '—'}</div><div class="lbl">Exp. Base</div></div>
          </div>

          <!-- Abilities -->
          <div class="section-title">Habilidades</div>
          <div class="abilities-row">
            ${abilities.map(a =>
              `<span class="ability-chip${a.hidden ? ' hidden' : ''}" title="${a.hidden ? 'Habilidade oculta' : ''}">
                ${a.name}${a.hidden ? ' ✦' : ''}
              </span>`
            ).join('')}
          </div>

          <!-- Base stats -->
          <div class="section-title">Estatísticas base</div>
          <div class="stats-list">
            ${stats.map(s => `
              <div class="stat-row">
                <span class="stat-name">${renderStatName(s.name)}</span>
                <span class="stat-val">${s.val}</span>
                <div class="stat-bar-wrap">
                  <div class="stat-bar ${statColor(s.val)}" style="width:${statWidth(s.val)}%"></div>
                </div>
              </div>
            `).join('')}
          </div>

          <!-- Evolution chain -->
          ${evoHTML}

        </div>`;

    } catch (e) {
      el.innerHTML = `<div class="error-msg">Pokémon não encontrado. Tente outro nome ou número!</div>`;
    }
  }

  /* ── Search ── */

  function searchPokemon() {
    const val = document.getElementById('searchInput').value.trim().toLowerCase();
    if (val) showPokemon(val);
  }

  document.getElementById('searchInput').addEventListener('keydown', e => {
    if (e.key === 'Enter') searchPokemon();
  });

  /* ── Grid view (first 151) ── */

  function showGrid() {
    const el = document.getElementById('mainContent');
    el.innerHTML = `
      <div class="grid-view">
        ${allPokemon.slice(0, 151).map(p => `
          <div class="grid-card" onclick="showPokemon('${p.name}')">
            <div class="gc-num">#${String(p.id).padStart(3, '0')}</div>
            <img
              src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/official-artwork/${p.id}.png"
              onerror="this.src='https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/${p.id}.png'"
              alt="${p.name}"
              loading="lazy"
            >
            <div class="gc-name">${p.name}</div>
          </div>
        `).join('')}
      </div>`;
  }

  /* ── Initialisation ── */

  async function init() {
    /* Populate quick-access chips */
    document.getElementById('quickList').innerHTML =
      POPULAR.map(n => `<span class="chip" onclick="showPokemon('${n}')">${n}</span>`).join('');

    /* Fetch list of first-gen Pokémon */
    try {
      const data  = await fetchJSON('https://pokeapi.co/api/v2/pokemon?limit=151');
      allPokemon  = data.results.map((p, i) => ({ ...p, id: i + 1 }));
      showGrid();
    } catch (e) {
      document.getElementById('mainContent').innerHTML =
        '<div class="error-msg">Erro ao carregar lista. Verifique sua conexão.</div>';
    }
  }

  init();
</script>
</body>
</html>
