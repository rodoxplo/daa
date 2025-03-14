<html>
<head>
<meta charset="UTF-8" />
    <meta name="viewport" content=
        "width=device-width, initial-scale=1.0" <meta/>
<title>DAA Report</title>
</head>
<body>
<img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250306104014185.png?raw=true" alt="Banner">
<pre align="left"; style="white-space:pre-line; line-height:20.0px; font-size:12px; font-weight:bold; background:#ffffff; font-family:arial; margin-top:0; margin-bottom:10px; padding:0"><span style="background:#245bdb; color:white">Reporte Migración de nodos a Plataforma DAA – Nodo U04041AB – EXITOSO
</span></pre>

<pre style="white-space:pre-line; line-height:8px; font-family:arial; font-size:10px; background:#ffffff; margin-bottom:10px">A continuación, encontrarán el reporte de estado posterior a la actividad realizada en ventana de trabajo.
</pre>

<p style="color:#8abdb5; font-size:12px; font-weight:bold; margin:0; padding-bottom:10px">☰ <u>SUMMARY</u></p>

<pre style="white-space:pre-line; line-height:8px; font-family:arial; font-size:10px; background:#ffffff">
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
<br>
<p style="color:#bf4c58; font-size:12px; font-weight:bold; margin:0; padding:0px">☰ <u>EVIDENCIAS DOCSIS</u></p>

<p style="color:#c77b4a; font-size:12px; font-weight:bold; padding-top:0; padding-bottom:0">① <u>TABLA RESUMEN CM</u></p>

<table border="1"; style="width:auto; line-height:8px; ">
  <tr>
    <th colspan="6"; style="font-weight:bold; text-align:center; vertical-align:middle; font-size:0.4em">Resumen Migración Nodo U04041AB</th>
  </tr>
    <tr>
    <th align="left"; style="background:#808080; vertical-align:middle; font-size:0.4em">Variables</th>
    <th style="background:#7FAC53; text-align:center; vertical-align:middle; font-size:0.4em">PRE</th> 
    <th style="background:#DE8242; text-align:center; vertical-align:middle; font-size:0.4em">POST</th> 
    <th style="background:#BFBFBF; text-align:center; vertical-align:middle; font-size:0.4em">Var</th>
    <th style="background:#BFBFBF; text-align:center; vertical-align:middle; font-size:0.4em">% CM</th> 
    <th style="background:#BFBFBF; text-align:center; vertical-align:middle; font-size:0.4em">Status</th> 
  </tr>
  <tr>
    <th align="left"; style="background:#BFBFBF; font-size:0.4em; vertical-align:middle"># CMs</th>
    <td style="font-size:0.4em; vertical-align:middle">142</td>
    <td style="font-size:0.4em; vertical-align:middle">186</td>
    <td style="font-size:0.4em; vertical-align:middle">-44</td>
    <td style="font-size:0.4em; vertical-align:middle">131%</td>
    <td style="background:#7BFC45; text-align:center; vertical-align:middle; font-size:0.4em">OK</td>
  </tr>
