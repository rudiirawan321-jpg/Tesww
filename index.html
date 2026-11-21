<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Catatan Cepat</title>
  <style>
    body {
      font-family: system-ui, sans-serif;
      max-width: 520px;
      margin: 2rem auto;
      padding: 0 1rem;
      background: #f6f7f9;
      color: #1f2937;
    }
    .card {
      background: #ffffff;
      padding: 1.25rem;
      border-radius: 12px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.06);
    }
    input, button {
      padding: 0.65rem 0.8rem;
      font-size: 1rem;
      border-radius: 8px;
      border: 1px solid #d1d5db;
    }
    button {
      background: #111827;
      color: #fff;
      border: none;
      cursor: pointer;
    }
    ul { padding-left: 1.2rem; }
  </style>
</head>
<body>
  <div class="card">
    <h2>Catatan Cepat</h2>
    <form id="noteForm">
      <input id="noteInput" type="text" placeholder="Tulis catatan..." required />
      <button type="submit">Simpan</button>
    </form>
    <ul id="noteList"></ul>
  </div>

  <script>
    const form = document.getElementById("noteForm");
    const input = document.getElementById("noteInput");
    const list = document.getElementById("noteList");
    const STORAGE_KEY = "catatan_cepat_v1";

    const loadNotes = () => JSON.parse(localStorage.getItem(STORAGE_KEY) || "[]");
    const saveNotes = (notes) => localStorage.setItem(STORAGE_KEY, JSON.stringify(notes));

    const render = () => {
      list.innerHTML = "";
      for (const text of loadNotes()) {
        const li = document.createElement("li");
        li.textContent = text;
        list.appendChild(li);
      }
    };

    form.addEventListener("submit", (e) => {
      e.preventDefault();
      const val = input.value.trim();
      if (!val) return;
      const notes = loadNotes();
      notes.unshift(val);
      saveNotes(notes);
      input.value = "";
      render();
    });

    render();
  </script>
</body>
</html>
