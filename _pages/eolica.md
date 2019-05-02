---
key: 2
title: Eólica
permalink: /eolica/
excerpt: Serviços de torres de ventos.
image: pic02.jpg
background-image: pic02.jpg
---
{% include post_picwrap.html pos="left" src="/images/pic01.jpg" %}

## INSTRUMENTAÇÃO DE ESTAÇÕES ANEMOMÉTRICAS

Parte fundamental de um projeto, a campanha de medição é também um dos pontos mais críticos onde precisão, qualidade, conhecimento e agilidade nos serviços se fazem necessários para atingirmos objetivos.

### Serviços Principais

{% include post_picwrap.html pos="right" src="/images/meteo40.jpg" %}

Dentro das normas nacionais e internacionais[^1] de segurança seguimos as regras para as boas
práticas de instalação de torres anemométricas voltadas para o estudo de potencial eólico.

Trabalhamos com os melhores e mais poderosos equipamentos existentes no mercado para registros e análises de potencial energético do vento. Nossas estações anemométricas também contam com os melhores e mais avançados instrumentos para medições de velocidade, direção e climáticos.

{% include post_picwrap.html pos="left" src="/images/telem.jpg" %}


Apresentamos soluções em comunicação de sistemas de monitoramento para medições anemométricas e solarimétricas. Instalação e manutenção de equipamentos de telecomunicações (GSM, Satélite e Wifi), sistemas de balizamento noturo e monitoramento por cameras. Integração a sistemas SCADA[(Supervisory Control and Data Acquisition)](https://www.ammonit.com/pt/wind-solar-messsysteme/scada-windpark-ueberwachung).

***
[^1]:IEC – International
Electrothecnical Commission, IEA - International Energy Agency, MEASNET - Network of European Measuring Institutes, AWEA - American Wind Energy Association, ABNT – Associação Brasileira de Normas Técnicas e o INMETRO – Instituto Nacional de Metrologia

<!--{%
if site.social.linkedin-square %}
<div class="table-wrapper">
  <table class="alt"><tbody><tr><td style="text-align: center;">Visit my
  <a target="_blank" href="{{ site.social.linkedin-square }}">LinkedIn profile</a></td>
  </tr></tbody></table>
</div>{%
endif %}
{%
if site.categories.eolica %}
<div class="table-wrapper">
  <table>
    <tbody>{%
      include fn_groupsort_reverse.html unsorted=site.categories.eolica groupby='priority' sortby='date'
%}{%  for eolica in sorted_list %}
      <tr>
        <td><b><a href="{{ eolica.url | prepend: site.baseurl }}">{{ eolica.title }}</a></b></td>
        <td>{{ eolica.date | date: "%b %Y" }}</td>
        <td>{{ eolica.excerpt | strip_html | truncatewords: 12 }}</td>
        <td>
          {% include techlist.html %}
        </td>
      </tr>{%
      endfor %}
    </tbody>
  </table>
</div>{%
  if site.eolica_in_progress %}
  <div class="works_inprogress">In-progress, more to come.</div>{%
  endif %}{%
endif
%}-->
