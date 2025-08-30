import React, { useState } from "react";

// === Configure these before deploy ===
const NAME = "Astro Coin";
const TICKER = "ASTRO";
const MINT = "PASTE_MINT_ADDRESS_HERE"; // e.g., 9x...
const BUY_LINK = "PASTE_BUY_LINK_HERE"; // Pump.fun coin URL or similar
const DEX_LINK = "PASTE_DEX_LINK_HERE"; // PumpSwap/Raydium/Orca
const TELEGRAM = "https://t.me/astrocoin";
const TWITTER = "https://x.com/astrocoin";

export default function AstroLanding() {
  return (
    <div className="min-h-screen text-white bg-[radial-gradient(60%_50%_at_50%_0%,#1d2a73_0%,#0f1a3f_55%,#0a1025_100%)]">
      <Nav />
      <Hero />
      <Highlights />
      <HowToBuy />
      <About />
      <Footer />
    </div>
  );
}

function Nav(){
  return (
    <header className="sticky top-0 z-40 bg-black/30 backdrop-blur border-b border-white/10">
      <div className="max-w-6xl mx-auto px-4 py-3 flex items-center justify-between">
        <div className="flex items-center gap-3">
          <img src="/astro-logo.png" alt={NAME} className="w-9 h-9 rounded-xl shadow"/>
          <div>
            <div className="font-extrabold tracking-wide">{NAME.toUpperCase()}</div>
            <div className="text-[10px] uppercase tracking-[.2em] text-white/60">${TICKER} • To The Moon</div>
          </div>
        </div>
        <nav className="hidden sm:flex items-center gap-2">
          <a href={TELEGRAM} target="_blank" className="px-3 py-2 rounded-xl bg-white/5 ring-1 ring-white/10 hover:bg-white/10">Telegram</a>
          <a href={TWITTER} target="_blank" className="px-3 py-2 rounded-xl bg-white/5 ring-1 ring-white/10 hover:bg-white/10">X</a>
          <a href={BUY_LINK} target="_blank" className="px-4 py-2 rounded-xl bg-[#F3B300] text-black font-black">Buy</a>
        </nav>
      </div>
    </header>
  )
}

function Hero(){
  return (
    <section className="relative overflow-hidden">
      <div className="absolute inset-0 opacity-30" style={{backgroundImage:"radial-gradient(#bcd3ff 1px, transparent 1px), radial-gradient(#bcd3ff 1px, transparent 1px)", backgroundSize:"120px 120px, 160px 160px", backgroundPosition:"20px 30px, 60px 80px"}}/>
      <div className="max-w-6xl mx-auto px-4 py-16 sm:py-24 grid md:grid-cols-2 gap-10 items-center">
        <div>
          <h1 className="text-4xl sm:text-6xl font-black leading-tight">Astronaut vibes. Rocket fuel memes.</h1>
          <p className="mt-4 text-white/80 max-w-prose">${TICKER} is a space‑themed parody memecoin. 0% tax. Fixed supply. Not investment advice.</p>
          <div className="mt-6 flex flex-wrap gap-3">
            <a href={BUY_LINK} target="_blank" className="px-5 py-3 rounded-2xl bg-[#F3B300] text-black font-extrabold">Buy {TICKER}</a>
            <a href={DEX_LINK} target="_blank" className="px-5 py-3 rounded-2xl bg-white/5 ring-1 ring-white/10 hover:bg-white/10">Trade on DEX</a>
          </div>
          <div className="mt-6 p-4 bg-black/30 rounded-2xl">
            <div className="text-xs uppercase tracking-widest text-white/50">Mint Address</div>
            <div className="flex items-center gap-3 mt-1">
              <code className="text-sm sm:text-base break-all">{MINT}</code>
              <CopyButton text={MINT} />
            </div>
          </div>
          <div className="grid grid-cols-2 gap-3 mt-4">
            <Fact>Supply: <b>1,000,000,000</b></Fact>
            <Fact>Taxes: <b>0%</b></Fact>
          </div>
        </div>
        <div className="flex justify-center">
          <img src="/astro-logo.png" alt="Astro art" className="w-[420px] h-[420px] rounded-3xl shadow-2xl ring-1 ring-white/10 object-cover"/>
        </div>
      </div>
    </section>
  )
}