<tr>
    <th align="left"; style="background:#BFBFBF; font-size:0.4em; vertical-align:middle"># CMs Oper</th>
    <td style="font-size:0.4em; vertical-align:middle">0</td>
    <td style="font-size:0.4em; vertical-align:middle">183</td>
    <td style="font-size:0.4em; vertical-align:middle">-183</td>
    <td style="font-size:0.4em; vertical-align:middle"></td>
    <td style="background:#7BFC45; text-align:center; vertical-align:middle; font-size:0.4em">OK</td>
  </tr>
  <tr>
    <th align="left"; style="background:#F2F2F2; font-size:0.4em; vertical-align:middle">Avg US RxPwr (CMTS)</th>
    <td style="font-size:0.4em; vertical-align:middle">0,00</td>
    <td style="font-size:0.4em; vertical-align:middle">140,92</td>
    <td style="font-size:0.4em; vertical-align:middle"></td>
    <td style="font-size:0.4em; vertical-align:middle"></td>
    <td style="background:#7BFC45; text-align:center; vertical-align:middle; font-size:0.4em">OK</td>
  </tr>
  <tr>
    <th align="left"; style="background:#F2F2F2; font-size:0.4em; vertical-align:middle">Avg US SNR (CMTS)</th>
    <td style="font-size:0.4em; vertical-align:middle">359,67</td>
    <td style="font-size:0.4em; vertical-align:middle">368,32</td>
    <td style="font-size:0.4em; vertical-align:middle"></td>
    <td style="font-size:0.4em; vertical-align:middle"></td>
    <td style="background:#7BFC45; text-align:center; vertical-align:middle; font-size:0.4em">OK</td>
  </tr>
  <tr>
    <th align="left"; style="background:#BFBFBF; font-size:0.4em; vertical-align:middle">Avg US TxPwr (CM)</th>
    <td style="font-size:0.4em; vertical-align:middle">470,30</td>
    <td style="font-size:0.4em; vertical-align:middle">444,91</td>
    <td style="font-size:0.4em; vertical-align:middle">-44</td>
    <td style="font-size:0.4em; vertical-align
      :middle">131%</td>
    <td style="background:#7BFC45; text-align:center; vertical-align:middle; font-size:0.4em">OK</td>
  </tr>
  <tr>
    <th align="left"; style="background:#BFBFBF; font-size:0.4em; vertical-align:middle">Ave DS RxPwr (CM)</th>
    <td style="font-size:0.4em; vertical-align:middle">25,46</td>
    <td style="font-size:0.4em; vertical-align:middle">35,49</td>
    <td style="font-size:0.4em; vertical-align:middle"></td>
    <td style="font-size:0.4em; vertical-align:middle"></td>
    <td style="background:#7BFC45; text-align:center; vertical-align:middle; font-size:0.4em">OK</td>
  </tr>
  <tr>
    <th align="left"; style="background:#BFBFBF; font-size:0.4em; vertical-align:middle">Ave DS RxPwr (CM)</th>
    <td style="font-size:0.4em; vertical-align:middle">384,96</td>
    <td style="font-size:0.4em; vertical-align:middle">413,17</td>
    <td style="font-size:0.4em; vertical-align:middle"></td>
    <td style="font-size:0.4em; vertical-align:middle"></td>
    <td style="background:#7BFC45; text-align:center; vertical-align:middle; font-size:0.4em">OK</td>
  </tr>
</table>

<p style="color:#c77b4a; font-size:12px; font-weight:bold; padding-top:10; padding-bottom:10">② <u>IP NULL</u></p>

<table border="1"; style="width:500px; line-height:8px">
<th style="color:#c77b4a; font-size:8; font-weight:bold; text-align:left">Cable Modems con IP Nulas al Cierre de la Ventana</th>
  <tr>
    <td style="font-family:Consolas,courier new; background:#f4f4f4; vertical-align:middle; text-align:left">
      <pre style="white-space:pre-line; line-height:8px; font-size:0.5em">
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
    </pre>
		</td>
  </tr>
</table>

<p style="color:#c77b4a; font-size:12px; font-weight:bold; padding-top:10; padding-bottom:10">③ <u>PRUEBAS DE CONECTIVIDAD (CM, INTERNET, MTA)</u></p>

<table border="1"; style="width:500px; line-height:8px">
<th style="color:#c77b4a; font-size:8; font-weight:bold; text-align:left">1. Ping a <a href="www.claro.com.ec">google.com</a> redes de Internet (públicas)</th>
  <tr>
    <td style="font-family:Consolas,courier new; background:#f4f4f4; vertical-align:middle; text-align:left">
      <pre style="white-space:pre-line; line-height:8px; font-size:0.5em">
RMD-ACC-U04041AB# ping 8.8.8.8 source-ip 100.77.146.1
Using Source-IP for cable-mac 0.0
Sending IP ping to:8.8.8.8 from 100.77.146.1
ping (8.8.8.8):100 data bytes!!!!!
5 packets transmitted, 5 packets received
round-trip min/avg/max = 8.985/9.189/9.553 ms
    </pre>
		</td>
  </tr> 
</table>
</ul>
<br>

<table border="1"; style="width:500px; line-height:8px">
<th style="color:#c77b4a; font-size:8; font-weight:bold; text-align:left">2. Ping a servidores de aprovisionamiento (DHCP)</th>
  <tr>
    <td style="font-family:Consolas,courier new; background:#f4f4f4; vertical-align:middle; text-align:left">
      <pre style="white-space:pre-line; line-height:8px; font-size:0.5em">
