`<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:161b22&height=300&section=header&text=Mudassir%20Ali&fontSize=90&animation=fadeIn&fontAlignY=38&desc=Full%20Stack%20Software%20Engineer&descAlignY=51&descSize=20" width="100%" />

  <p align="center">
    <img src="https://img.shields.io/badge/Open_Source-Collaborator-10adff?style=for-the-badge&logo=github&logoColor=white" />
    <img src="https://img.shields.io/badge/Full_Stack-Developer-FFD700?style=for-the-badge&logo=javascript&logoColor=black" />
    <img src="https://img.shields.io/badge/Learning-Always-success?style=for-the-badge&logo=bookstack&logoColor=white" />
  </p>
</div>

### 🛠️ Systems & Architecture

\`\`\`javascript
const engineer = {
  name: "Mudassir Ali",
  role: "Full Stack Developer",
  focus: ["Scalable Web Systems", "Performance Optimization"],
  passion: "Solving complex engineering puzzles 🧩",
  status: "Compiling next-gen solutions..."
};
\`\`\`

---

### 🚀 Technical Arsenal

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🌐 Frontend Core</h4>
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
      <img src="https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white" />
      <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
      <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" />
    </td>
    <td width="50%" valign="top">
      <h4>⚙️ Backend & Infrastructure</h4>
      <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
      <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
      <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white" />
    </td>
  </tr>
</table>

---

### 📊 Git Transformation Metrics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=alii22&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="Mudassir's Stats" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=alii22&show_icons=true&theme=tokyonight&hide_border=true&layout=compact" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=alii22&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

---

### 🏆 Engineering Milestones

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=alii22&theme=tokyonight&no-bg=true&margin-w=4" alt="Trophies" />
</p>

---

### 🏗️ Connect with the Architect

<p align="left">
  <a href="mailto:mudassir4227@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/mudassir-a-ba721830b" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://discord.com" target="_blank">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" />
  </a>
</p>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=alii22&label=SYSTEM%20ACCESSES&color=0e75b6&style=flat-square" alt="Profile Views" />
  <br/>
  <sub>⚡ Fun Fact: I binary-search my way through life's problems.</sub>
</div>
`;

