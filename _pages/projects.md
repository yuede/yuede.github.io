---
layout: archive
title: "Research"
permalink: /projects/
author_profile: true
---

<style>
  .pillars-grid{
    display:grid;
    gap:24px;
    grid-template-columns:1fr;
    margin:16px 0 32px;
    align-items:start;
  }
  @media (min-width:900px){
    .pillars-grid{ grid-template-columns:repeat(2,minmax(0,1fr)); }
  }
  .pillar-card{
    border:1px solid #e3e3e3;
    border-radius:10px;
    padding:20px 22px;
    background:#fff;
  }
  .pillar-card.scalable{ border-top:4px solid #2b6cb0; }
  .pillar-card.trustworthy{ border-top:4px solid #b83280; }
  .pillar-card h3{ margin-top:0; }
  .pillar-tag{
    display:inline-block;
    font-size:0.75em;
    font-weight:600;
    letter-spacing:0.03em;
    text-transform:uppercase;
    padding:2px 8px;
    border-radius:12px;
    margin-bottom:8px;
  }
  .pillar-card.scalable .pillar-tag{ background:#ebf4ff; color:#2b6cb0; }
  .pillar-card.trustworthy .pillar-tag{ background:#fbe8f4; color:#b83280; }

  .stack-flow{
    display:flex;
    flex-direction:column;
    gap:0;
    margin:16px 0 20px;
  }
  .stack-step{
    border:1px solid #e3e3e3;
    border-radius:8px;
    padding:10px 14px;
    background:#fdf5fa;
  }
  .stack-step strong{ color:#b83280; }
  .stack-arrow{
    text-align:center;
    color:#b83280;
    font-size:1.1em;
    line-height:1.4;
    margin:2px 0;
  }
</style>

Graph Lab's research spans two connected pillars, unified by graph-centric methods developed over the lab's HPC and graph-computing work: <strong>Scalable AI Systems</strong>, which makes AI systems fast and efficient at scale, and <strong>Trustworthy AI Systems</strong>, which makes them safe, verifiable, and trustworthy to rely on.

<div class="pillars-grid">

  <div class="pillar-card scalable">
    <span class="pillar-tag">Pillar 1</span>
    <h3>Scalable AI Systems</h3>
    <p>
    Graph, in reality, is big data — in scale and in count — and many of the most interesting graph and AI algorithms are computationally expensive. This pillar builds on the lab's existing strengths in HPC and graph computing to tackle scalability at every layer: <strong>Graph Foundation Models</strong>, systems for foundation models and LLMs, scalable training and inference, and HPC/graph infrastructure for AI.
    </p>
    <p>
    <span style="color:blue">Publications</span>: [KSPine [SC \'26]](.), [VeriHGN [KDD \'26]](.), [HuggingGraph [CIKM \'25]](.), [BINGO [EuroSys \'25]](.), [PeeK [SC \'23]](.), [Tango [SC \'23]](.), [TLPGNN [HPDC \'22]](../files/22_hpdc_TLPGNN.pdf), [Aquila [HPDC \'20]](../files/20_HPDC_Aquila.pdf), [iSpan [SC \'18]](../files/18_SC_iSpan.pdf)
    </p>
    <p>
    <span style="color:orange">Fundings</span>: [NSF SHF 2331301](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2331301&HistoricalAwards=false), [NSF SHF 2508118](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2508118&HistoricalAwards=false)
    </p>
  </div>

  <div class="pillar-card trustworthy">
    <span class="pillar-tag">Pillar 2</span>
    <h3>Trustworthy AI Systems</h3>
    <p>
    As AI systems and agents are increasingly composed from third-party models, datasets, tools, and workflows, understanding and ensuring their trustworthiness becomes a top priority. This pillar — potentially the lab's most distinctive long-term direction — studies trust as a connected stack, from the AI supply chain up to trust-aware decisions:
    </p>

    <div class="stack-flow">
      <div class="stack-step"><strong>1. AI Supply Chain &amp; Provenance</strong><br/><small>Reconstructing incomplete AI supply chains from graph structure, code evidence, and metadata, with quantified confidence.</small></div>
      <div class="stack-arrow">&#8595;</div>
      <div class="stack-step"><strong>2. Security &amp; Risk</strong><br/><small>Identifying compromised components, supply-chain attacks, prompt injection, malicious tool use, and threat propagation through AI workflows.</small></div>
      <div class="stack-arrow">&#8595;</div>
      <div class="stack-step"><strong>3. Reliability &amp; Verification</strong><br/><small>Detecting, verifying, containing, and recovering from errors that propagate and amplify through multi-agent AI workflows.</small></div>
      <div class="stack-arrow">&#8595;</div>
      <div class="stack-step"><strong>4. Trust-Aware Decision Making</strong><br/><small>Recommending models, datasets, agents, and tools based on provenance, security, reliability, cost, compatibility, and compliance — not just performance.</small></div>
    </div>

    <p>
    <span style="color:blue">Publications</span>: [HuggingGraph [CIKM \'25]](.), [L2R [INSCRYPT \'26]](.), [eMicro [CCS \'26]](.), [TARA [SRDS \'26]](.), [Image Security [Cloud Summit \'25]](./), [CloudCover [ACSAC \'24]](./), [HermesSim [USENIX Security \'24]](./), [API2Vec [ISSTA \'23]](.), [Illuminati [EuroS&P \'22]](../files/22_EuroSP_Illuminati.pdf), [DEFInit [USENIX Security \'21]](https://www.usenix.org/conference/usenixsecurity21/presentation/ji), [BugGraph [AsiaCCS \'21]](../files/21_AsiaCCS_BugGraph.pdf), [APT detection [RAID \'20]](../files/20_RAID_lateral_movement.pdf)
    </p>
    <p>
    <span style="color:orange">Fundings</span>: [NSF OAC 2516003](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2516003&HistoricalAwards=false), [NSF OAC 2419843](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2419843)
    </p>
  </div>

</div>

<img src="../images/NSF_logo.png"
     alt="Markdown Monster icon"
     width="150"
     />
<img src="../images/Google-logo.png"
     alt="Markdown Monster icon"
     width="250"
     />