RMD-ACC-U04041AB# ping 192.168.9.193 source-ip 10.253.146.1
Using Source-IP for cable-mac 0.0
Sending IP ping to:192.168.9.193 from 10.253.146.1
ping (192.168.9.193):100 data bytes
!!!!!
5 packets transmitted, 5 packets received
round-trip min/avg/max = 8.985/9.189/9.553 ms
RMD-ACC-U04041AB# ping 192.168.9.194 source-ip 10.253.146.1
Using Source-IP for cable-mac 0.0
Sending IP ping to:192.168.9.194 from 10.253.146.1
ping (192.168.9.194):100 data bytes
!!!!!
5 packets transmitted, 5 packets received
round-trip min/avg/max = 9.029/9.269/9.662 ms
    </pre>
		</td>
  </tr>
</table>
<br>
<table border="1"; style="width:500px; line-height:8px">
<th style="color:#c77b4a; font-size:8; font-weight:bold; text-align:left">3. Estado de conexiones COPS</th>
  <tr>
    <td style="font-family:Consolas,courier new; text-align:left; background:#f4f4f4; vertical-align:middle; text-align:left">
      <pre style="white-space:pre-line; line-height:8px; font-size:0.5em">
RMD-ACC-U04041AB# show packetcable cops servers
Proto   Local Addr      Server Addr.Port       KA     PCMM   IPSec UpTime
Timer  PSID
------- --------------- ---------------------- -----  ------ ----- -----------------
PC vI09 10.156.165.3    172.22.4.66.3030         30s  N/A    No      0 days  0:36:10
5 packets transmitted, 5 packets received
round-trip min/avg/max = 9.029/9.269/9.662 ms
    </pre>
		</td>
  </tr>
</table>
<br>
<table border="1"; style="width:500px; line-height:8px">
<th style="color:#c77b4a; font-size:8; font-weight:bold; text-align:left">4. Ping a Servidores COPS desde red de MTA</th>
<tr>
    <td style="font-family:Consolas,courier new; text-align:left; background:#f4f4f4; vertical-align:middle; text-align:left">
    <pre style="white-space:pre-line; line-height:8px; font-size:0.5em">
RMD-ACC-U04041AB# ping 172.22.4.66 source-ip 10.155.40.1
Using Source-IP for cable-mac 0.0
Sending IP ping to:172.22.4.66 from 10.155.40.1
ping (172.22.4.66):100 data bytes
!!!!!
5 packets transmitted, 5 packets received
round-trip min/avg/max = 9.131/9.164/9.258 ms
    </pre>
		</td>
  </tr>
</table>

<p style="color:#c77b4a; font-size:12px; font-weight:bold; padding-top:10; padding-bottom:10">④ <u>URL TEST</u> 🌐</p>

<table border="1"; style="width:auto; line-height:8px">
  <tr>
    <th style="font-weight:bold; text-align:center; vertical-align:middle; font-size:0.4em"><a href="http://www.claro.com.ec" target="_blank">www.claro.com.ec</a></th>
    <th style="font-weight:bold; text-align:center; vertical-align:middle; font-size:0.4em"><a href="http://www.teleamazonas.com">www.teleamazonas.com</a></th>
    <th style="font-weight:bold; text-align:center; vertical-align:middle; font-size:0.4em"><a href="http://www.facebook.com">www.facebook.com</a></th>
  </tr>
    <tr>
    <td style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125735.png?raw=true"></td>
    <td style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306115528.png?raw=true"></td>
    <td style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125735.png?raw=true"></td>
  </tr>
    <tr>
    <th style="font-weight:bold; text-align:center; vertical-align:middle; font-size:0.4em"><a href="http://www.Formula1.com">www.Formula1.com</a></th>
    <th style="font-weight:bold; text-align:center; vertical-align:middle; font-size:0.4em"><a href="http://www.google.com">www.google.com</a></th>
    <th style="font-weight:bold; text-align:center; vertical-align:middle; font-size:0.4em"><a href="http://ww.youtube.com">ww.youtube.com</a></th>
  </tr>
    <tr>
    <td style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306115353.png?raw=true"></td>
    <td style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306115357.png?raw=true"></td>
    <td style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306115225.png?raw=true"></td>
  </tr>  
  </table>

