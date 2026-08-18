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
</style>

Graph Lab's research spans two connected pillars, unified by graph-centric methods developed over the lab's HPC and graph-computing work: <strong>Scalable AI Systems</strong>, which makes AI systems fast and efficient at scale, and <strong>Trustworthy AI Systems</strong>, which makes them safe, verifiable, and trustworthy to rely on.

<div class="pillars-grid" markdown="1">

<div class="pillar-card scalable" markdown="1">
<span class="pillar-tag">Pillar 1</span>

### Scalable AI Systems

Graph, in reality, is big data — in scale and in count — and many of the most interesting graph and AI algorithms are computationally expensive. This pillar builds on the lab's existing strengths in HPC and graph computing to tackle scalability at every layer: <strong>Graph Foundation Models</strong>, systems for foundation models and LLMs, scalable training and inference, and HPC/graph infrastructure for AI.

<span style="color:blue">Publications</span>: [KSPine (SC \'26)](.), [VeriHGN (KDD \'26)](.), [HuggingGraph (CIKM \'25)](.), [BINGO (EuroSys \'25)](.), [PeeK (SC \'23)](.), [Tango (SC \'23)](.), [TLPGNN (HPDC \'22)](../files/22_hpdc_TLPGNN.pdf), [Aquila (HPDC \'20)](../files/20_HPDC_Aquila.pdf), [iSpan (SC \'18)](../files/18_SC_iSpan.pdf)

<span style="color:orange">Fundings</span>: [NSF SHF 2331301](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2331301&HistoricalAwards=false), [NSF SHF 2508118](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2508118&HistoricalAwards=false)

</div>

<div class="pillar-card trustworthy" markdown="1">
<span class="pillar-tag">Pillar 2</span>

### Trustworthy AI Systems

As AI systems and agents are increasingly composed from third-party models, datasets, tools, and workflows, understanding and ensuring their trustworthiness becomes a top priority. This pillar studies trust as a connected stack, from <strong>AI supply chain and provenance</strong>, to <strong>security and risk</strong>, to <strong>reliability and verification</strong> of multi-agent workflows, to <strong>trust-aware decision making</strong>.

<span style="color:blue">Publications</span>: [eMicro (CCS \'26)](.), [TARA (SRDS \'26)](.), [HuggingGraph (CIKM \'25)](.), [CloudCover (ACSAC \'24)](./), [HermesSim (USENIX Security \'24)](./), [API2Vec (ISSTA \'23)](.), [Illuminati (EuroS&P \'22)](../files/22_EuroSP_Illuminati.pdf), [DEFInit (USENIX Security \'21)](https://www.usenix.org/conference/usenixsecurity21/presentation/ji), [BugGraph (AsiaCCS \'21)](../files/21_AsiaCCS_BugGraph.pdf), [APT detection (RAID \'20)](../files/20_RAID_lateral_movement.pdf)

<span style="color:orange">Fundings</span>: [NSF OAC 2516003](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2516003&HistoricalAwards=false), [NSF OAC 2419843](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2419843)

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