function Highlights(){
  return (
    <section className="py-12">
      <div className="max-w-6xl mx-auto px-4 grid md:grid-cols-3 gap-4">
        <Card title="Fair & Simple" text="No taxes, no weird rules. Keep it clean and meme‑friendly." />
        <Card title="Community First" text="Memes > promises. Focused on vibes, contests, fun reveals." />
        <Card title="DEX Ready" text="Buy link for launchpad; DEX link when trading goes live." />
      </div>
    </section>
  )
}

function Card({title, text}:{title:string, text:string}){
  return (
    <div className="p-5 rounded-2xl bg-white/5 ring-1 ring-white/10">
      <div className="font-bold text-lg">{title}</div>
      <p className="text-white/80 mt-1">{text}</p>
    </div>
  )
}

function Fact({children}:{children:React.ReactNode}){
  return <div className="p-3 rounded-2xl bg-white/5 ring-1 ring-white/10 text-sm">{children}</div>
}

function HowToBuy(){
  return (
    <section className="py-16 bg-black/20">
      <div className="max-w-6xl mx-auto px-4">
        <h2 className="text-3xl sm:text-4xl font-extrabold">How to buy</h2>
        <div className="mt-6 grid md:grid-cols-3 gap-4">
          <Step n={1} title="Get SOL" desc="Buy SOL and send to Phantom or your Solana wallet."/>
          <Step n={2} title="Open Buy Link" desc="Visit the launch page and connect your wallet."/>
          <Step n={3} title="Swap for ${TICKER}" desc={`Swap SOL for ${TICKER}. Import the token in your wallet if needed.`}/>
        </div>
      </div>
    </section>
  )
}

function Step({n,title,desc}:{n:number,title:string,desc:string}){
  return (
    <div className="p-5 rounded-2xl bg-white/5 ring-1 ring-white/10">
      <div className="w-9 h-9 rounded-full bg-white text-black font-bold flex items-center justify-center">{n}</div>
      <div className="mt-2 font-semibold">{title}</div>
      <p className="text-white/80">{desc}</p>
    </div>
  )
}

function About(){
  return (
    <section className="py-16">
      <div className="max-w-6xl mx-auto px-4 grid md:grid-cols-2 gap-10 items-center">
        <div>
          <h2 className="text-3xl sm:text-4xl font-extrabold">About ASTRO</h2>
          <p className="mt-4 text-white/80">Born from the "to the moon" meme energy. Community‑driven fun, no promises of profit. Keep it playful and responsible.</p>
          <ul className="grid sm:grid-cols-2 gap-3 text-sm mt-5">
            <Fact>Chain: <b>Solana</b></Fact>
            <Fact>Type: <b>Parody memecoin</b></Fact>
            <Fact>Launch: <b>Via launch link</b></Fact>
            <Fact>DEX: <b>After launch</b></Fact>
          </ul>
        </div>
        <div className="relative">
          <img src="/astro-banner.png" alt="Astro banner" className="rounded-3xl shadow-2xl ring-1 ring-white/10"/>
          <div className="absolute -bottom-3 -right-3 px-3 py-1 rounded-xl text-xs bg-white text-black font-semibold">${TICKER}</div>
        </div>
      </div>
    </section>
  )
}

function Footer(){
  return (
    <footer className="py-10 text-center text-white/60">
      <p className="max-w-3xl mx-auto px-4 text-sm">© {new Date().getFullYear()} Astro Coin. Parody memecoin. Not investment advice.</p>
    </footer>
  )
}

function CopyButton({ text }:{ text:string }){
  const [copied, setCopied] = useState(false)
  return (
    <button onClick={async()=>{try{await navigator.clipboard.writeText(text);setCopied(true);setTimeout(()=>setCopied(false),1200)}catch(e){}}} className="px-3 py-1 rounded-lg bg-white/10 hover:bg-white/20 text-xs">{copied?"Copied!":"Copy"}</button>
  )
}