<p style="color:#c77b4a; font-size:12px; font-weight:bold; padding-top:10; padding-bottom:10">⑤ <u>PING TEST TO TEST CDN</u> 🌐</p>

<table border="1"; style="width:auto; line-height:8px">
  <tr>
    <th style="font-weight:bold; text-align:center; vertical-align:middle; font-size:0.4em; white-space:pre-line"><a href="http://rr1---sn-xj0uxa-btxs.googlevideo.com">Youtube:
    rr1---sn-xj0uxa-btxs.googlevideo.com</a></th>
    <th style="font-weight:bold; text-align:center; vertical-align:middle; font-size:0.4em; white-space:pre-line"><a href="http://rr1---sn-xj0uxa-btxs.googlevideo.com">Facebook:
    rr1---sn-xj0uxa-btxs.googlevideo.com</a></th>
    <th style="font-weight:bold; text-align:center; vertical-align:middle; font-size:0.4em; white-space:pre-line"><a href="http://rr1---sn-xj0uxa-btxs.googlevideo.com">Netflix:
    rr1---sn-xj0uxa-btxs.googlevideo.com</a></th>
  </tr>
    <tr>
    <td style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306115211.png?raw=true"></td>
    <td style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306115225.png?raw=true"></td>
    <td style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306115233.png?raw=true"></td>
  </tr>
  </table>

<p style="color:#c77b4a; font-size:12px; font-weight:bold; padding-top:10; padding-bottom:10">⑥ <u>PARAMENTROS REFERENCIA UPSTREAM (US)</u> 🌐</p>

<table border="1"; style="width:auto; line-height:8px">
  <tr>
      <td style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125501.png?raw=true"></td>
      <td align="left"; style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125520.png?raw=true"></td>
</tr>
<tr>
      <td style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125600.png?raw=true"></td>
      <td align="left"; style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125607.png?raw=true"></td>
</tr>
<tr>
      <td style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125613.png?raw=true"></td>
      <td align="left"; style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125637.png?raw=true"></td>
</tr>
<tr>
      <td style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125649.png?raw=true"></td>
      <td align="left"; style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/Pasted%20image%2020250306125656.png?raw=true"></td>
</tr>
  </table>

<p style="color:#c77b4a; font-size:12px; font-weight:bold; padding-top:10; padding-bottom:10">⑦ <u>PARAMETROS REFERENCIA DOWNSTREAM (DS) 🌐</u></p>

<table border="1"; style="width:auto; line-height:8px">
<tr>
      <td align="left"; style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250306114236406.png?raw=true"></td>
      <td align="left"; style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250306114239811.png?raw=true"></td>
</tr>
<tr>
      <td align="left"; style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250306114244251.png?raw=true"></td>
      <td align="left"; style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250306114249653.png?raw=true"></td>
</tr>
  </table>
<br>

<p style="color:#bf4c58; font-size:12px; font-weight:bold; margin:0; padding:0px">☰ <u>EVIDENCIAS VIDEO</u></p>
<p style="color:#c77b4a; font-size:12px; font-weight:bold; padding-top:0; padding-bottom:10">① <u>TABLA RESUMEN STB</u></p>

<table border="1"; style="width:auto; line-height:8px">
<tr>
	<th colspan="7"; style="background:#97C5D7; font-weight:bold; text-align:center; vertical-align:middle; font-size:0.4em">SET TOP BOXES REGISTRADO</th>
