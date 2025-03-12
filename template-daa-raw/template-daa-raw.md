<!DOCTYPE html>
<html>
<body>
<p align="left">
<img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250306104014185.png?raw=true" alt="Banner">
<p/>
  
<p align="left"; ; style="background:#245bdb; color:white; font-size:8; font-weight: bold; width:40%">
Migración NODO LDN 1 – vCCAP – HUB CORABASTO - EXITOSO
<p

<pre style="background:white; font-size:6">
A continuación, encontrarán el reporte de estado posterior a la actividad realizada en ventana de trabajo.  
</pre>
</p>
<p style="color:#8abdb5; font-size:10; font-weight: bold">☰ <u>SUMMARY</u></p>
<p>This is some <u>mispeled</u> text.</p>

<pre style="background:white; font-size:6; width:40%">
➢ Se realizan respaldos de configuración de los equipos involucrados.
➢ Se realizaron pruebas de verificación del estado de funcionamiento del RMD.
➢ Se realizaron pruebas de conectividad de redes de servicio (CM, Internet y MTA).
➢ Se realizaron validaciones del servicio de video.
➢ Se realizaron validaciones de parámetros RF de los puertos del RMD.
➢ Se toman datos comparativos del conteo de la cantidad de CM y STB migrados.
➢ Se toma registro de los CM con aprovisionamiento al cierre de la ventana.
➢ Se realizó limpieza de RMD en status "pending" y "offline" que no serán migrados.
➢ Se realizó limpieza de Startup-config templates que no serán usados en el despliegue.  
</pre>
<p style="color:#bf4c58; font-size:10"; font-weight: bold>☰ DOCSIS</p>
<p style="color:#c77b4a; font-size:10; font-weight: bold">① TABLA RESUMEN CM</p>

<table border="1"; style="width:auto; line-height: 8px">
  <tr>
    <th colspan="6"; style="font-weight:bold; text-align: center; vertical-align: middle; font-size:0.4em">Resumen Migración Nodo U04041AB</th>
  </tr>
    <tr>
    <th align="left"; style="background:#808080; vertical-align: middle; font-size:0.4em">Variables</th>
    <th style="background:#7FAC53; text-align: center; vertical-align: middle; font-size:0.4em">PRE</th> 
    <th style="background:#DE8242; text-align: center; vertical-align: middle; font-size:0.4em">POST</th> 
    <th style="background:#BFBFBF; text-align: center; vertical-align: middle; font-size:0.4em">Var</th>
    <th style="background:#BFBFBF; text-align: center; vertical-align: middle; font-size:0.4em">% CM</th> 
    <th style="background:#BFBFBF; text-align: center; vertical-align: middle; font-size:0.4em">Status</th> 
  </tr>
  <tr>
    <th align="left"; style="background:#BFBFBF; font-size:0.4em; vertical-align: middle"># CMs</th>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">142</td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">186</td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">-44</td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">131%</td>
    <td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-size:0.4em">OK</td>
  </tr>
<tr>
    <th align="left"; style="background:#BFBFBF; font-size:0.4em; vertical-align: middle"># CMs Oper</th>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">0</td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">183</td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">-183</td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle"></td>
    <td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-size:0.4em">OK</td>
  </tr>
  <tr>
    <th align="left"; style="background:#F2F2F2; font-size:0.4em; vertical-align: middle">Avg US RxPwr (CMTS)</th>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">0,00</td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">140,92</td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle"></td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle"></td>
    <td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-size:0.4em">OK</td>
  </tr>
  <tr>
    <th align="left"; style="background:#F2F2F2; font-size:0.4em; vertical-align: middle">Avg US SNR (CMTS)</th>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">359,67</td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">368,32</td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle"></td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle"></td>
    <td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-size:0.4em">OK</td>
  </tr>
  <tr>
    <th align="left"; style="background:#BFBFBF; font-size:0.4em; vertical-align: middle">Avg US TxPwr (CM)</th>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">470,30</td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">444,91</td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">-44</td>
    <td align="center"; style="font-size:0.4em; vertical-align
      : middle">131%</td>
    <td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-size:0.4em">OK</td>
  </tr>
  <tr>
    <th align="left"; style="background:#BFBFBF; font-size:0.4em; vertical-align: middle">Ave DS RxPwr (CM)</th>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">25,46</td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">35,49</td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle"></td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle"></td>
    <td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-size:0.4em">OK</td>
  </tr>
  <tr>
    <th align="left"; style="background:#BFBFBF; font-size:0.4em; vertical-align: middle">Ave DS RxPwr (CM)</th>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">384,96</td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle">413,17</td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle"></td>
    <td align="center"; style="font-size:0.4em; vertical-align: middle"></td>
    <td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-size:0.4em">OK</td>
  </tr>
