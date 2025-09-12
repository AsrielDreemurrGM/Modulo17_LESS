<h2>Project Overview</h2>
<p>
  Este README também está disponível em <a href="./README.pt-br.md">Português</a>.
</p>
<p>
  This project is a responsive profile page built with <strong>LESS</strong>.
  It demonstrates the use of variables, maps, mixins, media queries, and escaping.
  LESS maps are used to centralize and manage the color palette, making it easier
  to apply and change themes across the stylesheet. Feather Icons were integrated
  for UI elements, and the <strong>less-watch-compiler</strong> plugin was used
  to automate the compilation process.
</p>
<p>
  🔗 Live Demo: <a href="https://less-profile-page-asrieldreemurrgm.vercel.app/" target="_blank">View on Vercel</a>
</p>
<h2>Technologies Used</h2>
<ul>
  <li>HTML5</li>
  <li>CSS3 / LESS</li>
  <li>Feather Icons</li>
  <li>LESS Watch Compiler</li>
  <li>copyfiles (copy HTML and images)</li>
  <li>chokidar-cli (watch for file changes)</li>
  <li>concurrently (run multiple scripts simultaneously)</li>
</ul>
<h2>How to Run</h2>
<ol>
  <li>Clone the repository.</li>
  <li>Install dependencies with <code>npm install</code>.</li>
  <li>Run the development script with <code>npm run dev</code> to watch and compile LESS, copy HTML, and images.</li>
  <li>Or run <code>npm run build</code> to build once for deployment.</li>
  <li>Open <code>build/index.html</code> (or <code>index.html</code> in dev) in your browser to view the profile page.</li>
</ol>
