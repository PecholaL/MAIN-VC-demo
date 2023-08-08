# MAIN-VC

## Abstract
<p align="justify">
demo: MAIN-VC
</p>

## Overview
<p align="justify">

</p>

![Model Architecture ](assets/image/fig1.jpg)
<p align="center">Figure.1 The architecture of MAIN-VC.</p>
<p>&nbsp;</p> 

## Samples
Audio samples are taken from the VCTK data set [1].

<script>
function pauseOthers(ele) {
    $("audio").not(ele).each(function (index, audio) {audio.pause();});
}
</script>

<style>
.main-content table {
    display: inline-table;
}
table {
    table-layout:fixed;
    width: 100%;
    overflow: hidden;
}
#player{
    width: 100%;
}
</style>


<table>
	<CAPTION>Table.1 Traditional Voice Conversion (seen speakers)</CAPTION>
    <tr>
        <th>  </th>
	<th> Source </th>
        <th> Target </th>
        <th> Baseline </th>
	<th> MAIN-VC </th>
    </tr>
<tr>
        <th> F2F </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/s2s_raw/p228_154.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/s2s_raw/p233_025.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/ADAINVC/s2s/p228_154_p233_025.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/MAINVC/s2s/F2Fp228_154_p233_025.mp3" type="audio/mpeg"></audio> </th>
</tr>
	
<tr>
        <th> M2M </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/s2s_raw/p374_070.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/s2s_raw/p286_028.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/ADAINVC/s2s/p374_070_p286_028.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/MAINVC/s2s/M2Mp374_070_p286_028.mp3" type="audio/mpeg"></audio> </th>
</tr>

<tr>
        <th> F2M </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/s2s_raw/p313_300.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/s2s_raw/p363_041.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/ADAINVC/s2s/p313_300_p363_041.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/MAINVC/s2s/F2Mp313_300_p363_041.mp3" type="audio/mpeg"></audio> </th>
</tr>
    
<tr>
        <th> M2F </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/s2s_raw/p270_234.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/s2s_raw/p265_148.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/ADAINVC/s2s/p270_234_p265_148.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/MAINVC/s2s/M2Fp270_234_p265_148.mp3" type="audio/mpeg"></audio> </th>
</tr>	
</table>

<p>&nbsp;</p> 

<table>
	<CAPTION>Table.2 One-shot Voice conversion (unseen speakers)</CAPTION>
    <tr>
        <th>  </th>
	<th> Source </th>
        <th> Target </th>
        <th> Baseline </th>
	<th> MAIN-VC </th>
    </tr>
<tr>
        <th> F2F </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/u2u_raw/p225_001.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/u2u_raw/p268_004.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/ADAINVC/u2u/p225_001_p268_004.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/MAINVC/u2u/F2Fp225_001_p268_004.mp3" type="audio/mpeg"></audio> </th>
</tr>
	
<tr>
        <th> M2M </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/u2u_raw/p345_112.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/u2u_raw/p360_012.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/ADAINVC/u2u/p345_112_p360_012.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/MAINVC/u2u/M2Mp345_112_p360_012.mp3" type="audio/mpeg"></audio> </th>
</tr>

<tr>
        <th> F2M </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/u2u_raw/p225_001.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/u2u_raw/p360_010.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/ADAINVC/u2u/p225_001_p360_010.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/MAINVC/u2u/F2Mp225_001_p360_010.mp3" type="audio/mpeg"></audio> </th>
</tr>
    
<tr>
        <th> M2F </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/u2u_raw/p345_058.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/u2u_raw/p268_062.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/ADAINVC/u2u/p345_058_p268_062.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/MAINVC/u2u/M2Fp345_058_p268_062.mp3" type="audio/mpeg"></audio> </th>
</tr>
</table>

<table>
	<CAPTION>Table.3 Cross-language One-shot Voice conversion (Chinese-to-English)</CAPTION>
    <tr>
	<th> Source </th>
        <th> Target </th>
	<th> MAIN-VC </th>
    </tr>
<tr>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/xlang_raw/IC0001W0001.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/xlang_raw/p247_001.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/MAINVC/xlang/IC0001W0001_p247_001.mp3" type="audio/mpeg"></audio> </th>
</tr>
	
<tr>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/xlang_raw/IC0002W0002.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/xlang_raw/p360_001.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/MAINVC/xlang/IC0002W0002_p360_001.mp3" type="audio/mpeg"></audio> </th>
</tr>

<tr>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/xlang_raw/IC0010W0010.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/xlang_raw/p244_001.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/MAINVC/xlang/IC0010W0010_p244_001.mp3" type="audio/mpeg"></audio> </th>
</tr>
    
<tr>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/xlang_raw/IC0001W0001.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/xlang_raw/p316_001.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/MAINVC/xlang/IC0001W0001_p316_001.mp3" type="audio/mpeg"></audio> </th>
</tr>
</table>

<p>&nbsp;</p> 

## Ablation Study
Compare  __MAIN-VC__ with: 
+ __model*__ the proposed method _without_ MI module,
+ __model**__ the proposed method _without_ siamese encoder.

<table>
	<CAPTION>Table.3 Ablation Study</CAPTION>
<tr>
	<th> Source </th>
        <th> Target </th>
	<th> MAIN-VC </th>
	<th> model* </th>
	<th> model** </th>
</tr>
<tr>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/u2u_raw/p225_001.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/u2u_raw/p268_004.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/ab1/p228_154_p233_025.mp3" type="audio/mpeg"></audio> </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/ab2/p228_154_p233_025.mp3" type="audio/mpeg"></audio> </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/MAINVC/u2u/F2Fp225_001_p268_004.mp3" type="audio/mpeg"></audio> </th>
</tr>
	
<tr>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/u2u_raw/p225_001.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/u2u_raw/p360_010.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/ab1/p225_001_p360_010.mp3" type="audio/mpeg"></audio> </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/ab2/p225_001_p360_010.mp3" type="audio/mpeg"></audio> </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/MAINVC/u2u/F2Mp225_001_p360_010.mp3" type="audio/mpeg"></audio> </th>
</tr>

<tr>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/s2s_raw/p345_112.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/s2s_raw/p360_012.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/ab1/p345_112_p360_012.mp3" type="audio/mpeg"></audio> </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/ab2/p345_112_p360_012.mp3" type="audio/mpeg"></audio> </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/MAINVC/u2u/M2Mp345_112_p360_012.mp3" type="audio/mpeg"></audio> </th>
</tr>
    
<tr>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/s2s_raw/p345_058.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/s2s_raw/p268_062.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/ab1/p345_058_p268_062.mp3" type="audio/mpeg"></audio> </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/ab2/p345_058_p268_062.mp3" type="audio/mpeg"></audio> </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/MAINVC/u2u/M2Fp345_058_p268_062.mp3" type="audio/mpeg"></audio> </th>
</tr>	
</table>

<p>&nbsp;</p> 



