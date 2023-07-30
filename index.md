<p align="justify">
demo: MAIN-VC
</p>

## Overview
<p align="justify">

</p>

## Model Architecture
<!-- <center class="half">
    <img src="assets/image/main-vc-overview.jpg" width="300"/>
    <img src="assets/image/fig2.jpg" width="300"/>
</center>       <p>&nbsp;</p> 
<p align="center">Figure.1 The architecture of MAIN-VC</p> -->

<p align="center">Figure.1 The architecture of MAIN-VC.</p>


<!-- ### General Digestive Metabolic Network

![Model Architecture ](assets/image/fig1.jpg)
<p align="center">Figure.1 The architecture of the general digestive metabolic network.</p>


## Samples
Audio samples are taken from the VCTK data set [1].


<p>&nbsp;</p> 

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
	<CAPTION>Table.1 Voice conversion.</CAPTION>
    <tr>
        <th> ID </th>
		<th> Ground Truth</th>
        <th> Tacotron2 </th>
        <th> Tacotron2+x-vector </th>
		<th> DMN</th>
        <th> FDMN </th>
    </tr>
    <tr>
        <th> text1 </th>
		<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Ground_Truth/30/0.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2/30/0.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2_x-vec/30/0.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/DMN/30/0.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/FDMN/30/0.mp3" type="audio/mpeg"></audio> </th>
    </tr>
	
	<tr>
        <th> text2 </th>
		<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Ground_Truth/30/1.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2/30/1.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2_x-vec/30/1.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/DMN/30/1.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/FDMN/30/1.mp3" type="audio/mpeg"></audio> </th>
    </tr>
	
	
	<tr>
        <th> text3 </th>
		<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Ground_Truth/30/2.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2/30/2.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2_x-vec/30/2.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/DMN/30/2.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/FDMN/30/2.mp3" type="audio/mpeg"></audio> </th>
    </tr>
	
	
	<tr>
        <th> text4 </th>
		<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Ground_Truth/30/3.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2/30/3.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2_x-vec/30/3.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/DMN/30/3.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/FDMN/30/3.mp3" type="audio/mpeg"></audio> </th>
    </tr>
	
	
	<tr>
        <th> text5 </th>
		<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Ground_Truth/30/4.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2/30/4.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2_x-vec/30/4.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/DMN/30/4.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/FDMN/30/4.mp3" type="audio/mpeg"></audio> </th>
    </tr>
	
	
	<tr>
        <th> text6 </th>
		<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Ground_Truth/30/5.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2/30/5.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2_x-vec/30/5.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/DMN/30/5.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/FDMN/30/5.mp3" type="audio/mpeg"></audio> </th>
    </tr>	
</table>


<p>&nbsp;</p> 


<table>
	<CAPTION>Table.2 One-shot Voice Conversion</CAPTION>
    <tr>
        <th> ID </th>
		<th> Ground Truth</th>
        <th> Tacotron2 </th>
        <th> Tacotron2+x-vector </th>
		<th> DMN</th>
        <th> FDMN </th>
    </tr>
    <tr>
        <th> text1 </th>
		<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Ground_Truth/100/0.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2/100/0.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2_x-vec/100/0.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/DMN/100/0.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/FDMN/100/0.mp3" type="audio/mpeg"></audio> </th>
    </tr>
	
	<tr>
        <th> text2 </th>
		<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Ground_Truth/100/1.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2/100/1.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2_x-vec/100/1.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/DMN/100/1.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/FDMN/100/1.mp3" type="audio/mpeg"></audio> </th>
    </tr>
	
	
	<tr>
        <th> text3 </th>
		<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Ground_Truth/100/2.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2/100/2.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2_x-vec/100/2.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/DMN/100/2.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/FDMN/100/2.mp3" type="audio/mpeg"></audio> </th>
    </tr>
	
	
	<tr>
        <th> text4 </th>
		<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Ground_Truth/100/3.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2/100/3.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2_x-vec/100/3.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/DMN/100/3.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/FDMN/100/3.mp3" type="audio/mpeg"></audio> </th>
    </tr>
	
	
	<tr>
        <th> text5 </th>
		<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Ground_Truth/100/4.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2/100/4.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2_x-vec/100/4.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/DMN/100/4.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/FDMN/100/4.mp3" type="audio/mpeg"></audio> </th>
    </tr>
	
	
	<tr>
        <th> text6 </th>
		<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Ground_Truth/100/5.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2/100/5.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/Tacotron2_x-vec/100/5.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/DMN/100/5.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audios/FDMN/100/5.mp3" type="audio/mpeg"></audio> </th>
    </tr>	
</table>

<p>&nbsp;</p> 