</table>

<p style="color:#c77b4a; font-size:10; font-weight: bold">② IP NULL</p>

<pre>
<code style="width:40%; background:#f4f4f4;font-size:4"; class="language-javascript">
Cable Modems con IP Nulas al Cierre de la Ventana

RMD-ACC-U04041AB# show cable modem detail showmac | include NULL_IP     
8c8a.bb3d.86ad  CPE(MTA)  8c8a.bb3d.86ae Filter-Group:Up=0 Down=0 IP  =NULL_IP
8c8a.bb40.2e21  CPE(MTA)  8c8a.bb40.2e22 Filter-Group:Up=0 Down=0 IP  =NULL_IP
b85e.718d.0614  CPE(MTA)  b85e.718d.0615 Filter-Group:Up=0 Down=0 IP  =NULL_IP
001c.fb32.dec4  CPE(MTA)  001c.fb32.dec6 Filter-Group:Up=0 Down=0 IP  =NULL_IP
1033.bf7e.d79c  CPE(MTA)  1033.bf7e.d79d Filter-Group:Up=0 Down=0 IP  =NULL_IP
3093.bcea.b218  CPE(MTA)  3093.bcea.b21b Filter-Group:Up=0 Down=0 IP  =NULL_IP
3093.bced.6068  CPE(MTA)  3093.bced.606b Filter-Group:Up=0 Down=0 IP  =NULL_IP
3cb7.4b7d.7e74  CPE(MTA)  3cb7.4b7d.7e75 Filter-Group:Up=0 Down=0 IP  =NULL_IP
6cba.b8f8.09c0  CPE(MTA)  6cba.b8f8.09c3 Filter-Group:Up=0 Down=0 IP  =NULL_IP
8c8a.bb3d.8c3e  CPE(MTA)  8c8a.bb3d.8c3f Filter-Group:Up=0 Down=0 IP  =NULL_IP
8c8a.bb3e.bcf3  CPE(MTA)  8c8a.bb3e.bcf4 Filter-Group:Up=0 Down=0 IP  =NULL_IP
8c8a.bb3f.a4d3  CPE(MTA)  8c8a.bb3f.a4d4 Filter-Group:Up=0 Down=0 IP  =NULL_IP
c03c.04fb.5390  CPE(MTA)  c03c.04fb.5393 Filter-Group:Up=0 Down=0 IP  =NULL_IP
c03c.04fb.5510  CPE(MTA)  c03c.04fb.5513 Filter-Group:Up=0 Down=0 IP  =NULL_IP
c83f.b47b.7052  CPE(MTA)  c83f.b47b.7053 Filter-Group:Up=0 Down=0 IP  =NULL_IP
d833.b723.a480  CPE(MTA)  d833.b723.a483 Filter-Group:Up=0 Down=0 IP  =NULL_IP
RMD-ACC-U04041AB#
</code>
</pre>

<p style="color:#c77b4a; font-size:10; font-weight: bold">③ Pruebas de conectividad de redes de servicio (CM, Internet y MTA)</p>


<pre style="background:#f4f4f4;font-size:4; width:60%">
<code class="language-javascript">
Ping a google.com redes de Internet (públicas)