</tr>
  <tr>
    <th colspan="2"; style="background:#B9D9E5; text-align:left; vertical-align:middle; font-size:0.4em">Variables</th>
    <th style="background:#7FAC53; text-align:center; vertical-align:middle; font-size:0.4em">PRE</th> 
    <th style="background:#DE8242; text-align:center; vertical-align:middle; font-size:0.4em">POST</th> 
    <th style="background:#A6A6A6; text-align:center; vertical-align:middle; font-size:0.4em">Var</th>
    <th style="background:#A6A6A6; text-align:center; vertical-align:middle; font-size:0.4em">% STB</th> 
    <th style="background:#A6A6A6; text-align:center; vertical-align:middle; font-size:0.4em">Status</th> 
  </tr>
  <tr>
    <th colspan="2"; style="background:#B9D9E5; text-align:left; vertical-align:middle; font-size:0.4em"># STB Nodo</th>
    <td style="background:white; text-align:center; vertical-align:middle; font-size:0.4em">6</td>
    <td style="background:white; text-align:center; vertical-align:middle; font-size:0.4em">6</td>
    <td style="background:white; text-align:center; vertical-align:middle; font-size:0.4em">0</td>
    <td rowspan="3"; style="background:white; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">100%</td>
    <td rowspan="3"; style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
  </tr>
  <tr>
    <th style="background:#B9D9E5; text-align:left; vertical-align:middle; font-size:0.4em"># STB Old US ID</th>
    <th style="background:#B1C595; text-align:center; vertical-align:middle; font-size:0.4em">1407</th> 
    <td style="background:white; text-align:center; vertical-align:middle; font-size:0.4em">72</td>
    <td style="background:white; text-align:center; vertical-align:middle; font-size:0.4em">66</td>
    <td style="background:white; text-align:center; vertical-align:middle; font-size:0.4em">-6</td>
  </tr>
  <tr>
    <th style="background:#B9D9E5; text-align:left; vertical-align:middle; font-size:0.4em"># STB new US ID</th>
    <th style="background:#EAB38A; text-align:center; vertical-align:middle; font-size:0.4em">1421</th> 
    <td style="background:white; text-align:center; vertical-align:middle; font-size:0.4em">0</td>
    <td style="background:white; text-align:center; vertical-align:middle; font-size:0.4em">9</td>
    <td style="background:white; text-align:center; vertical-align:middle; font-size:0.4em">9</td>
  </tr>
</table>

<p style="color:#c77b4a; font-size:12px; font-weight:bold; padding-top:0; padding-bottom:10">② <u>INFORMACION NODO A MIGRAR</u></p>

<table border="1"; style="width:auto; line-height:8px">
<tr>
	<th colspan="2"; align="center"; style="background:#97C5D7; text-align:center; vertical-align:middle; font-size:0.4em">DATOS DEL NODO</th>
</tr>
  <tr>
    <th style="background:#B9D9E5; text-align:left; vertical-align:middle; font-size:0.4em">Nodo RMD</th><td style="background:white; text-align:left; vertical-align:middle;  font-size:0.4em">RMD-ACC-U04041AB</td></tr><tr>
    <th style="background:#B9D9E5; text-align:left; vertical-align:middle; font-size:0.4em">Mac Address</th><td style="background:white; text-align:left; vertical-align:middle;  font-size:0.4em">C0:94:35:3A:60:90</td></tr><tr>
    <th style="background:#B9D9E5; text-align:left; vertical-align:middle; font-size:0.4em">IP Address</th><td style="background:white; text-align:left; vertical-align:middle;  font-size:0.4em">172.20.102.131</td></tr><tr>
    <th style="background:#B9D9E5; text-align:left; vertical-align:middle;  font-size:0.4em">Region</th><td style="background:white; text-align:left; vertical-align:middle;  font-size:0.4em">REGION1</td></tr><tr>
    <th style="background:#B9D9E5; text-align:left; vertical-align:middle;  font-size:0.4em">HUB</th><td style="background:white; text-align:left; vertical-align:middle;  font-size:0.4em">MARISCAL</td></tr><tr>
    <th style="background:#B9D9E5; text-align:left; vertical-align:middle;  font-size:0.4em">DS Plant</th><td style="background:white; text-align:left; vertical-align:middle;  font-size:0.4em">Quito Vhub 4</td></tr><tr>
    <th style="background:#B9D9E5; text-align:left; vertical-align:middle;  font-size:0.4em">US Plant</th><td style="background:white; text-align:left; vertical-align:middle;  font-size:0.4em">QUITO VH 4</td></tr><tr>
    <th style="background:#B9D9E5; text-align:left; vertical-align:middle;  font-size:0.4em">IP NC2000</th><td style="background:white; text-align:left; vertical-align:middle;  font-size:0.4em">192.168.7.10</td></tr><tr>
    <th style="background:#B9D9E5; text-align:left; vertical-align:middle;  font-size:0.4em">vARPD</th><td style="background:white; text-align:left; vertical-align:middle;  font-size:0.4em">q4_varpd1</td>
  </tr>
