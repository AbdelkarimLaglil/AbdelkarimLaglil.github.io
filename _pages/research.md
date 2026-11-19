---
layout: archive
permalink: /research/
title: "Research"
excerpt: "Research on migrant agency under hostility, violence across borders, and legacies of violence in Spain."
author_profile: true
---

One question runs through my work: how do people respond when politics turns hostile or violent against them? I follow it mostly through migrants, in the places where they live and in the places they come from.

Select a stage to jump to the project behind it.

<div class="lh-map">
<div class="lh-row">
<button type="button" class="lh-node" data-target="lh-borders" aria-pressed="false"><span class="t">Where they come from</span><span class="s">Electoral violence and state power</span></button>
<button type="button" class="lh-node" data-target="lh-hostility" aria-pressed="false"><span class="t">What migrants do</span><span class="s">Exit, voice, staying, sending money</span></button>
<button type="button" class="lh-node" data-target="lh-hostility" aria-pressed="false"><span class="t">Where they live</span><span class="s">Hostility as political violence</span></button>
</div>
<svg class="lh-back" viewBox="0 0 640 52" aria-hidden="true" focusable="false"><defs><marker id="lh-arrow" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="7" markerHeight="7" orient="auto-start-reverse"><path d="M0 0L10 5L0 10z" fill="currentColor"/></marker></defs><path d="M533 2 Q320 40 107 2" fill="none" stroke="currentColor" stroke-width="1.6" stroke-dasharray="1 6" stroke-linecap="round" marker-end="url(#lh-arrow)"/><text x="320" y="46" text-anchor="middle">money and political voice travel back</text></svg>
<button type="button" class="lh-node lh-wide" data-target="lh-spain" aria-pressed="false"><span class="t">Legacies of past violence in Spain</span><span class="s">Mass graves, state withdrawal, transitional justice</span></button>
</div>

<div class="lh-card" id="lh-hostility">
<h2>Migrant agency under hostility</h2>
<p class="q">How do migrants respond to hostility where they settle: leave, speak up, stay, or send money home?</p>
<dl>
<dt>Hostility</dt><dd>Hate crimes, anti-immigrant rallies and far-right exclusionary politics, which I treat as political violence</dd>
<dt>Setting</dt><dd>Germany, mainly but not exclusively, and Spain</dd>
<dt>Data</dt><dd>SOEP panel, 1984–2023; intermunicipal mobility data around relevant episodes in Spain</dd>
<dt>Thesis</dt><dd>Navigating Hostility: Migrant Agency in Response to Far-Right Exclusionary Politics</dd>
<dt>Supervisors</dt><dd><a href="https://sites.google.com/view/sebastianlavezzolo">Sebastián Lavezzolo</a> (UC3M) and <a href="https://web.comillas.edu/profesor/cmeseguer">Covadonga Meseguer</a> (ICADE)</dd>
</dl>
<ul class="papers">
<li><a href="{{ site.baseurl }}/work-in-progress/">Exit, Voice and the Limits of Both</a></li>
<li><a href="{{ site.baseurl }}/work-in-progress/">Money, Staying, and Perceived Hostility</a></li>
</ul>
</div>

<div class="lh-card now" id="lh-borders">
<h2>Violence across borders</h2>
<p class="q">How does violence in migrants' countries of origin connect to what they do abroad?</p>
<dl>
<dt>Focus</dt><dd>Electoral violence, remittances, and how authoritarian states use migrants' money and ties to build transnational power</dd>
<dt>Setting</dt><dd>Countries of origin, including Africa</dd>
</dl>
<ul class="papers">
<li><a href="{{ site.baseurl }}/work-in-progress/">Remittances and Electoral Violence in Africa</a></li>
<li><a href="{{ site.baseurl }}/work-in-progress/">The Political Valence of Financial Remittances</a>, with <a href="https://sites.google.com/view/sebastianlavezzolo">Sebastián Lavezzolo</a></li>
</ul>
</div>

<div class="lh-card quiet" id="lh-spain">
<h2>Legacies of violence in Spain</h2>
<p class="q">What happens when the state withdraws from transitional justice, and what does grassroots human rights work change?</p>
<dl>
<dt>Focus</dt><dd>Mass grave exhumations in Spain</dd>
<dt>With</dt><dd>Francisco Villamil, Paloma Aguilar and Fernando de la Cuesta</dd>
</dl>
<ul class="papers">
<li><a href="{{ site.baseurl }}/work-in-progress/">Broken promises: State withdrawal and mass grave exhumations in Spain</a></li>
<li><a href="{{ site.baseurl }}/work-in-progress/">The consequences of grassroots human rights</a></li>
</ul>
</div>

<script>
(function(){var m=document.querySelector('.lh-map');if(!m)return;m.classList.add('js');
var nodes=m.querySelectorAll('.lh-node'),reduce=window.matchMedia&&window.matchMedia('(prefers-reduced-motion: reduce)').matches;
for(var k=0;k<nodes.length;k++){nodes[k].addEventListener('click',function(){
var id=this.getAttribute('data-target'),c=document.getElementById(id);if(!c)return;
for(var i=0;i<nodes.length;i++){nodes[i].setAttribute('aria-pressed',nodes[i]===this?'true':'false');}
var all=document.querySelectorAll('.lh-card');for(var j=0;j<all.length;j++){all[j].classList.remove('flash');}
c.scrollIntoView({behavior:reduce?'auto':'smooth',block:'start'});void c.offsetWidth;c.classList.add('flash');});}
})();
</script>

See the papers in [Work in progress]({{ site.baseurl }}/work-in-progress/) and where I have presented them in [Talks]({{ site.baseurl }}/talks/).