RMD-ACC-U04041AB# ping 8.8.8.8 source-ip 100.77.146.1
Using Source-IP for cable-mac 0.0
Sending IP ping to: 8.8.8.8 from 100.77.146.1
ping (8.8.8.8): 100 data bytes
!!!!!
</code>
</pre>

<pre style="background:#f4f4f4;font-size:4; width:60%">
<code class="language-javascript">
Ping a servidores de aprovisionamiento (DHCP)

RMD-ACC-U04041AB# ping 192.168.9.193 source-ip 10.253.146.1
Using Source-IP for cable-mac 0.0
Sending IP ping to: 192.168.9.193 from 10.253.146.1
ping (192.168.9.193): 100 data bytes
!!!!!
5 packets transmitted, 5 packets received
round-trip min/avg/max = 8.985/9.189/9.553 ms
RMD-ACC-U04041AB# ping 192.168.9.194 source-ip 10.253.146.1
Using Source-IP for cable-mac 0.0
Sending IP ping to: 192.168.9.194 from 10.253.146.1
ping (192.168.9.194): 100 data bytes
!!!!!
5 packets transmitted, 5 packets received
round-trip min/avg/max = 9.029/9.269/9.662 ms
RMD-ACC-U04041AB#
</code>
</pre>

<pre style="background:#f4f4f4;font-size:4; width:60%">
<code class="language-javascript">
Estado de conexiones COPS

RMD-ACC-U04041AB# show packetcable cops servers
Proto   Local Addr      Server Addr.Port       KA     PCMM   IPSec UpTime
Timer  PSID
------- --------------- ---------------------- -----  ------ ----- -----------------
PC vI09 10.156.165.3    172.22.4.66.3030         30s  N/A    No      0 days  0:36:10
RMD-ACC-U04041AB#
</code>
</pre>

<pre style="background:#f4f4f4;font-size:4; width:60%">
<code class="language-javascript">
Ping a Servidores COPS desde red de MTA

RMD-ACC-U04041AB# ping 172.22.4.66 source-ip 10.155.40.1
Using Source-IP for cable-mac 0.0
Sending IP ping to: 172.22.4.66 from 10.155.40.1
ping (172.22.4.66): 100 data bytes
!!!!!
5 packets transmitted, 5 packets received
round-trip min/avg/max = 9.131/9.164/9.258 ms
</code>
</pre>

<p style="color:#c77b4a; font-size:4; font-weight: bold">④ URL Test 🌐</p>

|           www.claro.com.ec           |         www.teleamazonas.com         |           www.facebook.com           |
| :----------------------------------: | :----------------------------------: | :----------------------------------: |
| <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125735.png?raw=true"> | <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306115528.png?raw=true"> | <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306115532.png?raw=true"> |
|           www.Formula1.com           |            www.google.com            |           www.youtube.com            |
| <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306115353.png?raw=true"> | <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306115357.png?raw=true"> | <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306115401.png?raw=true"> |

<p style="color:#c77b4a; font-size:4; font-weight: bold">⑤ Ping Test to CDN 🌐</p>

| <span style="color:Blue; font-size:0.6em">Youtube:<br>rr1---sn-xj0uxa-btxs.googlevideo.com</span> | <span style="color:Blue; font-size:0.6em">Facebook:<br>rr1---sn-xj0uxa-btxs.googlevideo.com</span> | <span style="color:Blue; font-size:0.6em">Netflix:<br>rr1---sn-xj0uxa-btxs.googlevideo.com</span> |
| :-----------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------: |
|                               <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306115211.png?raw=true">                                |                                <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306115225.png?raw=true">                                |                               <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306115233.png?raw=true">                                |

<p style="color:#c77b4a; font-size:4; font-weight: bold">⑥ Parámetros de referencia Upstream (US) 🌐</p>

| <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125501.png"> | <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125520.png"> |
| ------------------------------------ | ------------------------------------ |
| <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125600.png?raw=true"> | <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125607.png?raw=true"> |
| <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125613.png?raw=true"> | <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125637.png?raw=true"> |
| <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125649.png?raw=true"> | <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125656.png?raw=true"> |