</table>

<p style="color:#c77b4a; font-size:12px; font-weight:bold; padding-top:0; padding-bottom:10">③ <u>VALIDACION VIA CLI</u></p>

<table border="1"; style="width:auto; line-height:8px">
  <tr>
    <th colspan="3"; style="background:#97C5D7; text-align:center; vertical-align:middle; font-size:0.4em">Variables</th>
  </tr>
  <tr>
    <th style="background:#B9D9E5; text-align:left; vertical-align:middle; font-size:0.4em">Aux Core IP</th>
    <td style="background:white; text-align:center; vertical-align:middle; font-size:0.4em">172.29.96.130</td>
    <td style="background:#7BFC45; text-align:center; vertical-align:middle; font-size:0.4em">OK</td>
  </tr>
  <tr>
    <th style="background:#B9D9E5; text-align:left; vertical-align:middle; font-size:0.4em">Aux Core State</th>
    <td style="background:white; text-align:center; vertical-align:middle; font-size:0.4em">Operational</td>
    <td style="background:#7BFC45; text-align:center; vertical-align:middle; font-size:0.4em">OK</td>
  </tr>
  <tr>
	<th style="background:#B9D9E5; text-align:left; vertical-align:middle; font-size:0.4em">ntp associated</th>
    <td style="background:white; text-align:center; vertical-align:middle; font-size:0.4em">*10.57.110.52</td>
    <td style="background:#7BFC45; text-align:center; vertical-align:middle; font-size:0.4em">OK</td>
  </tr>
<tr>
    <th colspan="3"; style="background:#97C5D7; text-align:center; vertical-align:middle; font-size:0.4em">Bandwidth</th>
  </tr>
  <tr>
	<th style="background:#B9D9E5; text-align:left; vertical-align:middle; font-size:0.4em">lag 0</th>
    <td style="background:white; text-align:center; vertical-align:middle; font-size:0.4em">2969,00 Mbps</td>
    <td style="background:#7BFC45; text-align:center; vertical-align:middle; font-size:0.4em">OK</td>
  </tr>
  <tr>
    <th colspan="3"; style="background:#97C5D7; text-align:center; vertical-align:middle; font-size:0.4em">Multicast</th>
  </tr>
  <tr>
	<th style="background:#B9D9E5; text-align:left; vertical-align:middle; font-size:0.4em">Broadcast</th>
    <td style="background:white; text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td>
    <td style="background:#7BFC45; text-align:center; vertical-align:middle; font-size:0.4em">OK</td>
  </tr>
  <tr>
  	<th style="background:#B9D9E5; text-align:left; vertical-align:middle; font-size:0.4em">Reg2 Broadcast</th>
    <td style="background:white; text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.35</td>
    <td style="background:#7BFC45; text-align:center; vertical-align:middle; font-size:0.4em">OK</td>
  </tr>
  <tr>
    <th style="background:#B9D9E5; text-align:left; vertical-align:middle; font-size:0.4em">Piolot Broadcast</th>
    <td style="background:white; text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.37</td>
    <td style="background:#7BFC45; text-align:center; vertical-align:middle; font-size:0.4em">OK</td>
  </tr>
    <tr>
    <th style="background:#B9D9E5; text-align:left; vertical-align:middle; font-size:0.4em">Downstream OOB</th>
    <td style="background:white; text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.77</td>
    <td style="background:#7BFC45; text-align:center; vertical-align:middle; font-size:0.4em">OK</td>
  </tr>
</table>

<p style="color:#c77b4a; font-size:12px; font-weight:bold; padding-top:0; padding-bottom:10">④ <u>VALIDACION CANALES DE BROADCAST, OOB, PILOT</u></p>

<table border="1"; style="width:auto; line-height:8px">
<tr>
	<th colspan="7"; style="background:#97C5D7; text-align:center; vertical-align:middle; font-size:0.4em">VTM configure</th>
