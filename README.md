# Ideas    
*20-08-18*    
<ul>
 <li>Microarchitectural internal buffers introduced to optimize the performance of processors (e.g., Store buffer, Load buffer, Line fill buffer, etc...)
 currently become exploitable since side channel attacks(e.g., FLUSH+RELOAD), Meltdown, and Spectre were introduced.</li>    
</ul>    
20-08-20   
<ul>
 <li>Starting point to find a new attack can be finding a way to execute instruction sequences    
 that shouldn't be executed in normal condition and extract some data to covert channel. -> transient execution!    
 (어쩌면 이미 이러한 instruction sequence들이 인지되지 못한 채 빈번하게 cpu에서 실행되고 있을 수도 있다.)</li>    
 <li>Trying to Find a new covert channel also can be a good starting point.</li>    
 <li>Exploiting race condition and covert channel...</li>    
</ul>    
20-08-25    
<ul>
 <li>Some microarchitectural optimization techniques and attack mitigation techniques bring a new surface of attack...</li>
</ul>

# Objective  
*20-08-18*    
Finding a new attack vector exploiting microarchitectural side channel    
or    
Finding a new techinque that mitigates currently proposed microarchitectural side channel attacks    

# Plans
*20-08-18*    
Currently I studying... (see ./Papers directory)    
<ol>
  <li>Meltdown and Meltdown-like attacks to understand how currently proposed attacks work.</li>    
  <li>Intel microarchitecture to find a new exploitable point.</li>
</ol>

*