<p style="color:#c77b4a; font-size:4; font-weight: bold">⑦ Parámetros de referencia Downstream (DS) 🌐</p>

| <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250306114236406.png"> | <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250306114239811.png"> |
| ------------------------------ | ------------------------------ |
| <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250306114244251.png?raw=true"> | <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250306114249653.png?raw=true"> |

<p style="color:#bf4c58; font-size:6; font-weight: bold">☰ VIDEO</p>

<p style="color:#c77b4a; font-size:10; font-weight: bold">① Tabla resumen STB</p>

<div align="left">
<table border="1"; width="1px"; border-collapse="collapse"; padding="8"; width:62%; style="color:Black; font-size:4"
<thead>
<tr>
<th colspan="7"; style="background:#97C5D7; font-weight:bold; text-align: center; vertical-align: middle">SET TOP BOXES REGISTRADO</th>
</tr>
  <tr>
    <th colspan="2"; align="left"; style="background:#B9D9E5; text-align: center; vertical-align: middle; font-size:0.7em">Variables</th>
    <th style="background:#7FAC53; text-align: center; vertical-align: middle; font-size:0.7em">PRE</th> 
    <th style="background:#DE8242; text-align: center; vertical-align: middle; font-size:0.7em">POST</th> 
    <th style="background:#A6A6A6; text-align: center; vertical-align: middle; font-size:0.7em">Var</th>
    <th style="background:#A6A6A6; text-align: center; vertical-align: middle; font-size:0.7em">% STB</th> 
    <th style="background:#A6A6A6; text-align: center; vertical-align: middle; font-size:0.7em">Status</th> 
  </tr>
  <tr>
    <th colspan="2"; align="left"; style="background:#B9D9E5; text-align: left; font-size:0.7em"># STB Nodo</th>
    <td align="center"; style="; font-weight:bold; font-size:1em">6</td>
    <td align="center"; style="; font-weight:bold; font-size:1em">6</td>
    <td align="center"; style="; font-weight:bold; font-size:1em">0</td>
    <td rowspan="3"; align="center"; style="background:white; text-align: center; vertical-align: middle">100%</td>
    <td rowspan="3"; align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:1em">OK</td>
  </tr>
  <tr>
    <th align="left"; style="background:#B9D9E5; font-size:0.7em"# STB Old US ID</th>
    <th style="background:#B1C595; text-align: center; vertical-align: middle; font-size:0.7em">1407</th> 
    <td style="font-size:0.7em"; align="center">72</td>
    <td style="font-size:0.7em"; align="center">66</td>
    <td style="font-size:0.7em"; align="center">-6</td>
  </tr>
  <tr>
    <th align="left"; style="background:#B9D9E5; font-size:0.7em"># STB new US ID</th>
    <th style="background:#EAB38A; text-align: center; vertical-align: middle; font-size:0.7em">1421</th> 
    <td style="font-size:0.7em"; align="center">0</td>
    <td style="font-size:0.7em"; align="center">9</td>
    <td style="font-size:0.7em"; align="center">9</td>
  </tr>
</table>
</div>
<p style="color:#c77b4a; font-size:10; font-weight: bold">② Información del nodo a migrar</p>

<div align="left">
<table border="1"; width="1px"; border-collapse="collapse"; padding="8"; width:62%; style="color:Black; font-size:4"
<thead>
<tr>
<th colspan="2"; align="center"; style="background:#97C5D7">DATOS DEL NODO</th>
</tr>
  <tr>
    <th align="left"; style="background:#B9D9E5">Nodo RMD</th> <td>RMD-ACC-U04041AB</td>  </tr><tr>
    <th align="left"; style="background:#B9D9E5">Mac Address</th> <td>C0:94:35:3A:60:90</td>   </tr><tr>
    <th align="left"; style="background:#B9D9E5">IP Address <td>172.20.102.131</td></tr><tr>
    <th align="left"; style="background:#B9D9E5">Region<td>REGION1</td></tr><tr>
    <th align="left"; style="background:#B9D9E5">HUB<td>MARISCAL</td></tr><tr>
    <th align="left"; style="background:#B9D9E5">DS Plant<td>Quito Vhub 4</td></tr><tr>
    <th align="left"; style="background:#B9D9E5">US Plant<td>QUITO VH 4</td></tr><tr>
    <th align="left"; style="background:#B9D9E5">IP NC2000<td>192.168.7.10</td></tr><tr>
    <th align="left"; style="background:#B9D9E5">vARPD<td>q4_varpd1</td>
  </tr>
