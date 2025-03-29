**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[fv-az1374-136:63628] *** Process received signal ***
[fv-az1374-136:63628] Signal: Aborted (6)
[fv-az1374-136:63628] Signal code:  (-6)
[fv-az1374-136:63628] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3402645330]
[fv-az1374-136:63628] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f340269eb2c]
[fv-az1374-136:63628] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f340264527e]
[fv-az1374-136:63628] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f34026288ff]
[fv-az1374-136:63628] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3402aa5ff5]
[fv-az1374-136:63628] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3402abb0da]
[fv-az1374-136:63628] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3402aa5a55]
[fv-az1374-136:63628] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3402aa5a6f]
[fv-az1374-136:63628] [ 8] plumed(+0x146dd)[0x565315b606dd]
[fv-az1374-136:63628] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f340262a1ca]
[fv-az1374-136:63628] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f340262a28b]
[fv-az1374-136:63628] [11] plumed(+0x15365)[0x565315b61365]
[fv-az1374-136:63628] *** End of error message ***
</pre>
{% endraw %}