export default function App() {
  const [copied, setCopied] = useState(false);

  const handleCopy = () => {
    navigator.clipboard.writeText(ENHANCED_README);
    setCopied(true);
    setTimeout(() => setCopied(false), 2000);
  };

  return (
    <div className="min-h-screen flex flex-col items-center py-12 px-6 bg-[#050505]">
      <header className="max-w-5xl w-full mb-12 flex flex-col md:flex-row justify-between items-start md:items-end border-b border-[#333] pb-8">
        <motion.div
          initial={{ opacity: 0, x: -20 }}
          animate={{ opacity: 1, x: 0 }}
          className="space-y-1"
        >
          <div className="flex items-center gap-2 text-accent font-mono text-sm mb-1">
            <span className="opacity-50">&gt;</span> 
            <span>profile / mudassir-ali / v2.4.0</span>
            <span className="cursor-blink">_</span>
          </div>
          <h1 className="text-5xl font-bold tracking-tight text-white">README <span className="text-gray-500 font-light italic">Refactor</span></h1>
          <p className="text-[#888] font-light text-lg">Next-Level Software Engineering Profile Enhancement</p>
        </motion.div>
        <div className="text-right mt-6 md:mt-0 font-mono">
          <p className="text-[10px] text-[#555] uppercase tracking-[0.2em] mb-1">System Status</p>
          <p className="text-xs font-medium text-accent">REPL: ACTIVE // READY TO DEPLOY</p>
        </div>
      </header>

      <div className="max-w-6xl w-full grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
        {/* Left: Preview Panel (8 columns) */}
        <section className="lg:col-span-7 flex flex-col h-full">
          <div className="terminal-card overflow-hidden h-full flex flex-col">
            <div className="bg-[#1a1a1a] px-5 py-3 border-b border-[#333] flex items-center justify-between">
              <div className="flex items-center gap-2">
                <Terminal size={14} className="text-accent/60" />
                <span className="text-[11px] font-mono text-[#888] uppercase tracking-widest">Preview: README.md</span>
              </div>
              <div className="flex gap-1.5 grayscale opacity-50">
                <div className="w-2.5 h-2.5 rounded-full bg-[#ff5f56]" />
                <div className="w-2.5 h-2.5 rounded-full bg-[#ffbd2e]" />
                <div className="w-2.5 h-2.5 rounded-full bg-[#27c93f]" />
              </div>
            </div>
            <div className="p-10 bg-white overflow-y-auto max-h-[75vh] custom-scrollbar selection:bg-blue-100">
              <article className="prose prose-slate max-w-none">
                <ReactMarkdown 
                  components={{
                    img: (props: any) => <img {...props} referrerPolicy="no-referrer" className="inline-block" />,
                  }}
                >
                  {ENHANCED_README}
                </ReactMarkdown>
              </article>
            </div>
          </div>
        </section>

        {/* Right: Code & Metrics (5 columns) */}
        <section className="lg:col-span-5 flex flex-col gap-6 lg:sticky lg:top-8">
          <div className="terminal-card flex flex-col overflow-hidden">
            <div className="px-5 py-3 border-b border-[#333] flex items-center justify-between bg-[#1a1a1a]">
              <div className="flex items-center gap-2">
                <Code2 className="text-[#888]" size={14} />
                <h2 className="text-[11px] font-mono text-[#888] uppercase tracking-widest">Source Buffer</h2>
              </div>
              <button
                onClick={handleCopy}
                className={cn(
                  "flex items-center gap-2 px-3 py-1.5 rounded-sm text-[11px] font-mono uppercase tracking-wider transition-all duration-300",
                  copied 
                    ? "text-accent bg-accent/10 border border-accent/20" 
                    : "border border-accent text-accent hover:bg-accent hover:text-black"
                )}
              >
                {copied ? <CheckCircle2 size={12} /> : <div className="w-2 h-2 rounded-full border border-current" />}
                {copied ? "Copied" : "Copy Source"}
              </button>
            </div>
            <div className="p-6 bg-black/40">
              <pre className="text-[12px] font-mono leading-relaxed text-[#00FF41]/70 p-4 rounded bg-[#050505] overflow-x-auto max-h-[40vh] custom-scrollbar">
                {ENHANCED_README}
              </pre>
            </div>
          </div>

          <div className="grid grid-cols-1 sm:grid-cols-2 gap-4">
            <FeatureCard 
              label="// UI ENGINE"
              title="Modern Badges"
              desc="High-contrast SVG status indicators."
            />
            <FeatureCard 
              label="// DATA LAYER"
              title="Real-time Stats"
              desc="Dynamic GitHub API integration hooks."
            />
          </div>
          
          <div className="p-5 border-l-2 border-accent bg-accent/5 terminal-card rounded-none">
            <p className="text-[10px] font-mono text-accent mb-2 uppercase tracking-[0.2em]">Deployment Guide</p>
            <p className="text-sm text-[#aaa] font-light leading-relaxed">
              To activate this profile, copy the source buffer and paste it directly into your <span className="text-white font-mono text-xs italic">alii22/alii22</span> repository's <span className="text-white font-mono text-xs">README.md</span>.
            </p>
          </div>

          <div className="terminal-card p-6 flex flex-col gap-5">
            <h2 className="font-mono text-accent text-[10px] uppercase tracking-widest border-b border-[#333] pb-2">// System Metrics</h2>
            
            <div className="space-y-4">
              <StatItem label="Profile Completeness" value={98} />
              <StatItem label="Accessibility Score" value={100} />
              <StatItem label="Visual Density" value={85} />
            </div>
          </div>
        </section>
      </div>

      <footer className="mt-20 pt-8 border-t border-[#333] max-w-5xl w-full flex justify-between items-center text-[10px] font-mono text-[#444] uppercase tracking-[0.3em]">
        <div>SYSTEM://BOOTSTRAP/SUCCESS</div>
        <div>&copy; 2026 MUDASSIR ALI • SOFTWARE ARCHITECT</div>
      </footer>
    </div>
  );
}

function StatItem({ label, value }: { label: string, value: number }) {
  return (
    <div className="space-y-1.5">
      <div className="flex justify-between text-[10px] font-mono uppercase tracking-wider">
        <span className="text-[#666]">{label}</span>
        <span className="text-accent">{value}%</span>
      </div>
      <div className="h-1.5 bg-[#222] rounded-full overflow-hidden">
        <motion.div 
          initial={{ width: 0 }}
          animate={{ width: `${value}%` }}
          className="h-full bg-accent shadow-[0_0_8px_rgba(0,255,65,0.4)]"
        />
      </div>
    </div>
  );
}

function FeatureCard({ label, title, desc }: { label: string, title: string, desc: string }) {
  return (
    <div className="terminal-card p-4 hover:border-accent/40 transition-all duration-300 group cursor-default">
      <div className="text-accent/60 mb-2 font-mono text-[9px] uppercase tracking-widest group-hover:text-accent transition-colors">{label}</div>
      <h3 className="text-sm font-semibold text-white mb-1 tracking-tight">{title}</h3>
      <p className="text-[11px] text-[#777] leading-tight font-light">{desc}</p>
    </div>
  );
}