</table>
</div>
<p style="color:#c77b4a; font-size:10; font-weight: bold">③ Validación del RMD vía CLI</p>

<div align="left">
<table border="1"; width="1px"; border-collapse="collapse"; padding="8"; width:62%; style="color:Black; font-size:4"
<thead>
<tr>
  <tr>
    <th colspan="3"; align="center"; style="background:#97C5D7; vertical-align: middle; font-size:0.7em">Variables</th>
  </tr>
  <tr>
    <th align="left"; style="background:#B9D9E5; font-size:0.7em">Aux Core IP</th>
    <td align="center"; style="; font-size:0.7em">172.29.96.130</td>
    <td align="center"; style="background:#7BFC45;; font-weight:bold; font-size:0.7em">OK</td>
  </tr>
  <tr>
    <th align="left"; style="background:#B9D9E5; font-size:0.7em">Aux Core State</th>
    <td align="center"; style="; font-size:0.7em">Operational</td>
    <td align="center"; style="background:#7BFC45;; font-weight:bold; font-size:0.7em">OK</td>
  </tr>
  <tr>
    <th align="left"; style="background:#B9D9E5; font-size:0.7em">ntp associated</th>
    <td align="center"; style="; font-size:0.7em">*10.57.110.52</td>
    <td align="center"; style="background:#7BFC45; font-weight:bold; font-size:0.7em">OK</td>
  </tr>
<tr>
    <th colspan="3"; align="center"; style="background:#97C5D7; vertical-align: middle; font-size:0.7em">Bandwidth</th>
  </tr>
  <tr>
    <th align="left"; style="background:#B9D9E5; font-size:0.7em">lag 0</th>
    <td align="center"; style="; font-size:0.7em">2969,00 Mbps</td>
    <td align="center"; style="background:#7BFC45; font-weight:bold; font-size:0.7em">OK</td>
  </tr>
  <tr>
    <th colspan="3"; align="center"; style="background:#97C5D7; vertical-align: middle; font-size:0.7em">Multicast</th>
  </tr>
  <tr>
    <th align="left"; style="background:#B9D9E5; font-size:0.7em">Broadcast</th>
    <td align="center"; style="; font-size:0.7em">239.255.17.33</td>
    <td align="center"; style="background:#7BFC45; font-weight:bold; font-size:0.7em">OK</td>
  </tr>
  <tr>
    <th align="left"; style="background:#B9D9E5; font-size:0.7em">Reg2 Broadcast</th>
    <td align="center"; style="; font-size:0.7em">239.255.17.35</td>
    <td align="center"; style="background:#7BFC45; font-weight:bold; font-size:0.7em">OK</td>
  </tr>
  <tr>
    <th align="left"; style="background:#B9D9E5; font-size:0.7em">Piolot Broadcast</th>
    <td align="center"; style="; font-size:0.7em">239.255.17.37</td>
    <td align="center"; style="background:#7BFC45; font-weight:bold; font-size:0.7em">OK</td>
  </tr>
    <tr>
    <th align="left"; style="background:#B9D9E5; font-size:0.7em">Downstream OOB</th>
    <td align="center"; style="; font-size:0.7em">239.255.17.77</td>
    <td align="center"; style="background:#7BFC45; font-weight:bold; font-size:0.7em">OK</td>
  </tr>
</table>
</div>
<p style="color:#c77b4a; font-size:10; font-weight: bold">④ Validación de Canales de Broadcast, OOB y Pilot</p>

