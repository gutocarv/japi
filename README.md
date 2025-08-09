Testes de detecção de focos de incendio mediante triangulação- projeto do grupo de monitormento de incendio da Serra do Japi - Jundiaí - SP

a Idéia é criar ferramentas colaborativas para identificação de focos de incendios florestais 
testando dois conceitos : detecção por drone e por celular - 

1- **triangulação usando dados de voo do drone DJI**
aqui tem o protótipo do sistema de triangulação usando drone <https://gutocarv.github.io/japi/treiangula5.html> esse app recebe as plnilhas de voo padrão DJI enviadas emformato CSV que podem ser baixadas do DJI-FLY no celular ou ainda de uma conta em plataformas de agregação tipo <https://airdata.com>
<p class="p1">para ser efetivo é necessário seguir um protocolo de monitoramento<span class="Apple-converted-space"> </span></p>
<ul class="ul1">
  <li class="li1"><span class="Apple-converted-space">    </span>subir -<span class="Apple-converted-space"> </span></li>
  <li class="li1"><span class="Apple-converted-space">    </span>rotacionar até achar o foco de incendio ,<span class="Apple-converted-space"> </span></li>
  <li class="li1"><span class="Apple-converted-space">    </span>centralizar o foco no quadro,<span class="Apple-converted-space"> </span></li>
  <li class="li1"><span class="Apple-converted-space">    </span>voar o drone à frente com o foco centralizado - 20 segundos</li>
  <li class="li1"><span class="Apple-converted-space">    </span>retornar a base,<span class="Apple-converted-space"> </span></li>
  <li class="li1"><span class="Apple-converted-space">    </span>fazer deslocamento lateral (90º) por pelo menoa 200m<span class="Apple-converted-space"> </span></li>
  <li class="li1"><span class="Apple-converted-space">    </span>recentralizar no foco na imagem<span class="Apple-converted-space"> </span></li>
  <li class="li1"><span class="Apple-converted-space">    </span>voar novamente à frente</li>
</ul>
    
2- **triangulação a partir de dados de celular** <https://gutocarv.github.io/japi/tri_japi.html>

Aqui os dados são enviados a partir da localização e orientação, 
ou seja o usuário observa sinais de fumaça, bate uma foto e envia as coordenadas do ponto bem como a orientação magnética (bússola) 