<th colspan="7"; style="background:#97C5D7; text-align:center; vertical-align:middle; font-size:0.4em">RMD Configure</th>
</tr>
  <tr>
    <th style="background:#A6A6A6; text-align:center; vertical-align:middle; font-size:0.4em">ID</th>
    <th style="background:#A6A6A6; text-align:center; vertical-align:middle; font-size:0.4em; width:1px">Service Groups</th>
    <th style="background:#A6A6A6; text-align:center; vertical-align:middle; font-size:0.4em; width:10%">Session ID</th>
    <th style="background:#A6A6A6; text-align:center; vertical-align:middle; font-size:0.4em">Freq MHZ</th>
    <th style="background:#A6A6A6; text-align:center; vertical-align:middle; font-size:0.4em">Multicat address</th>
    <th style="background:#A6A6A6; text-align:center; vertical-align:middle; font-size:0.4em">UDP Port</th>
    <th style="background:#A6A6A6; text-align:center; vertical-align:middle; font-size:0.4em">DS P/TCH</th>
    <th style="background:#A6A6A6; text-align:center; vertical-align:middle; font-size:0.4em">Annex</th>
    <th style="background:#A6A6A6; text-align:center; vertical-align:middle; font-size:0.4em">InPackets received</th>
    <th style="background:#A6A6A6; text-align:center; vertical-align:middle; font-size:0.4em">OSS Packets</th>
    <th style="background:#A6A6A6; text-align:center; vertical-align:middle; font-size:0.4em">OverFlow Events</th>
    <th style="background:#A6A6A6; text-align:center; vertical-align:middle; font-size:0.4em">UnderFlow Events</th>
    <th style="background:#A6A6A6; text-align:center; vertical-align:middle; font-size:0.4em">Dropped Packets</th>
    <th style="background:#A6A6A6; text-align:center; vertical-align:middle; font-size:0.4em">Status</th>
  </tr>
  <tr>
	  <th colspan="14"; style="background:#97C5D7; text-align:center; vertical-align:middle; font-size:0.4em">BROADCAST CHANNELS</th>
  </tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-207 Mhz</td>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">8000fffa</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">207</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/122</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188547</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">2</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-213 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000fffd</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">213</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/110</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188622</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">3</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-219 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffef</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">219</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/103</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188658</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">4</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-225 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffee</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">225</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/106</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188646</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">5</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-231 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffed</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">231</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/94 </td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188709</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">6</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-237 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffd2</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">237</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/93 </td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188712</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">7</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-243 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffe1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">243</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/97 </td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188694</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">8</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-249 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffd9</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">249</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/117</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188571</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">9</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-255 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffe5</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">255</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/91 </td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188724</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">10</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-261 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffdd</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">261</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/126</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188532</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">11</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-267 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffea</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">267</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/121</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188556</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">12</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-273 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffe0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">273</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/100</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188673</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">13</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-291 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffe4</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">291</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/96 </td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188700</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">14</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-297 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffd6</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">297</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/118</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188568</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">15</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-303 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffda</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">303</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/113</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188598</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">16</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-309 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffe9</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">309</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/120</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188559</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">17</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-315 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffdf</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">315</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/124</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188544</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">18</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-321 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffd8</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">321</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/116</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188580</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">19</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-351 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffd5</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">351</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/102</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188664</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">20</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-363 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffdc</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">363</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/125</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188535</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">21</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-381 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffec</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">381</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/127</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188526</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">22</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-387 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffe6</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">387</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/92 </td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188718</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">23</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-393 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffdb</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">393</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/115</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188586</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">24</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-411 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffe3</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">411</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/95 </td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188703</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">25</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-429 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffe2</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">429</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/99 </td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188676</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">26</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-435 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffd7</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">435</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/119</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188565</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">27</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-441 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffe8</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">441</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/104</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188655</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">28</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-447 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffde</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">447</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/123</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188544</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">29</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-453 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffeb</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">453</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/111</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188607</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">30</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-465 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffd4</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">465</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/105</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188649</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">31</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-471 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffe7</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">471</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/109</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188628</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">32</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-477 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffd3</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">477</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/108</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188634</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">BC-483 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffd1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">483</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.33</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10033</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/98 </td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6188688</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<th colspan="14"; style="background:#97C5D7; text-align:center; vertical-align:middle; font-size:0.4em">REGIONAL BROADCAST CHANNELS</th>
  </tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em; width:11.2%">BC-333 REG Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffcf</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">333</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.35</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10035</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/101</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6187299</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em"></td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="text-align:center; vertical-align:middle; font-size:0.4em"></td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em"></td>