<div align="left">
<table border="1"; width="1px"; border-collapse="collapse"; padding="8"; width:62%; style="color:Black; font-size:4"
<thead>
<tr>
<th colspan="7"; style="background:#97C5D7; text-align: center; vertical-align: middle; font-size:0.5em">VTM configure</th>
<th colspan="7"; style="background:#97C5D7; text-align: center; vertical-align: middle; font-size:0.5em">RMD Configure</th>
</tr>
  <tr>
    <th align="center"; style="background:#A6A6A6; text-align: center; vertical-align: middle; font-size:0.5em">ID</th>
    <th align="center"; style="background:#A6A6A6; text-align: center; vertical-align: middle; font-size:0.5em; width: 1px">Service Groups</th>
    <th align="center"; style="background:#A6A6A6; text-align: center; vertical-align: middle; font-size:0.5em; width: 10%">Session ID</th>
    <th align="center"; style="background:#A6A6A6; text-align: center; vertical-align: middle; font-size:0.5em">Freq MHZ</th>
    <th align="center"; style="background:#A6A6A6; text-align: center; vertical-align: middle; font-size:0.5em">Multicat address</th>
    <th align="center"; style="background:#A6A6A6; text-align: center; vertical-align: middle; font-size:0.5em">UDP Port</th>
    <th align="center"; style="background:#A6A6A6; text-align: center; vertical-align: middle; font-size:0.5em">DS P/TCH</th>
    <th align="center"; style="background:#A6A6A6; text-align: center; vertical-align: middle; font-size:0.5em">Annex</th>
    <th align="center"; style="background:#A6A6A6; text-align: center; vertical-align: middle; font-size:0.5em">InPackets received</th>
    <th align="center"; style="background:#A6A6A6; text-align: center; vertical-align: middle; font-size:0.5em">OSS Packets</th>
    <th align="center"; style="background:#A6A6A6; text-align: center; vertical-align: middle; font-size:0.5em">OverFlow Events</th>
    <th align="center"; style="background:#A6A6A6; text-align: center; vertical-align: middle; font-size:0.5em">UnderFlow Events</th>
    <th align="center"; style="background:#A6A6A6; text-align: center; vertical-align: middle; font-size:0.5em">Dropped Packets</th>
    <th align="center"; style="background:#A6A6A6; text-align: center; vertical-align: middle; font-size:0.5em">Status</th>
  </tr>
  <tr>
  <th colspan="14"; style="background:#97C5D7; text-align: center; vertical-align: middle; font-size:5">BROADCAST CHANNELS</th>
  </tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-207 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000fffa</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">207</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/122</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188547</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">2</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-213 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000fffd</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">213</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/110</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188622</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">3</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-219 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffef</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">219</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/103</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188658</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">4</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-225 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffee</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">225</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/106</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188646</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">5</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-231 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffed</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">231</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/94 </td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188709</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-237 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffd2</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">237</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/93 </td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188712</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">7</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-243 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffe1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">243</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/97 </td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188694</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-249 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffd9</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">249</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/117</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188571</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">9</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-255 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffe5</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">255</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/91 </td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188724</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-261 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffdd</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">261</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/126</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188532</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">11</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-267 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffea</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">267</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/121</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188556</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">12</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-273 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffe0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">273</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/100</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188673</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">13</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-291 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffe4</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">291</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/96 </td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188700</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">14</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-297 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffd6</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">297</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/118</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188568</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">15</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-303 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffda</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">303</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/113</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188598</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">16</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-309 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffe9</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">309</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/120</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188559</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">17</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-315 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffdf</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">315</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/124</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188544</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">18</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-321 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffd8</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">321</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/116</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188580</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">19</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-351 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffd5</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">351</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/102</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188664</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">20</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-363 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffdc</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">363</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/125</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188535</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">21</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-381 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffec</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">381</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/127</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188526</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">22</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-387 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffe6</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">387</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/92 </td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188718</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">23</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-393 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffdb</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">393</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/115</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188586</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">24</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-411 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffe3</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">411</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/95 </td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188703</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">25</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-429 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffe2</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">429</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/99 </td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188676</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">26</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-435 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffd7</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">435</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/119</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188565</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">27</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-441 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffe8</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">441</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/104</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188655</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">28</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-447 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffde</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">447</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/123</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188544</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">29</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-453 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffeb</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">453</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/111</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188607</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">30</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-465 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffd4</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">465</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/105</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188649</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">31</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-471 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffe7</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">471</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/109</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188628</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">32</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-477 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffd3</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">477</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/108</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188634</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-483 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffd1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">483</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.33</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10033</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/98 </td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6188688</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
  <th colspan="14"; style="background:#97C5D7; text-align: center; vertical-align: middle; font-size:5">REGIONAL BROADCAST CHANNELS</th>
  </tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">BC-333 REG Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffcf</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">333</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.35</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10035</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/101</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6187299</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em"></td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em"></td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em"></td>
