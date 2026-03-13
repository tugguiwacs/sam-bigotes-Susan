<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sam Bigotes | El Mejor Sabor de Isla Mujeres</title>
  <meta name="theme-color" content="#7a0f12" />
  <style>
    :root{
      --bg:#0f0f10;
      --bg-soft:#171719;
      --card:#1b1b1e;
      --card-2:#222226;
      --gold:#d4af37;
      --gold-soft:#f1d889;
      --red:#7a0f12;
      --red-2:#a11518;
      --text:#ffffff;
      --muted:#c9c9c9;
      --line:#2d2d33;
      --green:#25D366;
      --shadow:0 12px 34px rgba(0,0,0,.38);
      --radius:20px;
    }

    *{box-sizing:border-box}
    html{scroll-behavior:smooth}

    body{
      margin:0;
      font-family:Arial, Helvetica, sans-serif;
      color:var(--text);
      background:
        radial-gradient(circle at top center, rgba(212,175,55,.08), transparent 30%),
        linear-gradient(180deg, #111214 0%, #0d0d0f 100%);
    }

    .hero{
      position:relative;
      overflow:hidden;
      border-bottom:1px solid rgba(255,255,255,.08);
      background:
        linear-gradient(rgba(9,9,11,.55), rgba(9,9,11,.82)),
        url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;
    }

    .hero::after{
      content:"";
      position:absolute;
      inset:0;
      background:
        radial-gradient(circle at center, rgba(212,175,55,.10), transparent 35%);
      pointer-events:none;
    }

    .hero-inner{
      position:relative;
      z-index:1;
      max-width:1200px;
      margin:0 auto;
      padding:28px 18px 26px;
      text-align:center;
    }

    .brand-badge{
      display:inline-flex;
      align-items:center;
      justify-content:center;
      width:86px;
      height:86px;
      border-radius:50%;
      margin-bottom:14px;
      background:linear-gradient(180deg,#ffd667,#d4af37);
      color:#4a2b00;
      font-weight:900;
      box-shadow:0 10px 28px rgba(0,0,0,.35);
      border:3px solid rgba(255,255,255,.18);
      font-size:14px;
      text-transform:uppercase;
    }

    .hero h1{
      margin:0;
      font-size:clamp(34px, 7vw, 62px);
      line-height:1;
      font-weight:900;
      letter-spacing:1.5px;
      color:var(--gold-soft);
      text-transform:uppercase;
      text-shadow:0 3px 18px rgba(0,0,0,.35);
    }

    .hero .tagline{
      margin-top:12px;
      font-size:clamp(16px, 2.4vw, 24px);
      font-weight:800;
      color:#fff4c8;
      text-transform:uppercase;
      letter-spacing:.6px;
    }

    .hero .meta{
      max-width:900px;
      margin:16px auto 0;
      display:flex;
      flex-wrap:wrap;
      gap:10px;
      justify-content:center;
    }

    .pill{
      padding:10px 14px;
      border-radius:999px;
      background:rgba(255,255,255,.08);
      border:1px solid rgba(255,255,255,.10);
      backdrop-filter: blur(6px);
      color:#fff;
      font-size:13px;
      font-weight:700;
    }

    .wrap{
      max-width:1200px;
      margin:0 auto;
      padding:26px 18px 130px;
    }

    .section-head{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:16px;
      margin:8px 0 18px;
      flex-wrap:wrap;
    }

    .section-title{
      margin:0;
      font-size:30px;
      color:var(--gold-soft);
      text-transform:uppercase;
      font-weight:900;
      letter-spacing:.7px;
    }

    .section-sub{
      color:var(--muted);
      font-size:14px;
    }

    .product-grid{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(255px,1fr));
      gap:18px;
    }

    .card{
      background:
        linear-gradient(180deg, rgba(255,255,255,.02), rgba(255,255,255,.01)),
        var(--card);
      border:1px solid var(--line);
      border-radius:var(--radius);
      overflow:hidden;
      box-shadow:var(--shadow);
      display:flex;
      flex-direction:column;
      min-height:370px;
    }

    .card-image{
      position:relative;
      height:180px;
      background:
        linear-gradient(180deg, rgba(122,15,18,.22), rgba(0,0,0,.15)),
        linear-gradient(135deg,#2b2b30,#1a1a1d);
      display:flex;
      align-items:center;
      justify-content:center;
      color:#8d8d95;
      font-weight:700;
    }

    .card-image img{
      width:100%;
      height:100%;
      object-fit:cover;
      display:block;
    }

    .card-badge{
      position:absolute;
      left:12px;
      top:12px;
      background:rgba(0,0,0,.55);
      color:var(--gold-soft);
      border:1px solid rgba(212,175,55,.35);
      padding:6px 10px;
      border-radius:999px;
      font-size:11px;
      font-weight:900;
      text-transform:uppercase;
      letter-spacing:.5px;
    }

    .card-body{
      padding:16px;
      display:flex;
      flex-direction:column;
      flex:1;
    }

    .card-title{
      margin:0 0 8px;
      font-size:24px;
      font-weight:900;
      line-height:1.1;
    }

    .card-desc{
      color:var(--muted);
      font-size:14px;
      line-height:1.5;
      min-height:42px;
      margin-bottom:16px;
    }

    .card-footer{
      margin-top:auto;
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:12px;
    }

    .price{
      font-size:31px;
      font-weight:900;
      color:var(--gold);
      white-space:nowrap;
    }

    .btn{
      border:none;
      border-radius:14px;
      padding:12px 16px;
      font-weight:900;
      cursor:pointer;
      transition:.2s ease;
      font-size:14px;
    }

    .btn:hover{transform:translateY(-1px)}
    .btn:active{transform:translateY(0)}

    .btn-add{
      background:linear-gradient(180deg,var(--red-2),var(--red));
      color:#fff;
      box-shadow:0 8px 20px rgba(122,15,18,.35);
    }

    .extras-box{
      margin-top:28px;
      background:var(--bg-soft);
      border:1px solid var(--line);
      border-radius:var(--radius);
      box-shadow:var(--shadow);
      overflow:hidden;
    }

    .extras-header{
      padding:16px 18px;
      background:linear-gradient(90deg, rgba(212,175,55,.12), rgba(255,255,255,.02));
      border-bottom:1px solid var(--line);
    }

    .extras-header h3{
      margin:0;
      color:var(--gold-soft);
      font-size:22px;
      text-transform:uppercase;
    }

    .extras-table{
      width:100%;
      border-collapse:collapse;
    }

    .extras-table th,
    .extras-table td{
      padding:15px 18px;
      text-align:left;
      border-bottom:1px solid #2b2b30;
      font-size:15px;
    }

    .extras-table th{
      color:var(--gold-soft);
      background:#111214;
      font-size:13px;
      text-transform:uppercase;
      letter-spacing:.6px;
    }

    .extras-table tr:last-child td{
      border-bottom:none;
    }

    .extras-table td:last-child,
    .extras-table th:last-child{
      text-align:right;
      white-space:nowrap;
    }

    .cart{
      position:fixed;
      right:16px;
      bottom:16px;
      width:min(430px, calc(100% - 32px));
      background:linear-gradient(180deg,#151518,#111214);
      border:1px solid #323239;
      border-radius:22px;
      box-shadow:0 20px 44px rgba(0,0,0,.50);
      overflow:hidden;
      z-index:50;
    }

    .cart-head{
      padding:15px 18px;
      background:linear-gradient(90deg, var(--red), #4c090b);
      color:#fff;
      font-size:21px;
      font-weight:900;
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:8px;
    }

    .cart-count{
      background:rgba(255,255,255,.12);
      padding:6px 10px;
      border-radius:999px;
      font-size:12px;
      font-weight:800;
    }

    .cart-body{
      padding:16px;
      max-height:70vh;
      overflow:auto;
    }

    .cart-empty{
      padding:10px 0 6px;
      color:#bbbbc2;
      font-size:14px;
    }

    .cart-item{
      display:flex;
      justify-content:space-between;
      gap:10px;
      padding:12px 0;
      border-bottom:1px solid #26262b;
    }

    .cart-item:last-child{
      border-bottom:none;
    }

    .ci-name{
      font-size:15px;
      font-weight:800;
    }

    .ci-meta{
      color:#b9b9bf;
      font-size:12px;
      margin-top:4px;
    }

    .qty{
      display:flex;
      align-items:center;
      gap:8px;
      margin-top:8px;
    }

    .qty button{
      width:28px;
      height:28px;
      border:none;
      border-radius:8px;
      cursor:pointer;
      background:#2a2a30;
      color:#fff;
      font-size:16px;
      font-weight:900;
    }

    .ci-total{
      color:var(--gold-soft);
      font-size:16px;
      font-weight:900;
      white-space:nowrap;
    }

    .summary{
      margin-top:14px;
      border-top:1px solid #2b2b31;
      padding-top:14px;
      color:#f1f1f1;
      font-size:14px;
      line-height:1.9;
    }

    .summary strong{
      color:var(--gold-soft);
      font-size:22px;
    }

    .form-title{
      margin:16px 0 8px;
      color:#fff3c8;
      font-size:15px;
      font-weight:900;
      text-transform:uppercase;
      letter-spacing:.5px;
    }

    label{
      display:block;
      margin:12px 0 6px;
      color:#dddddf;
      font-size:13px;
      font-weight:800;
    }

    input, textarea, select{
      width:100%;
      border:1px solid #35353b;
      background:#0d0e10;
      color:#fff;
      border-radius:14px;
      padding:12px 13px;
      font-size:14px;
      outline:none;
    }

    textarea{
      resize:vertical;
      min-height:72px;
    }

    .btn-whats{
      margin-top:16px;
      width:100%;
      border:none;
      border-radius:16px;
      padding:15px;
      background:linear-gradient(180deg,#29d868,#1faf52);
      color:#fff;
      font-size:16px;
      font-weight:900;
      cursor:pointer;
      box-shadow:0 12px 24px rgba(37,211,102,.22);
    }

    .mini-note{
      margin-top:10px;
      text-align:center;
      color:#bdbdc3;
      font-size:12px;
      line-height:1.5;
    }

    .status-link{
      display:block;
      margin-top:10px;
      color:#ffd77b;
      text-align:center;
      font-size:12px;
      text-decoration:none;
    }

    .status-link:hover{text-decoration:underline}

    .mobile-pad{
      height:120px;
    }

    @media (max-width: 760px){
      .hero-inner{padding-top:22px}
      .cart{
        left:12px;
        right:12px;
        bottom:12px;
        width:auto;
      }
      .price{font-size:28px}
    }
  </style>
</head>
<body>
  <header class="hero">
    <div class="hero-inner">
      <div class="brand-badge">Sam<br>Bigotes</div>
      <h1>SAM BIGOTES</h1>
      <div class="tagline">El Mejor Sabor de Isla Mujeres</div>
      <div class="meta">
        <div class="pill">📞 998 161 7895</div>
        <div class="pill">📞 998 224 6406</div>
        <div class="pill">🕛 12:00 PM - 7:00 PM</div>
        <div class="pill">🚚 Servicio a domicilio: $20</div>
        <div class="pill">💳 Efectivo, tarjeta o transferencia</div>
        <div class="pill">📘 Facebook: Sam Bigotes</div>
      </div>
    </div>
  </header>

  <main class="wrap">
    <div class="section-head">
      <div>
        <h2 class="section-title">Pollos</h2>
        <div class="section-sub">Arma tu pedido y confírmalo por WhatsApp.</div>
      </div>
    </div>

    <section id="productGrid" class="product-grid"></section>

    <section class="extras-box">
      <div class="extras-header">
        <h3>Extras</h3>
      </div>
      <table class="extras-table">
        <thead>
          <tr>
            <th>Producto</th>
            <th>Precio</th>
          </tr>
        </thead>
        <tbody id="extrasBody"></tbody>
      </table>
    </section>

    <div class="mobile-pad"></div>
  </main>

  <aside class="cart">
    <div class="cart-head">
      <span>Tu pedido</span>
      <span class="cart-count" id="cartCount">0 artículos</span>
    </div>

    <div class="cart-body">
      <div id="cartItems" class="cart-empty">Tu carrito está vacío.</div>

      <div class="summary">
        Subtotal: $<span id="subtotal">0</span><br>
        Servicio: $<span id="envio">0</span><br>
        <strong>Total: $<span id="total">0</span></strong>
      </div>

      <div class="form-title">Datos del cliente</div>

      <label for="nombre">Nombre</label>
      <input type="text" id="nombre" placeholder="Tu nombre">

      <label for="tel">Teléfono</label>
      <input type="text" id="tel" placeholder="Tu teléfono">

      <label for="tipoEntrega">Tipo de entrega</label>
      <select id="tipoEntrega">
        <option value="DOMICILIO">Domicilio</option>
        <option value="RECOGER">Recoger</option>
      </select>

      <label for="direccion">Dirección</label>
      <input type="text" id="direccion" placeholder="Tu dirección">

      <label for="referencias">Referencias</label>
      <textarea id="referencias" placeholder="Color de casa, punto de referencia, etc."></textarea>

      <label for="metodoPago">Método de pago</label>
      <select id="metodoPago">
        <option value="EFECTIVO">Efectivo</option>
        <option value="TARJETA">Tarjeta</option>
        <option value="TRANSFERENCIA">Transferencia</option>
      </select>

      <button class="btn-whats" onclick="confirmarPedido()">Confirmar por WhatsApp</button>
      <div class="mini-note">
        El servicio a domicilio de $20 solo aplica en pedidos a domicilio.
      </div>
      <a class="status-link" id="statusHint" href="javascript:void(0)">Tu folio se genera al confirmar el pedido.</a>
    </div>
  </aside>

  <script>
    const API_BASE = "https://script.google.com/macros/s/AKfycbytXopsNxdQxJU6G0cMP7Y1BJMwyVX_OyO_K1HBL9_WKFCOUL69jZb3pN9UuWsa7AuB/exec";

    let MENU = [];
    let CONFIG = {};
    let CART = [];

    async function loadConfig() {
      try {
        const res = await fetch(API_BASE + "?action=config");
        const data = await res.json();
        if (data.ok) CONFIG = data.config || {};
      } catch (err) {
        console.error("Error config:", err);
      }
    }

    async function loadMenu() {
      try {
        const res = await fetch(API_BASE + "?action=menu");
        const data = await res.json();

        if (!data.ok) {
          alert("No se pudo cargar el menú.");
          return;
        }

        MENU = data.items || [];
        renderProducts();
        renderExtras();
      } catch (err) {
        console.error("Error menú:", err);
        alert("Error al cargar productos.");
      }
    }

    function renderProducts() {
      const grid = document.getElementById("productGrid");
      grid.innerHTML = "";

      const pollos = MENU.filter(p => String(p.categoria || "").toUpperCase() === "POLLO");

      pollos.forEach(item => {
        const div = document.createElement("article");
        div.className = "card";

        div.innerHTML = `
          <div class="card-image">
            <div class="card-badge">${item.categoria}</div>
            ${
              item.imagen
                ? `<img src="${item.imagen}" alt="${escapeHtml(item.nombre)}">`
                : `Imagen próximamente`
            }
          </div>
          <div class="card-body">
            <h3 class="card-title">${escapeHtml(item.nombre)}</h3>
            <div class="card-desc">${escapeHtml(item.descripcion || "")}</div>
            <div class="card-footer">
              <div class="price">$${Number(item.precio)}</div>
              <button class="btn btn-add" onclick="addToCart('${item.id}')">Agregar</button>
            </div>
          </div>
        `;

        grid.appendChild(div);
      });
    }

    function renderExtras() {
      const body = document.getElementById("extrasBody");
      body.innerHTML = "";

      const extras = MENU.filter(p => String(p.categoria || "").toUpperCase() === "EXTRAS");

      extras.forEach(item => {
        const tr = document.createElement("tr");
        tr.innerHTML = `
          <td>${escapeHtml(item.nombre)}</td>
          <td>$${Number(item.precio)}</td>
        `;
        body.appendChild(tr);
      });
    }

    function addToCart(id) {
      const product = MENU.find(p => p.id === id);
      if (!product) return;

      const existing = CART.find(x => x.id === id);
      if (existing) {
        existing.qty += 1;
      } else {
        CART.push({
          id: product.id,
          nombre: product.nombre,
          precio: Number(product.precio),
          qty: 1
        });
      }

      renderCart();
    }

    function changeQty(id, delta) {
      const item = CART.find(x => x.id === id);
      if (!item) return;

      item.qty += delta;

      if (item.qty <= 0) {
        CART = CART.filter(x => x.id !== id);
      }

      renderCart();
    }

    function renderCart() {
      const box = document.getElementById("cartItems");
      const count = document.getElementById("cartCount");

      if (CART.length === 0) {
        box.innerHTML = "Tu carrito está vacío.";
        count.textContent = "0 artículos";
        document.getElementById("subtotal").textContent = "0";
        document.getElementById("envio").textContent = "0";
        document.getElementById("total").textContent = "0";
        return;
      }

      count.textContent = `${CART.reduce((a,b)=>a+b.qty,0)} artículos`;

      let subtotal = 0;
      box.innerHTML = "";

      CART.forEach(item => {
        const importe = item.precio * item.qty;
        subtotal += importe;

        const row = document.createElement("div");
        row.className = "cart-item";
        row.innerHTML = `
          <div>
            <div class="ci-name">${escapeHtml(item.nombre)}</div>
            <div class="ci-meta">$${item.precio} c/u</div>
            <div class="qty">
              <button onclick="changeQty('${item.id}',-1)">-</button>
              <span>${item.qty}</span>
              <button onclick="changeQty('${item.id}',1)">+</button>
            </div>
          </div>
          <div class="ci-total">$${importe}</div>
        `;
        box.appendChild(row);
      });

      const tipoEntrega = document.getElementById("tipoEntrega").value;
      const envio = tipoEntrega === "DOMICILIO" ? Number(CONFIG.ENVIO_FIJO || 20) : 0;
      const total = subtotal + envio;

      document.getElementById("subtotal").textContent = subtotal;
      document.getElementById("envio").textContent = envio;
      document.getElementById("total").textContent = total;
    }

    async function confirmarPedido() {
      const nombre = document.getElementById("nombre").value.trim();
      const tel = document.getElementById("tel").value.trim();
      const direccion = document.getElementById("direccion").value.trim();
      const referencias = document.getElementById("referencias").value.trim();
      const tipoEntrega = document.getElementById("tipoEntrega").value;
      const metodoPago = document.getElementById("metodoPago").value;

      if (!nombre || !tel) {
        alert("Captura tu nombre y teléfono.");
        return;
      }

      if (tipoEntrega === "DOMICILIO" && !direccion) {
        alert("Captura la dirección para pedidos a domicilio.");
        return;
      }

      if (CART.length === 0) {
        alert("Tu carrito está vacío.");
        return;
      }

      const payload = {
        action: "crearPedido",
        nombre,
        tel,
        direccion,
        referencias,
        tipoEntrega,
        metodoPago,
        items: CART
      };

      try {
        const res = await fetch(API_BASE, {
          method: "POST",
          headers: {
            "Content-Type": "application/json"
          },
          body: JSON.stringify(payload)
        });

        const data = await res.json();

        if (!data.ok) {
          alert(data.error || "No se pudo generar el pedido.");
          return;
        }

        const hint = document.getElementById("statusHint");
        hint.textContent = "Folio generado: " + data.orderId;
        hint.href = API_BASE + "?action=status&orderId=" + encodeURIComponent(data.orderId);

        alert("Pedido creado con éxito. Folio: " + data.orderId);
        window.open(data.whatsapp_url, "_blank");
      } catch (err) {
        console.error("Error pedido:", err);
        alert("Error al enviar el pedido.");
      }
    }

    function escapeHtml(str) {
      return String(str)
        .replaceAll("&","&amp;")
        .replaceAll("<","&lt;")
        .replaceAll(">","&gt;")
        .replaceAll('"',"&quot;")
        .replaceAll("'","&#039;");
    }

    document.getElementById("tipoEntrega").addEventListener("change", renderCart);

    Promise.all([loadConfig(), loadMenu()]).then(() => renderCart());
  </script>
</body>
</html>