</tr>
<tr>
	<th colspan="14"; style="background:#97C5D7; text-align:center; vertical-align:middle; font-size:0.4em">DOWNSTREAM OOB CHANNEL</th>
  </tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">OOB-OM-MARISCAL</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000fffb</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">107,4</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.77</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10077</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/55-1/0 </td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">209054</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">n/a</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">n/a</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">n/a</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<th colspan="14"; style="background:#97C5D7; text-align:center; vertical-align:middle; font-size:0.4em">UPSTREAM OOB CHANNEL</th>
  </tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">Q4_VARPD1-US1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">AC146063</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">12,128</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">q4_varpd1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">N/A</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/55-1/2 </td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">n/a</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">n/a</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">n/a</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">n/a</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">n/a</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<th colspan="14"; style="background:#97C5D7; text-align:center; vertical-align:middle; font-size:0.4em">REGIONAL BROADCAST CHANNELS</th>
  </tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">Pilot 177 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffcd</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">177</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.37</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10037</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/107</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6187269</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">2</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">Pilot 861 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffcc</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">861</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.37</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10037</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/114</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6187221</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
<tr>
	<td style="text-align:center; vertical-align:middle; font-size:0.4em">3</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">Pilot 993 Mhz</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">8000ffcb</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">993</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">239.255.17.37</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">10037</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0/vid/112</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">B</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">6187230</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">1</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="text-align:center; vertical-align:middle; font-size:0.4em">0</td><td style="background:#7BFC45; text-align:center; vertical-align:middle; font-weight:bold; font-size:0.4em">OK</td>
</tr>
</table>

<p style="color:#c77b4a; font-size:12px; font-weight:bold; padding-top:0; padding-bottom:10">⑤ <u>PAQUETES FUERA DE SECUENCIA POR TRANSPORT STREAM</u></p>

<table border="1"; style="width:auto; line-height:8px">
<tr>
      <td align="left"; style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250307132155821.png?raw=true"></td>
</tr>
</table>

<p style="color:#c77b4a; font-size:12px; font-weight:bold; padding-top:0; padding-bottom:10">⑥ <u>PAQUETES DROPEADOS POR CANAL DE VIDEO</u></p>

<table border="1"; style="width:auto; line-height:8px">
<tr>
      <td align="left"; style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250307132303777.png?raw=true"></td>
</tr>
</table>

<p style="color:#c77b4a; font-size:12px; font-weight:bold; padding-top:0; padding-bottom:10">⑦ <u>PRUEBA DE SERVICIO CON STB DCX</u></p>

<table border="1"; style="width:auto; line-height:8px">
  <tr>
    <th style="font-weight:bold; text-align:center; vertical-align:middle; font-size:0.4em"><font color="blue">STB:000-01783-33438-127</font> <font color="#9bbb59">Comando:Refresh</font></th>
    <th style="font-weight:bold; text-align:center; vertical-align:middle; font-size:0.4em"><font color="#9bbb59">Respuesta</font></th>
  </tr>
<tr>
    <td style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250307132422325.png?raw=true"></td>
    <td style="text-align:center; vertical-align:middle"><img src="https://github.com/rodoxplo/daa/blob/main/template-daa-raw/IMG-20250307132406805.png?raw=true"></td> 
  </tr>
  </table>
<br>

<p style="color:#8abdb5; font-size:12px; font-weight:bold; margin:0; padding-top:40px">☰ <u>OBSERVACIONES</u></p>
<pre style="white-space:pre-line; line-height:8px; font-family:arial; font-size:10px; background:#ffffff;padding-top:10px">
➢ Se realizó la migración del nodo de manera exitosa.
➢ Se aplicó un soft reset al nodo para actualizar la configuración de la frecuencia 499.250 de manera exitosa.
</pre>
<br>

<p style="color:#8abdb5; font-size:12px; font-weight:bold; margin:0; padding-top:20">☰ <u>RESULTADO DEL TRABAJO</u></p>
<pre style="white-space:pre-line; line-height:8px; font-size:16px; font-family:arial; font-weight:bold; background:#ffffff; color:green">✅ EXITOSO</pre>
</body>
</html>