</tr>
<tr>
  <th colspan="14"; style="background:#97C5D7; text-align: center; vertical-align: middle; font-size:5">DOWNSTREAM OOB CHANNEL</th>
  </tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">OOB-OM-MARISCAL</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000fffb</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">107,4</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.77</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10077</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/55-1/0 </td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">209054</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">n/a</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">n/a</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">n/a</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
  <th colspan="14"; style="background:#97C5D7; text-align: center; vertical-align: middle; font-size:5">UPSTREAM OOB CHANNEL</th>
  </tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">Q4_VARPD1-US1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">AC146063</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">12,128</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">q4_varpd1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">N/A</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/55-1/2 </td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">n/a</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">n/a</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">n/a</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">n/a</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">n/a</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
  <th colspan="14"; style="background:#97C5D7; text-align: center; vertical-align: middle; font-size:5">REGIONAL BROADCAST CHANNELS</th>
  </tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">Pilot 177 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffcd</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">177</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.37</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10037</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/107</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6187269</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">2</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">Pilot 861 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffcc</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">861</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.37</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10037</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/114</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6187221</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
<td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">3</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">Pilot 993 Mhz</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">8000ffcb</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">993</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">239.255.17.37</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">10037</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0/vid/112</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">B</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">6187230</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">1</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="text-align: center; vertical-align: middle; font-size:0.4em">0</td><td align="center"; style="background:#7BFC45; text-align: center; vertical-align: middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
</table>
</div>
<p style="color:#c77b4a; font-size:4; font-weight: bold">⑤ Paquetes fuera de secuencia por Transport Stream</p>

| <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250307132155821.png?raw=true"> |
| ------------------------------ |
<p style="color:#bf4c58; font-size:4; font-weight: bold">⑥ Paquetes Dropeado por Canal de Video</p>

| <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250307132303777.png?raw=true"> |
| ------------------------------ |
<p style="color:#c77b4a; font-size:4; font-weight: bold">⑦ Paquetes Dropeado por Canal de Video</p>

| STB: 000-01783-33438-127 Comando:Refresh | <font color="#9bbb59">Respuesta</font> |
| ---------------------------------------- | -------------------------------------- |
| <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250307132422325.png?raw=true"> | <img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250307132406805.png?raw=true"> |


<p style="color:#8abdb5; font-size:2; font-weight: bold">☰ OBSERVACIONES</p>
<pre style="background:white; font-size:1">
➢ Se realizó la migración del nodo de manera exitosa.
➢ Se aplicó un soft reset al nodo para actualizar la configuración de la frecuencia 499.250 de manera exitosa.
</pre>

<p style="color:#8abdb5; font-size:2; font-weight: bold">☰ RESULTADO DEL TRABAJO</p>

<pre style="background:#FFFFFF; color:green; font-size:14; font-weight: bold"; align="left">
✅ EXITOSO
</pre>
</div>
</body>
</html>
</html>
