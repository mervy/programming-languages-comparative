<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Comparativo de 9 Linguagens de Programação</title>
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    font-family: 'Segoe UI', Tahoma, sans-serif;
    background: linear-gradient(135deg, #1e1e2f 0%, #2a2a40 100%);
    color: #e8e8f0;
    line-height: 1.5;
    padding: 20px;
  }
  header {
    text-align: center;
    padding: 30px 20px;
    background: rgba(255,255,255,0.03);
    border-radius: 12px;
    margin-bottom: 25px;
    border: 1px solid rgba(255,255,255,0.08);
  }
  header h1 {
    font-size: 2.2em;
    background: linear-gradient(90deg, #64b5f6, #ba68c8, #ff8a65);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-bottom: 10px;
  }
  header p { color: #b0b0c8; max-width: 900px; margin: 0 auto; }

  .controls {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
    margin-bottom: 20px;
    align-items: center;
  }
  .controls input, .controls select {
    padding: 10px 14px;
    background: #2a2a40;
    border: 1px solid #444;
    color: #fff;
    border-radius: 8px;
    font-size: 14px;
  }
  .controls input { flex: 1; min-width: 200px; }

  .table-wrapper {
    overflow-x: auto;
    background: rgba(255,255,255,0.02);
    border-radius: 12px;
    border: 1px solid rgba(255,255,255,0.08);
  }
  table {
    border-collapse: collapse;
    width: 100%;
    min-width: 1800px;
  }
  th, td {
    border: 1px solid rgba(255,255,255,0.1);
    padding: 12px;
    vertical-align: top;
    font-size: 13px;
  }
  th {
    background: #3a3a55;
    position: sticky;
    top: 0;
    z-index: 2;
    text-align: center;
    font-weight: 600;
  }
  th.topic {
    background: #4a4a70;
    min-width: 140px;
    text-align: left;
    position: sticky;
    left: 0;
    z-index: 3;
  }
  td.topic-cell {
    background: #35354f;
    font-weight: bold;
    color: #ffd54f;
    position: sticky;
    left: 0;
    z-index: 1;
  }
  td pre {
    background: #0f0f1a;
    color: #9cdcfe;
    padding: 8px;
    border-radius: 6px;
    overflow-x: auto;
    font-size: 11.5px;
    margin: 4px 0;
    white-space: pre;
    font-family: 'Consolas', monospace;
  }
  td code {
    background: #0f0f1a;
    color: #ce9178;
    padding: 1px 5px;
    border-radius: 4px;
    font-size: 12px;
  }
  .lang-header {
    font-size: 15px;
    font-weight: bold;
  }
  .lang-js { color: #f7df1e; }
  .lang-php { color: #8993be; }
  .lang-go { color: #00add8; }
  .lang-py { color: #3776ab; }
  .lang-rust { color: #dea584; }
  .lang-c { color: #a8b9cc; }
  .lang-cpp { color: #00599c; }
  .lang-cs { color: #9b4f96; }
  .lang-java { color: #f89820; }

  .badge {
    display: inline-block;
    padding: 2px 8px;
    border-radius: 10px;
    font-size: 11px;
    background: #4a4a70;
    margin: 2px;
  }
  a { color: #64b5f6; text-decoration: none; }
  a:hover { text-decoration: underline; }

  footer {
    text-align: center;
    margin-top: 30px;
    color: #888;
    font-size: 13px;
  }
</style>
</head>
<body>

<header>
  <h1>⚡ Comparativo de 9 Linguagens de Programação</h1>
  <p>
    Este projeto reúne, em uma única tabela interativa, um panorama comparativo entre
    <strong>JavaScript, PHP, Golang, Python, Rust, C, C++, C# e Java</strong>.
    O objetivo é oferecer um material de consulta rápida para desenvolvedores que desejam
    entender como cada linguagem aborda conceitos fundamentais — desde sua história e
    instalação até estruturas de controle, manipulação de strings, acesso a bancos de
    dados e casos de uso. A tabela pode ser filtrada por tópico e pesquisada por palavra-chave,
    facilitando estudos, revisões e comparações lado a lado.
  </p>
</header>

<div class="controls">
  <input type="text" id="search" placeholder="🔍 Buscar palavra-chave (ex: loop, string, postgres)...">
  <select id="topicFilter">
    <option value="">-- Todos os tópicos --</option>
  </select>
</div>

<div class="table-wrapper">
  <table id="mainTable">
    <thead>
      <tr>
        <th class="topic">Tópico</th>
        <th><span class="lang-header lang-js">JavaScript</span></th>
        <th><span class="lang-header lang-php">PHP</span></th>
        <th><span class="lang-header lang-go">Golang</span></th>
        <th><span class="lang-header lang-py">Python</span></th>
        <th><span class="lang-header lang-rust">Rust</span></th>
        <th><span class="lang-header lang-c">C</span></th>
        <th><span class="lang-header lang-cpp">C++</span></th>
        <th><span class="lang-header lang-cs">C#</span></th>
        <th><span class="lang-header lang-java">Java</span></th>
      </tr>
    </thead>
    <tbody id="tableBody"></tbody>
  </table>
</div>

<footer>
  Projeto educacional — comparativo entre 9 linguagens · Atualizado em 2026
</footer>

<script>
/* =========================================================
   DADOS DO COMPARATIVO
   Cada linha = um tópico; cada coluna = uma linguagem
   ========================================================= */
const data = [
  {
    topic: "História (quem, quando, por quê)",
    js: "Criado por <b>Brendan Eich</b> em <b>1995</b> na Netscape. Nasceu em 10 dias para dar interatividade aos navegadores, originalmente chamado Mocha/LiveScript.",
    php: "Criado por <b>Rasmus Lerdorf</b> em <b>1994</b>. Começou como um conjunto de scripts Perl para rastrear visitas ao seu currículo; evoluiu para linguagem de web dinâmica.",
    go: "Criado por <b>Robert Griesemer, Rob Pike e Ken Thompson</b> no Google, lançado em <b>2009</b>. Motivação: unir produtividade do Python com performance de C/C++ e concorrência nativa.",
    py: "Criado por <b>Guido van Rossum</b> em <b>1991</b>. Foco em legibilidade e simplicidade, nome inspirado no grupo Monty Python.",
    rust: "Criado por <b>Graydon Hoare</b> na Mozilla, lançado em <b>2010</b> (1.0 em 2015). Objetivo: segurança de memória sem garbage collector.",
    c: "Criado por <b>Dennis Ritchie</b> nos Bell Labs entre <b>1969-1972</b> para reescrever o Unix. Base de quase toda computação moderna.",
    cpp: "Criado por <b>Bjarne Stroustrup</b> em <b>1979</b> (\"C with Classes\"), lançado em <b>1985</b>. Adicionou OOP e recursos de alto nível ao C.",
    cs: "Criado por <b>Anders Hejlsberg</b> na Microsoft, lançado em <b>2000</b>. Linguagem moderna para a plataforma .NET, inspirada em Java e C++.",
    java: "Criado por <b>James Gosling</b> na Sun Microsystems, lançado em <b>1995</b>. Lema: \"Write once, run anywhere\" via JVM."
  },
  {
    topic: "Playground online",
    js: `<a href="https://jsfiddle.net" target="_blank">JSFiddle</a><br><a href="https://playcode.io/javascript" target="_blank">PlayCode</a><br><a href="https://developer.mozilla.org/pt-BR/play" target="_blank">MDN Playground</a>`,
    php: `<a href="https://onlinephp.io" target="_blank">onlinephp.io</a><br><a href="https://3v4l.org" target="_blank">3v4l.org</a>`,
    go: `<a href="https://go.dev/play" target="_blank">Go Playground</a>`,
    py: `<a href="https://replit.com" target="_blank">Replit</a><br><a href="https://www.programiz.com/python-programming/online-compiler" target="_blank">Programiz</a>`,
    rust: `<a href="https://play.rust-lang.org" target="_blank">Rust Playground</a>`,
    c: `<a href="https://onlinegdb.com" target="_blank">OnlineGDB</a><br><a href="https://www.programiz.com/c-programming/online-compiler" target="_blank">Programiz</a>`,
    cpp: `<a href="https://godbolt.org" target="_blank">Compiler Explorer</a><br><a href="https://www.onlinegdb.com/online_c++_compiler" target="_blank">OnlineGDB</a>`,
    cs: `<a href="https://dotnetfiddle.net" target="_blank">.NET Fiddle</a><br><a href="https://replit.com" target="_blank">Replit</a>`,
    java: `<a href="https://www.onlinegdb.com/online_java_compiler" target="_blank">OnlineGDB</a><br><a href="https://replit.com" target="_blank">Replit</a>`
  },
  {
    topic: "Instalação (Windows / Linux)",
    js: "Nativo no navegador. Para Node.js:<br><b>Win:</b> baixar em <code>nodejs.org</code><br><b>Linux:</b> <code>sudo apt install nodejs npm</code>",
    php: "<b>Win:</b> XAMPP ou baixar em <code>windows.php.net</code><br><b>Linux:</b> <code>sudo apt install php-cli</code>",
    go: "<b>Win:</b> MSI em <code>go.dev/dl</code><br><b>Linux:</b> <code>sudo apt install golang</code> ou tarball oficial",
    py: "<b>Win:</b> instalador em <code>python.org</code><br><b>Linux:</b> <code>sudo apt install python3</code>",
    rust: "<b>Win/Linux:</b> <code>curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh</code> (rustup)",
    c: "<b>Win:</b> MinGW / MSYS2 / Visual Studio<br><b>Linux:</b> <code>sudo apt install gcc</code>",
    cpp: "<b>Win:</b> Visual Studio / MinGW<br><b>Linux:</b> <code>sudo apt install g++</code>",
    cs: "<b>Win:</b> Visual Studio ou .NET SDK em <code>dot.net</code><br><b>Linux:</b> <code>sudo apt install dotnet-sdk-8.0</code>",
    java: "<b>Win:</b> JDK em <code>oracle.com/java</code> ou Adoptium<br><b>Linux:</b> <code>sudo apt install default-jdk</code>"
  },
  {
    topic: "Comandos: criar / rodar programas",
    js: `Criar: <code>node app.js</code><br>Rodar: <code>node app.js</code><br>No browser: <code>&lt;script src="app.js"&gt;</code>`,
    php: `Criar: <code>index.php</code><br>Rodar CLI: <code>php index.php</code><br>Servidor web: <code>php -S localhost:8000</code>`,
    go: `Criar: <code>go mod init app</code><br>Rodar: <code>go run main.go</code><br>Build: <code>go build -o app</code>`,
    py: `Criar: <code>app.py</code><br>Rodar: <code>python3 app.py</code>`,
    rust: `Criar: <code>cargo new app</code><br>Rodar: <code>cargo run</code><br>Build: <code>cargo build --release</code>`,
    c: `Criar: <code>app.c</code><br>Compilar: <code>gcc app.c -o app</code><br>Rodar: <code>./app</code>`,
    cpp: `Criar: <code>app.cpp</code><br>Compilar: <code>g++ app.cpp -o app</code><br>Rodar: <code>./app</code>`,
    cs: `Criar: <code>dotnet new console -n App</code><br>Rodar: <code>dotnet run</code><br>Build: <code>dotnet build</code>`,
    java: `Criar: <code>App.java</code><br>Compilar: <code>javac App.java</code><br>Rodar: <code>java App</code>`
  },
  {
    topic: "Tipos de dados",
    js: `<code>number, string, boolean, null, undefined, symbol, bigint, object</code> (tipagem dinâmica e fraca)`,
    php: `<code>int, float, string, bool, array, object, null, resource</code> (dinâmica com tipagem opcional)`,
    go: `<code>int, float64, string, bool, byte, rune, []T, map[K]V, struct</code> (estática e forte)`,
    py: `<code>int, float, str, bool, list, tuple, dict, set, None</code> (dinâmica e forte)`,
    rust: `<code>i32, u64, f64, bool, char, &str, String, Vec&lt;T&gt;, Option&lt;T&gt;, Result&lt;T,E&gt;</code>`,
    c: `<code>int, char, float, double, long, short, struct, union, enum, pointer</code>`,
    cpp: "Mesmos do C + <code>bool, auto, string, vector, map, class</code>",
    cs: `<code>int, double, bool, char, string, decimal, object, dynamic, struct, class</code>`,
    java: `<code>int, double, boolean, char, String, long, float, byte, short</code> (primitivos + objetos)"`
  },
  {
    topic: "Função",
    js: `<pre>function soma(a, b) {
  return a + b;
}
const mult = (a,b) =&gt; a*b;</pre>`,
    php: `<pre>function soma($a, $b) {
  return $a + $b;
}</pre>`,
    go: `<pre>func soma(a, b int) int {
  return a + b
}</pre>`,
    py: `<pre>def soma(a, b):
    return a + b</pre>`,
    rust: `<pre>fn soma(a: i32, b: i32) -&gt; i32 {
    a + b
}</pre>`,
    c: `<pre>int soma(int a, int b) {
  return a + b;
}</pre>`,
    cpp: `<pre>int soma(int a, int b) {
  return a + b;
}
// ou sobrecarga / lambda</pre>`,
    cs: `<pre>int Soma(int a, int b) {
  return a + b;
}</pre>`,
    java: `<pre>public static int soma(int a, int b) {
  return a + b;
}</pre>`
  },
  {
    topic: "Entrada de dados no terminal (prompt)",
    js: `Node: <pre>const readline = require('readline');
const rl = readline.createInterface({input:process.stdin,output:process.stdout});
rl.question('Nome: ', n =&gt; { console.log(n); rl.close(); });</pre>`,
    php: `<pre>$nome = readline("Nome: ");
echo "Olá, $nome";</pre>`,
    go: `<pre>var nome string
fmt.Print("Nome: ")
fmt.Scanln(&amp;nome)</pre>`,
    py: `<pre>nome = input("Nome: ")
print(f"Olá, {nome}")</pre>`,
    rust: `<pre>let mut nome = String::new();
println!("Nome: ");
std::io::stdin().read_line(&amp;mut nome).unwrap();</pre>`,
    c: `<pre>char nome[50];
printf("Nome: ");
scanf("%49s", nome);</pre>`,
    cpp: `<pre>string nome;
cout &lt;&lt; "Nome: ";
cin &gt;&gt; nome;
// ou getline(cin, nome);</pre>`,
    cs: `<pre>Console.Write("Nome: ");
string nome = Console.ReadLine();</pre>`,
    java: `<pre>Scanner sc = new Scanner(System.in);
System.out.print("Nome: ");
String nome = sc.nextLine();</pre>`
  },
  {
    topic: "Cálculos",
    js: `<pre>let r = (5 + 3) * 2 / 4;
let pot = Math.pow(2, 10);
let raiz = Math.sqrt(16);</pre>`,
    php: `<pre>$r = (5 + 3) * 2 / 4;
$pot = pow(2, 10);
$raiz = sqrt(16);</pre>`,
    go: `<pre>import "math"
r := (5 + 3) * 2 / 4
pot := math.Pow(2, 10)
raiz := math.Sqrt(16)</pre>`,
    py: `<pre>r = (5 + 3) * 2 / 4
pot = 2 ** 10
raiz = 16 ** 0.5
import math; math.sqrt(16)</pre>`,
    rust: `<pre>let r = (5 + 3) * 2 / 4;
let pot = 2_i32.pow(10);
let raiz = 16_f64.sqrt();</pre>`,
    c: `<pre>#include &lt;math.h&gt;
int r = (5+3)*2/4;
double p = pow(2,10);
double s = sqrt(16);</pre>`,
    cpp: `<pre>#include &lt;cmath&gt;
int r = (5+3)*2/4;
double p = std::pow(2,10);</pre>`,
    cs: `<pre>using System;
int r = (5+3)*2/4;
double p = Math.Pow(2,10);
double s = Math.Sqrt(16);</pre>`,
    java: `<pre>int r = (5+3)*2/4;
double p = Math.pow(2,10);
double s = Math.sqrt(16);</pre>`
  },
  {
    topic: "Strings",
    js: `<pre>let s = "Olá " + "mundo";
let t = \`Oi \${nome}\`;
s.length; s.toUpperCase();
s.split(",");</pre>`,
    php: `<pre>$s = "Olá " . "mundo";
$t = "Oi $nome";
strlen($s); strtoupper($s);
explode(",", $s);</pre>`,
    go: `<pre>s := "Olá " + "mundo"
t := fmt.Sprintf("Oi %s", nome)
len(s)
strings.ToUpper(s)
strings.Split(s, ",")</pre>`,
    py: `<pre>s = "Olá " + "mundo"
t = f"Oi {nome}"
len(s); s.upper()
s.split(",")</pre>`,
    rust: `<pre>let s = String::from("Olá ") + "mundo";
let t = format!("Oi {}", nome);
s.len();
s.to_uppercase();
s.split(',').collect::&lt;Vec&lt;_&gt;&gt;();</pre>`,
    c: `<pre>#include &lt;string.h&gt;
char s[50] = "Ola";
strcat(s, " mundo");
strlen(s);
strcmp(a,b);</pre>`,
    cpp: `<pre>#include &lt;string&gt;
string s = "Ola " + string("mundo");
s.length();
s.find("a");
s.substr(0,3);</pre>`,
    cs: `<pre>string s = "Ola " + "mundo";
string t = $"Oi {nome}";
s.Length;
s.ToUpper();
s.Split(',');</pre>`,
    java: `<pre>String s = "Ola " + "mundo";
String t = "Oi " + nome;
s.length();
s.toUpperCase();
s.split(",");</pre>`
  },
  {
    topic: "Loops",
    js: `<pre>for (let i=0; i&lt;5; i++) {}
arr.forEach(x =&gt; console.log(x));
for (const x of arr) {}
while (cond) {}</pre>`,
    php: `<pre>for ($i=0; $i&lt;5; $i++) {}
foreach ($arr as $x) {}
while ($cond) {}
do {} while ($cond);</pre>`,
    go: `<pre>for i := 0; i &lt; 5; i++ {}
for _, x := range arr {}
for cond {}
// Go só tem for</pre>`,
    py: `<pre>for i in range(5): pass
for x in arr: pass
while cond: pass</pre>`,
    rust: `<pre>for i in 0..5 {}
for x in &amp;arr {}
while cond {}
loop { break; }</pre>`,
    c: `<pre>for (int i=0; i&lt;5; i++) {}
while (cond) {}
do {} while (cond);</pre>`,
    cpp: `<pre>for (int i=0; i&lt;5; i++) {}
for (auto x : arr) {}
while (cond) {}
// range-based for</pre>`,
    cs: `<pre>for (int i=0; i&lt;5; i++) {}
foreach (var x in arr) {}
while (cond) {}</pre>`,
    java: `<pre>for (int i=0; i&lt;5; i++) {}
for (int x : arr) {}
while (cond) {}</pre>`
  },
  {
    topic: "if / else / match / switch",
    js: `<pre>if (x &gt; 0) {}
else if (x === 0) {}
else {}
switch(x) {
  case 1: break;
  default: break;
}</pre>`,
    php: `<pre>if ($x &gt; 0) {}
elseif ($x === 0) {}
else {}
match($x) {
  1 =&gt; 'um',
  default =&gt; 'outro'
};</pre>`,
    go: `<pre>if x &gt; 0 {
} else if x == 0 {
} else {}
switch x {
case 1: // ...
default:
}</pre>`,
    py: `<pre>if x &gt; 0:
    pass
elif x == 0:
    pass
else:
    pass
# match (3.10+)
match x:
    case 1: ...
    case _: ...</pre>`,
    rust: `<pre>if x &gt; 0 {}
else if x == 0 {}
else {}
match x {
  1 =&gt; println!("um"),
  _ =&gt; println!("outro"),
}</pre>`,
    c: `<pre>if (x &gt; 0) {}
else if (x == 0) {}
else {}
switch (x) {
  case 1: break;
  default: break;
}</pre>`,
    cpp: `<pre>if (x &gt; 0) {}
else {}
switch (x) {
  case 1: break;
  default: break;
}
// C++17: if with initializer</pre>`,
    cs: `<pre>if (x &gt; 0) {}
else if (x == 0) {}
else {}
switch (x) {
  case 1: break;
  default: break;
}
// pattern matching</pre>`,
    java: `<pre>if (x &gt; 0) {}
else if (x == 0) {}
else {}
switch (x) {
  case 1 -&gt; ...;
  default -&gt; ...;
}</pre>`
  },
  {
    topic: "Arrays / Listas",
    js: `<pre>let a = [1,2,3];
a.push(4); a.pop();
a.map(x =&gt; x*2);
a.filter(x =&gt; x&gt;1);</pre>`,
    php: `<pre>$a = [1,2,3];
$a[] = 4;
array_push($a, 5);
array_map(fn($x)=&gt;$x*2, $a);</pre>`,
    go: `<pre>a := []int{1,2,3}
a = append(a, 4)
// slice: make([]int, 0)</pre>`,
    py: `<pre>a = [1,2,3]
a.append(4)
[x*2 for x in a]
list(map(lambda x:x*2, a))</pre>`,
    rust: `<pre>let mut a = vec![1,2,3];
a.push(4);
a.iter().map(|x| x*2).collect::&lt;Vec&lt;_&gt;&gt;();</pre>`,
    c: `<pre>int a[3] = {1,2,3};
// tamanho fixo
// ou malloc para dinâmico</pre>`,
    cpp: `<pre>#include &lt;vector&gt;
vector&lt;int&gt; a = {1,2,3};
a.push_back(4);
std::sort(a.begin(), a.end());</pre>`,
    cs: `<pre>int[] a = {1,2,3};
var list = new List&lt;int&gt;{1,2,3};
list.Add(4);
list.Where(x =&gt; x&gt;1);</pre>`,
    java: `<pre>int[] a = {1,2,3};
List&lt;Integer&gt; l = new ArrayList&lt;&gt;();
l.add(4);
l.stream().map(x-&gt;x*2);</pre>`
  },
  {
    topic: "Datas e horas",
    js: `<pre>const d = new Date();
d.getFullYear();
d.toLocaleString('pt-BR');
Date.now(); // timestamp</pre>`,
    php: `<pre>$d = new DateTime();
echo $d-&gt;format('Y-m-d H:i:s');
$time = time();
$d-&gt;modify('+1 day');</pre>`,
    go: `<pre>import "time"
t := time.Now()
fmt.Println(t.Format("2006-01-02 15:04:05"))
t.Add(24 * time.Hour)</pre>`,
    py: `<pre>from datetime import datetime, timedelta
d = datetime.now()
d.strftime("%Y-%m-%d %H:%M:%S")
d + timedelta(days=1)</pre>`,
    rust: `<pre>// crate chrono
use chrono::Local;
let t = Local::now();
println!("{}", t.format("%Y-%m-%d %H:%M"));</pre>`,
    c: `<pre>#include &lt;time.h&gt;
time_t t = time(NULL);
struct tm *tm = localtime(&amp;t);
char buf[64];
strftime(buf, sizeof buf, "%Y-%m-%d", tm);</pre>`,
    cpp: `<pre>#include &lt;chrono&gt;
auto now = std::chrono::system_clock::now();
// C++20: std::format / &lt;chrono&gt; melhorado</pre>`,
    cs: `<pre>var d = DateTime.Now;
d.ToString("yyyy-MM-dd HH:mm");
d.AddDays(1);
// DateTimeOffset para fusos</pre>`,
    java: `<pre>import java.time.*;
LocalDateTime d = LocalDateTime.now();
d.format(DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm"));
d.plusDays(1);</pre>`
  },
  {
    topic: "Banco de dados (Postgres / MySQL)",
    js: `<pre>// pg
const { Client } = require('pg');
const c = new Client({connectionString});
await c.connect();
// mysql2
const mysql = require('mysql2/promise');</pre>`,
    php: `<pre>// PDO (funciona p/ ambos)
$pdo = new PDO(
  'pgsql:host=localhost;dbname=db',
  'user','pass'
);
// ou mysqli para MySQL</pre>`,
    go: `<pre>import "database/sql"
import _ "github.com/lib/pq"
db, _ := sql.Open("postgres",
  "host=... user=... dbname=... sslmode=disable")</pre>`,
    py: `<pre>import psycopg2
conn = psycopg2.connect(
  "dbname=db user=u password=p")
# ou pymysql / SQLAlchemy</pre>`,
    rust: `<pre>// crate sqlx ou diesel
use sqlx::postgres::PgPool;
let pool = PgPool::connect(
  "postgres://u:p@host/db"
).await?;</pre>`,
    c: `<pre>// libpq (Postgres)
#include &lt;libpq-fe.h&gt;
PGconn *c = PQconnectdb(
  "host=localhost dbname=db");
// MySQL: libmysqlclient</pre>`,
    cpp: `<pre>// soci, pqxx, ou ODBC
#include &lt;pqxx/pqxx&gt;
pqxx::connection c(
  "dbname=db user=u password=p");</pre>`,
    cs: `<pre>// Npgsql p/ Postgres
using Npgsql;
await using var c = new NpgsqlConnection(
  "Host=...;Database=db;Username=u;Password=p");
// MySqlConnector p/ MySQL</pre>`,
    java: `<pre>// JDBC
Connection c = DriverManager.getConnection(
  "jdbc:postgresql://host/db", "u", "p");
// ou MySQL: jdbc:mysql://host/db</pre>`
  },
  {
    topic: "CRUD: ler, editar, apagar",
    js: `<pre>// SELECT
const r = await c.query('SELECT * FROM users');
// UPDATE
await c.query('UPDATE users SET n=$1 WHERE id=$2',['Jo',1]);
// DELETE
await c.query('DELETE FROM users WHERE id=$1',[1]);</pre>`,
    php: `<pre>// SELECT
$stmt = $pdo-&gt;query('SELECT * FROM users');
// UPDATE
$pdo-&gt;prepare('UPDATE users SET nome=? WHERE id=?')
    -&gt;execute(['Jo',1]);
// DELETE
$pdo-&gt;prepare('DELETE FROM users WHERE id=?')
    -&gt;execute([1]);</pre>`,
    go: `<pre>// SELECT
rows, _ := db.Query("SELECT id,nome FROM users")
// UPDATE
db.Exec("UPDATE users SET nome=$1 WHERE id=$2","Jo",1)
// DELETE
db.Exec("DELETE FROM users WHERE id=$1",1)</pre>`,
    py: `<pre>cur = conn.cursor()
cur.execute("SELECT * FROM users")
cur.execute("UPDATE users SET nome=%s WHERE id=%s",('Jo',1))
cur.execute("DELETE FROM users WHERE id=%s",(1,))
conn.commit()</pre>`,
    rust: `<pre>// sqlx
let users = sqlx::query_as!(User,
  "SELECT * FROM users").fetch_all(&amp;pool).await?;
sqlx::query("UPDATE users SET nome=$1 WHERE id=$2")
  .bind("Jo").bind(1).execute(&amp;pool).await?;
sqlx::query("DELETE FROM users WHERE id=$1")
  .bind(1).execute(&amp;pool).await?;</pre>`,
    c: `<pre>PQexec(c, "SELECT * FROM users");
PQexec(c, "UPDATE users SET nome='Jo' WHERE id=1");
PQexec(c, "DELETE FROM users WHERE id=1");</pre>`,
    cpp: `<pre>pqxx::work w(c);
auto r = w.exec("SELECT * FROM users");
w.exec("UPDATE users SET nome='Jo' WHERE id=1");
w.exec("DELETE FROM users WHERE id=1");
w.commit();</pre>`,
    cs: `<pre>await using var cmd = new NpgsqlCommand(
  "SELECT * FROM users", c);
await using var r = await cmd.ExecuteReaderAsync();
await new NpgsqlCommand(
  "UPDATE users SET nome=@n WHERE id=@i", c)
  {Parameters={new("@n","Jo"),new("@i",1)}}
  .ExecuteNonQueryAsync();</pre>`,
    java: `<pre>PreparedStatement ps = c.prepareStatement(
  "SELECT * FROM users");
ResultSet rs = ps.executeQuery();
c.prepareStatement(
  "UPDATE users SET nome=? WHERE id=?")
  .executeUpdate();
c.prepareStatement(
  "DELETE FROM users WHERE id=?")
  .executeUpdate();</pre>`
  },
  {
    topic: "Principais usos",
    js: `<span class="badge">Web frontend</span><span class="badge">Node.js backend</span><span class="badge">Apps (React Native)</span><span class="badge">Desktop (Electron)</span>`,
    php: `<span class="badge">Sites dinâmicos</span><span class="badge">CMS (WordPress)</span><span class="badge">E-commerce</span><span class="badge">APIs REST</span>`,
    go: `<span class="badge">Microsserviços</span><span class="badge">Cloud/DevOps (Docker, K8s)</span><span class="badge">APIs de alta performance</span><span class="badge">CLIs</span>`,
    py: `<span class="badge">Ciência de dados</span><span class="badge">IA/ML</span><span class="badge">Automação</span><span class="badge">Web (Django/Flask)</span><span class="badge">Scripts</span>`,
    rust: `<span class="badge">Sistemas</span><span class="badge">WebAssembly</span><span class="badge">Ferramentas CLI</span><span class="badge">Embarcados</span><span class="badge">Blockchain</span>`,
    c: `<span class="badge">Sistemas operacionais</span><span class="badge">Embarcados</span><span class="badge">Drivers</span><span class="badge">Bibliotecas de baixo nível</span>`,
    cpp: `<span class="badge">Games (Unreal)</span><span class="badge">Sistemas de alta performance</span><span class="badge">Compiladores</span><span class="badge">CAD/CAE</span>`,
    cs: `<span class="badge">Apps Windows</span><span class="badge">Web (.NET/ASP)</span><span class="badge">Games (Unity)</span><span class="badge">Enterprise</span>`,
    java: `<span class="badge">Enterprise</span><span class="badge">Android</span><span class="badge">Big Data (Hadoop)</span><span class="badge">Sistemas distribuídos</span>`
  }
];

/* =========================================================
   RENDER DA TABELA
   ========================================================= */
const tbody = document.getElementById("tableBody");
const topicFilter = document.getElementById("topicFilter");
const search = document.getElementById("search");

function render() {
  const q = search.value.toLowerCase().trim();
  const topic = topicFilter.value;
  tbody.innerHTML = "";
  data.forEach(row => {
    if (topic && row.topic !== topic) return;
    const tr = document.createElement("tr");
    const tdTopic = document.createElement("td");
    tdTopic.className = "topic-cell";
    tdTopic.textContent = row.topic;
    tr.appendChild(tdTopic);

    ["js","php","go","py","rust","c","cpp","cs","java"].forEach(lang => {
      const td = document.createElement("td");
      td.innerHTML = row[lang];
      tr.appendChild(td);
    });

    // filtro de busca
    if (q) {
      const text = (row.topic + " " + Object.values(row).join(" ")).toLowerCase();
      if (!text.includes(q)) return;
    }
    tbody.appendChild(tr);
  });
}

// popular filtro de tópicos
data.forEach(row => {
  const opt = document.createElement("option");
  opt.value = row.topic;
  opt.textContent = row.topic;
  topicFilter.appendChild(opt);
});

search.addEventListener("input", render);
topicFilter.addEventListener("change", render);
render();
</script>

</body>
</html>
